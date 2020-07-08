# tonyproject

To run the code, please follow this intruction.

Step 1: Upload dataset to drive and run the model through google colab or use from computer.
Step 2: Change directory to dataset in 
  image_paths = list(paths.list_images("/content/occupation")) #directory
Step 3: Load one of 5 pre-trained models: VGG16, VGG19, Resnet50, Xception, InceptionV3
  base_model = InceptionV3(weights="imagenet", include_top=False, input_tensor=Input(shape=(224, 224, 3)))
Step 4: Predicting futher dataset from pre-trained model.
