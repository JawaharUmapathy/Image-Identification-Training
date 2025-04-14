# Image-Identification-Training
This is a repo created to help beginners who struggle with training V3 Inception learning set for training a group of image dataset which can be easily downloaded from the kaggle and imported into google colab without the need of downloading in local machine and obtaining the trained dataset at the end(Uses T4 GPU hence the GPU need to be selected)
*The reference are taken from the following youtube video "https://youtu.be/chQNuV9B-Rw?si=2Y9h-ErzezMdq1ZH"
If you face any issue like two copies of dataset being copied then follow the following steps to avoid :
Step 1:Navigate to the kaggle folder (Refer the Path.png)
Step 2:Copy the path and create a new variable path1 or something
Step 3:"shutil.copytree(path, custom_path)" replace the path1 variable in the path1
