&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;__Hi👋__，欢迎来到这个关于使用 树莓派4B 实现检测人体是否摔倒项目的教程！这次的项目系列将分为三个部分，而今天你将进入第二个部分，实现核心功能，训练好数据，训练好后保存为cvs文件，再打开自己的摄像头进行验证。  
  接下来，将通过以下几个步骤📜，带你深入源码，轻松上手这个项目！准备好了吗？让我们开始吧🚀！  

- 🚀 打开远程
- 打开摄像头
- 配置vscode
- 使用vscode运行
- 🔧 使用说明
- - #注：本项目是基于KNN_人体3D识别骨架的项目进行修改，展示了在树莓派上如何展示的全教学过程。




打开远程：  
![82990c40bce1d5be8c360ba056338d25](https://github.com/user-attachments/assets/cec0a368-4f14-44ba-962c-bc4a5e0921d1)  

打开摄像头步骤：  
![9c0e721c3f94b627fbdb724d603371dc_720](https://github.com/user-attachments/assets/a193f9e8-d4eb-4a9c-8845-c5084e809d11)   
![b2a24c5c7c22cb5aba1b6f481550edd0_720](https://github.com/user-attachments/assets/8c07e88d-383f-45b5-823d-7dc8498c10d9)   
![d15f0dc4e379cefef9fd5be1c07ea376_720](https://github.com/user-attachments/assets/368f96ad-6e79-450c-9deb-be89f488f3cd)   

![b24b0293acafce3bc31c192cc4b936dc_720](https://github.com/user-attachments/assets/c0374e32-99a7-4f82-9cdf-e530fc689b8b)   
![e16696d17803db088ca54a734c738734_720](https://github.com/user-attachments/assets/db3541a1-9984-4921-b087-f9a26a6a4c26)  

树莓派上的IDE python运行位置：  
![cad7f71ca307bc83acc661290aa79f46_720](https://github.com/user-attachments/assets/c712ccad-a02f-4b49-8583-6b7db1d85103)  

配置code:好处，改报错更加方便：  
![image](https://github.com/user-attachments/assets/0296ca26-4ec2-44ed-9d7f-1b638cccae26)  
打开过程：  
![image](https://github.com/user-attachments/assets/31c92f39-8236-4eb4-a818-a11273778458)  


安装成功后：运行test.py    
![image](https://github.com/user-attachments/assets/ea277509-b497-4b76-8566-23958d801273)  

![image](https://github.com/user-attachments/assets/e1fd0d58-100b-4a9d-9c0f-8c8b502a46c4)  

### 编译运行    
1.先运行测试代码test.py，确保摄像头能够成功使用。  
2.运行First_train.py文件，训练数据后保存人体节点为1_Fall.csv和2_Normal.csv文件，用户按下 Esc 键时直接退出并保存结果。  
3.运行second_KNN.py文件，使用KNN模型调配。
3.进行验证运行Third.py文件，可以上传一段具有完整人体节点的视频或者打开自己的摄像头进行测试。  

![image](https://github.com/user-attachments/assets/300989ab-8395-4a6d-b718-8fc19c8fdcb0)  


最后结果为：  
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

