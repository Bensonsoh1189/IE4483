# IE4483
IE4483 Artificial Intelligence and Data Mining Project
Instruction to run code:

There are two main functions in the repo  
training,ipynb
predict.ipynb

To start training using the YoloV8 model,  
run the training,ipynb file. 
Change the "Data" directory to where your dataset is saved to  
Ensure dataset is split into two seperate files namely 'train', and 'val'.  
Edit the Epoch and imgsz to suit your training perference.  
A seperate files with directory ./runs/classify/train will be saved in the same directory  
within the the train, you can view the model training weights, the results and the confusion matrix.  

To do prediction on a test dataset after training the YoloV8 Model,  
Under "model", load the custom model with the directory of your training weight files from your previous training.  
Change and specify the directory of your testing dataset under "image_folder"  
and specify the directory to save the results of the output folder name  
