# tonyproject

**To run the code, please follow this intruction.**

Step 1: Upload dataset to drive and run the model through google colab or use from computer.<br/>
Step 2: Change directory to dataset in<br/> 
  - image_paths = list(paths.list_images("/content/occupation")) #directory<br/>

Step 3: Load one of 5 pre-trained models: VGG16, VGG19, Resnet50, Xception, InceptionV3<br/>
  - base_model = InceptionV3(weights="imagenet", include_top=False, input_tensor=Input(shape=(224, 224, 3)))<br/>
<a/>
Step 4: Predicting futher dataset from pre-trained model.<br/>
