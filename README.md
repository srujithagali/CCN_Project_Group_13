# CCN_Project_Group_13
As I can’t upload 350 mb file in github, I am pasting the link of google drive to download the project.
Link: https://drive.google.com/file/d/13Hg8gJ3OpBB3lh3bkIAvGwZniarinNkv/view?usp=share_link


Steps to follow:
1.	Download zip file from google drive and extract them
2.	Set the path to the folder in terminal and start downloading python 3.9
3.	Navigate to face alignment folder
4.	Then import all libraries in requirements.txt file.
5.	Try running the project. There will be some issues with the libraries. So imort all the extra libraries like pytorch, flask and tkinter, etc…
6. You can first try and check whether the code is running by using th following command in cmd: "CUDA_VISIBLE_DEVICES=0 python demo.py  --config config/vox-adv-256.yaml --driving_video path/to/driving --source_image path/to/source --checkpoint path/to/checkpoint --relative --adapt_scale --kp_num 15 --generator DepthAwareGenerator". ** This step not necessary. This is just to test whether the model is running or not.** 
7. If the code is runnung perfectly then go to the next steps.
8.	As I already integrated the trained check points, you can directly run the project using “vig.py” python file and the project starts running and the web interface pops up.
9.	Upload the image and video from the folder given and the output will be playing in vlc media player.

****Nvidia is mandatory as CUDA libraries are used in this model****
****I have already integrated the trained checkpoints as well so the project should work fine****
Any doubt. Please contact on vigneshramisettyrsv1234@gmail.com. 
