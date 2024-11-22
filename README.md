&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Hi👋, welcome to this tutorial on using the Raspberry Pi 4B to detect if a person has fallen! This project will be split into three parts, and today you will dive into the second part, which involves implementing the core functionality: training the data, saving it as a CSV file, and then using your camera for validation. 

Next, we will take you step-by-step 📜 through the source code, making it easy for you to get started with this project! Are you ready? Let’s get started 🚀!

- 🚀 Open Remote
- Open the Camera
- Configure VSCode
- Run with VSCode
- 🔧 Usage Instructions
- Note: This project is a modification of the KNN 3D Human Skeleton Recognition project, demonstrating the full tutorial on how to run it on a Raspberry Pi.  




Open Remote：    
![82990c40bce1d5be8c360ba056338d25](https://github.com/user-attachments/assets/cec0a368-4f14-44ba-962c-bc4a5e0921d1)    

Steps to Open the Camera：    
![9c0e721c3f94b627fbdb724d603371dc_720](https://github.com/user-attachments/assets/a193f9e8-d4eb-4a9c-8845-c5084e809d11)     
![b2a24c5c7c22cb5aba1b6f481550edd0_720](https://github.com/user-attachments/assets/8c07e88d-383f-45b5-823d-7dc8498c10d9)     
![d15f0dc4e379cefef9fd5be1c07ea376_720](https://github.com/user-attachments/assets/368f96ad-6e79-450c-9deb-be89f488f3cd)     

![b24b0293acafce3bc31c192cc4b936dc_720](https://github.com/user-attachments/assets/c0374e32-99a7-4f82-9cdf-e530fc689b8b)       
![e16696d17803db088ca54a734c738734_720](https://github.com/user-attachments/assets/db3541a1-9984-4921-b087-f9a26a6a4c26)    

IDE Python Running Location on Raspberry Pi：      
![cad7f71ca307bc83acc661290aa79f46_720](https://github.com/user-attachments/assets/c712ccad-a02f-4b49-8583-6b7db1d85103)    

Configure Code: Benefits, Easier Error Fixing：    
![image](https://github.com/user-attachments/assets/0296ca26-4ec2-44ed-9d7f-1b638cccae26)  
Opening Process：  
![image](https://github.com/user-attachments/assets/31c92f39-8236-4eb4-a818-a11273778458)  


Installation Success: Run test.py    
![image](https://github.com/user-attachments/assets/ea277509-b497-4b76-8566-23958d801273)   

![image](https://github.com/user-attachments/assets/e1fd0d58-100b-4a9d-9c0f-8c8b502a46c4)    

### Compile and Run    
1.First, run the test code test.py to ensure the camera works correctly.  
2.Run the First_train.py file to train the data, and save the human body keypoints as 1_Fall.csv and 2_Normal.csv files. The user can press the Esc key to exit and save the results.  
3.Run the second_KNN.py file to use the KNN model for configuration.  
4.Run the Third.py file for verification. You can upload a video with complete human keypoints or open your camera for testing.   

![image](https://github.com/user-attachments/assets/300989ab-8395-4a6d-b718-8fc19c8fdcb0)    


Final Result (includes GIF files) 
![img_v3_02gs_c205fc8a-26f5-41d1-b66b-d4dd3a21858g](https://github.com/user-attachments/assets/94578e53-b6e0-4bce-b1ee-22cd2682ee5b)





## 如何联系维护者或开发者
__OpenELAB:__   
[![OpenELAB_logo_resized_150](https://github.com/user-attachments/assets/5d3de375-359c-46a3-96bb-aaa211c6c636)](https://openelab.io)  
__YouTube:__  
[![youtube_logo_200x150](https://github.com/user-attachments/assets/d2365e7f-4ffe-4124-bf62-21eba19a71e4)](https://www.youtube.com/@OpenELAB)  
__X :__  
[![X_logo_150x150](https://github.com/user-attachments/assets/4ad5095f-2573-4791-9360-b355530093bf)](https://twitter.com/openelabio)  
__FaceBook:__  
[![facebook_logo_cropped_150x150](https://github.com/user-attachments/assets/52f2dc9a-a564-49a5-b72e-30eafbbc281f)](https://www.facebook.com/profile.php?id=61559154729457)  
__Discord__  
[![resized_image_150x150](https://github.com/user-attachments/assets/93ecd098-3391-45bb-9d80-b166c197a475)](https://discord.gg/VQspWyck)  

__源码改自于__
[M5StickCPlus](https://github.com/Sarah-C/M5StickC_Plus_Slot_Machine)

