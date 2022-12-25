
This projet is developed during Labs of the subject IoT Architecture

By:
Mtir Tasnim
Under-graduated student, 
Embadded system and IoT Bachelors 


Under the supervision of:
Amira Henaien, 
Computer Science, Assistant Professor,
Higher Institute of Computer Science Mahdia(ISIMA),
University of Monastir Tunisia


Title of the project:
 SmartDoorbell

Description:
a smart doorbell which can send notification to the phone when someone presses the doorbell

Objectif:
capture the photo ; send it to the user ; give them the choice to unlock or lock the door

List of devices:


esp32-cam


Electronic Lock


Push Switch


battery


Installation and prepartion instrcutions: 


1)Configure the Telegram App :


a) Create a New BOT in Telegram App 
              
              
              1) Search for BotFather in Telegram
              
              
              2) Tap on START.
               
               
              3) Type /newbot
               
               
              4) name the BOT(should be unique)
              
              
              5) enter a username
              
              
              6) copy the token 
               
![photo1671976575 (1)](https://user-images.githubusercontent.com/121382849/209470961-6ea8ade4-8d10-4c49-8564-b96370aac199.jpeg)


 ![photo1671976575](https://user-images.githubusercontent.com/121382849/209470964-975fc083-89fb-4864-a239-e86a7ed01a81.jpeg)


b)Get the User Id in Telegram App

                   
               1)Search for IDBot in Telegram
               
               
               2)Tap on START
               
               
               3)Tap on the /getid in IDBot
               
               
               4) copy the User ID
               




![photo1671977904](https://user-images.githubusercontent.com/121382849/209471652-8a79a0c3-e951-4aad-80d9-2cb493719d9c.jpeg)



2)Program ESP32-CAM with Arduino IDE


I have uploaded the code to ESP32-CAMM using the ESP32-CAM-MB USB (you can also use the FTDI232  or Arduino UNO to program ESP32CAM)


For this ESP32-CAM project, I have used the UniversalTelegramBot library (  you have to download and install it )

after uploading the code on the ESP32 it must be connected with the circuit and then tap on start on the bot i have created .


If the BOT is connected with ESP32CAM, you will get following message:




![photo1671977904](https://user-images.githubusercontent.com/121382849/209472133-020f7996-8e93-49a5-92cd-2a31327a0bb0.jpeg)







