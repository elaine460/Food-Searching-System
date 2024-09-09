[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XUsNR_oc)
## Requirements for Group Project
[Read the instruction](https://github.com/STIW3054-A222/class-activity-activityteam/blob/main/GroupProject.md)

## Group Info:
1. Matric Number & Name & Photo & Phone Number
1. Mention who is the leader.
1. Other related info (if any)

|     | Matric Number | Name                         | Role   | Phone Number | Photo |
|-----|---------------|------------------------------|--------|--------------|-------|
| 1.  | 277338        | Chow Jing Qi                 | Leader | 017-4008728  |   ![277338](https://user-images.githubusercontent.com/77046925/235867163-2acb3a3c-2131-447f-8a18-db047fd611a8.jpeg)    |
| 2.  | 279241        | Lew Elaine                   | Member | 018-9158226  |    ![profileImg279241](https://user-images.githubusercontent.com/102460032/235869124-31ecf04b-4735-4e13-9b64-beee8d374b91.jpg)     |
| 3.  | 280507        | Noor Shahida Bt Sharizal     | Member | 017-4311078 |   ![student](https://user-images.githubusercontent.com/103965506/235957256-43ce9899-c88c-4a14-8db8-c151eb96fff7.jpg)
| 4.  | 280213        | Siti Nur Aishah Bt Abd Latif | Member       | 013-3204030             |    ![myself](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103985766/df680869-0af7-405d-8a27-fb4cf25d517b)|
| 5.  | 280579        | Farah Binti Abd Aziz         | Member | 011-10384545 | ![farah_photo](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/26c1f50b-f390-4979-9da3-cb9d8d066c80) |

## Title of your application (a unique title)
TasteBot

## Abstract (in 300 words)
   1. Background
   
      TasteBot also pronounce as taste bud, is a food searching system that can interacts with cafe admin and students from Universiti Utara Malaysia(UUM). A system administrator is the one who has control over the system. TasteBot simplifies the process of gathering information by allowing students to discover menu provided by each cafe instantly instead of manually visit. The project is developed using combination of Java and Telegram Bot. 
   
   2. Problem Statement (from article or news paper or social media)

      The current dining experience for students at the UUM campus lacks an efficient and user-friendly system for searching and accessing food options. The absence of a system leads to difficulties in finding relevant information about cafeterias, menus, feedback, ratings and availability. Therefore, there is a need to develop a Food Searching System using a Telegram Bot to address these issues and enhance the dining experience for UUM students. When the system is utilized effectively, it has the potential to contribute to the prosperity of any organization (Dziadkiewicz et al., 2016).
   3. Main objective

      To develop a user-friendly system for food searching using Telegram bot which helps the UUM students discovering relevant information of the cafeterias. The bot provides convenient access to menus, operating hours, and user reviews, while promoting cafeteria owners' business growth.
   5. Methodology

      This project follows an agile methodology, including planning, development, review, and post-mortem. The project begins with an initial planning phase, where the vision, goals, and product backlog are defined. Testing, documentation, and knowledge sharing ensure a flexible and collaborative approach to deliver a high-quality Food Searching System for UUM using Telegram Bot.
   7. Result

      The queries implemented in TasteBot are able to be fetch and return accurate result accordingly. It has significantly reduces students' effort in accessing food options on campus. The overall dining experience is enhanced and contributed positive impacts toward the cafe owners.
   
   9. Conclusion
      
      In conclusion, the Food Searching System for UUM using Telegram Bot is successfully developed and enhances the dining experience for students at Universiti Utara Malaysia. It enables easy food search, menu browsing, comments, and ratings. The system provides efficient management for Cafe_Admin, user interaction, and reliable data storage.

## Flow Diagram of the requirements (MUST be included in your presentation)
![TasteBot Flow Diagram](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/f459b44c-fec8-481c-83fd-ea9b1f97b9bf)

## Use Case Diagram
![RTUseCaseFinal](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/b4393999-60b9-4561-aebb-1fbf9e05fc42)


## UML Class Diagram
![image](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103965506/79ff7cf5-2ec0-4f12-8c70-5c713104ce59)

## Database Design
![image](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/5611081b-8fbc-4b19-a3db-ccb688dc2bbb)

## JavaDoc
![Screenshot (66)](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103965506/83545862-c027-4f1e-bcad-302763f2497c)

## User manual for installing your application on Heroku Server (Bonus 5%)

## User manual/guideline for testing the system

**1. BOT ACCESS**

Launch the Telegram and search for our bot name "TasteBot” to access the UUM Food Searching System. Once you are in the telegram bot page, you can start using it by clicking “/start” to interact with the bot. 

**2. CAFE ADMIN FUNCTIONS**

Bot will prompt you to enter user type. Enter “Cafe_Admin” to proceed.

![cafe admin (1)](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103965506/5dd64866-9afa-4897-ad70-aa926b797e75)

   ***Figure 1 : Cafe Admin's Greeting Message***

      2.1 Register Cafe Admin 

In order to register as cafe admin, the staff have to get a successful approval of cafe_admin possition application from the system_admin. After getting the successful approval, you have to enter "1" and provide required information including email address, name, office phone number, mobile phone number, cafe name, inasis name, location link, open time, close time, and holiday status during the registration process. Registration is completed once the Bot displays successfully registered message. Once the registration successful, then now you may manage the food details by inputing information of your food items in cafeteria such as food type, food name, food price, food image, and food status.

      2.2 Managing Food Information

Refer to figure 1, you can enter “f” if you wish to add, update or delete food information. You need to reply your staff name accordingly and if it is available in the database, bot displays a message “Please proceed by choose(1:Add, 2: Update, 3:Delete)”. 

**Function 1 : Add Food**

To add food information, you can choose and click on “1: Add Food” from the inlined keyboard displayed. Then, you have to enter necessary food details based on the food type, food name, food price, food image(optional) and food status. Bot will display successful message if your food details have been saved into the database.

**Function 2: Update Food**

To update food information, you can choose and click on “2: Update” from the inlined keyboard displayed. The Bot will display food details, you are given two options either to update food price or food status. Choose “1:Update Food Price” to update the food price. Then, you need to provide food name to update its price and enter the new price. Bot will display successfully updated message. Same step used for updating food status, choose “2:Update Food Status”. Then, you need to provide food name to update its status and enter the new status. Bot will display successfully updated message.

**Function 3: Delete Food**

To delete food information, you can choose and click on “3: Delete” from the inlined keyboard displayed.Then, provide the email address to the bot and the bot will send a list of food items that have been added by using the email_address given. After that, you need to provide food name to be deleted. If the food name entered found in database, bot will display message that your food has been successfully deleted.

      2.3 View User's Comment and Rating

Refer to figure 1, you need to enter "c" to view user comments of food. Bot will display all of the food comment available from each inasis. To view the rating, you have to enter "r". Bot will display all of the food rating available from each inasis too.

      2.4 Sending Daily Status Updates

As a cafe admin, you can send status updates such as promotions or emergency closures that will be pushed to all users daily at 8.00 in the morning. 

**3. USER FUNCTIONS**

Bot will prompt you to enter user type. Enter “User” to proceed.

![user](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103965506/eeebf5fe-297a-4509-9af4-7fefbe8eba2b)

   ***Figure 2 : User's Greeting Message***

      3.1 Requesting Cafe Admin Application Approval 

Refer to Figure 2, you can enter "1" to request approval to apply for the cafe admin position. The bot will display a confirmation message, and you need to enter "1" to proceed. Afterward, you will be prompted to enter your email address, and the bot will send your approval submission to the system admin for review and approval. The applicant can always refer to the staff's email if they have forgoten their staff's email by clicking the embedded button to display the satff's email. If the applicant can remember their email_address, just input the email_address to proceed. If the staff email address is existing in tbl_staff and not beeen applied for the Cafe_Admin registration, the application will be submitted to the system successfully, then the system will display a success message. 

      3.2 Viewing Food Details

Refer to Figure 2, you can view list of food available at each cafeteria by entering “2”. The bot will send a message to ask whether the user want to view food at which inasis. The user have to input the number corresponding to the inasis. Then, the bot will display the list of food from the inasis and also display the cafe name, food type, food name, food price, and also food status.


      3.3 View Location of Inasis
      
Refer to Figure 2, you can enter "3" to view the location of each inasis (cafeterias). Then, the bot will display a list of cafe names along with their corresponding location links. You can simply click on the provided location link and it will redirect you to Google Maps, where you can access directions to the respective cafeterias.

      3.4 Providing Comments, Ratings and View Best Food

You can leave comment, give rating and view best food suggestions by entering “4” refer to Figure 2. Bot then will display list of food details from different inasis and give three criteria options :

**Function 1 : Leave Comment**

To provide comments for the food you have tried, click on the 1st button in inline keyboard, which is "1:Leave comment" from the options given. Before writing your comments, you need to enter the food ID. If the food id entered is present in database, your comment will be save. The bot will display the message "Added comment successfully." Otherwise, you need to enter existing food id to comment the food.

**Function 2 : Give Rating**

To give rating for the food you have tried, click on the 2nd button in inline keyboard, which is "2: Give rating" from the options given. In order to rate the food that you have tried, the user have to input the food id and also the rating. If the food id entered is present in database, your rating will be save . Then, the bot will display the message "Rating added successfully." Otherwise, you need to enter existed food id to rate the food.

**Function 3 : Best Food Suggestions**

To view best food suggestions from all inasis, choose and click on "3 : Best Food Suggestion" from the options given in inline keyboard button. Then, the bot will display a confirmation message for you to view that suggestion. Enter "1" to proceed and you will see list of food items in ascending order of price, along with the top 3 best food suggestion based on price and rating.

**4. SYSTEM ADMIN FUNCTIONS**

Bot will prompt you to enter user type. Enter “System_Admin” to proceed.

![system admin (1)](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103965506/489f0e5e-5453-4ff8-a6a8-14f4078e51d0)

   ***Figure 3 : System Admin's Greeting Message***

      4.1 Managing Cafe Admin Application
      
**Function 1 : Approve Cafe Admin application**

In order to approve the cafe_admin aplication, there are two criteria that have to be followed. The first one is choose inasis to view if there is any application. The second criteria is you may approve only one staff from each inasis. The system_admin will rely 1 to approve the applicants's application for cafe_admin's position. The system_admin have to select the inasis'name which is corresponding to the applicant's inasis by replying the number. The bot will send a record of applicant that exist in database. The system_admin have to send the email address of the applicant that want to approve to the system. Then the bot will dislay cafe_admin application approval successful message. 

**Function 2 : Viewing Cafe Admin Information**

Refer to Figure 3, you are given the authority to access all information provided by cafe admin by entering “2”. Bot will display their name, email, office phone number, mobile phone number, cafe name and inasis name.

**Function 3 : Delete Cafe Admin Registration**

Refer to Figure 3, you can enter “3” to delete a cafe admin. Bot will display list of cafe admins and their information. You can delete their record by entering their respective email address. Bot will display successfully deleted message if email address is found.
      
      
      
## Result/Output (Screenshot of the output)

For User:

User reply 1 to request approval

![CafeAdminAppication2](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/8043791f-481d-4196-9204-dca6656cf5a3)


Bot display message and option

![CafeAdminAppication3](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/982154b0-4c15-4f9e-8dad-4d51c61c25e4)


User make reply 1

![CafeAdminAppication4](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/707813d4-e788-404a-8f0a-c8260a63cede)


Bot send user input email message with embedded display email button

![CafeAdminAppication5](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/97887230-9fec-49f9-9d2f-e8c2720167b3)

List of email is being sent to user

![CafeAdminAppication6](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/e499d926-3cdb-44f1-9be9-cbd80380275b)


User, which is also the staff, choose their own email and send back to bot for Cafe_Admin position approval

![CafeAdminAppication7](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/705d255b-0bfe-493c-8ada-2d68130ec767)

Showing that application/request has been sent to the system successfully

![CafeAdminAppication8](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/885a999b-3f32-4d36-95df-ebcdf7dc0f6b)


For System_Admin:

System_Admin repy 1 to approve the applicant's applicantion for Cafe_Admin position

![OnlyAcceptOneCafeAdmin1](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/d65233aa-1b93-400b-a201-a84c43ac2156)


System_Admin have to select the Inasis applied by the applicant by inputting respective number

![ApproveOneCafeAdminApplication1](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/476d1cad-ae86-498d-9ec6-8191f3225107)


Bot display record of applicant

![ApproveOneCafeAdminApplication2](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/756af554-6606-4edc-8994-633f572cc360)


The system_admin have to send the email address of the applicant that he/she want to approve to the bot

![ApproveOneCafeAdminApplication3](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/e041437e-9273-4480-8cd4-7ac7dcf48608)


Bot display Cafe_Admin application approval successful message

![ApproveOneCafeAdminApplication4](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/543fdbe9-1602-49fe-8c36-b1d48fb0fffa)


Case: System_Admin can only approve 1 Cafe_Admin position application
System_Admin select a inasis first

![OnlyAcceptOneCafeAdmin2](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/0a214047-124e-4e8a-a276-8814831b161d)


Bot will display a list of applicant record who apply for the Cafe_Admin position

![OnlyAcceptOneCafeAdmin3](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/1f700d9d-30af-4be1-8621-f82ced171bff)


System_Admin have to reply a email that want to approve for Cafe_Admin position

![OnlyAcceptOneCafeAdmin4](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/dbe311a8-c3f2-4b92-b4be-9362868004a8)


Bot showing that a Cafe_Admin is approved for a particular Inasis, and the application below is rejected

![OnlyAcceptOneCafeAdmin5](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/7b9941a6-ebaa-44f8-a0ac-8fd62c1041ea)


Database table evidence: showing lew@gmail.com not exist

![Evidence-onlyOneInasisOneCafeAdmin](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/065cedf0-7da6-4b57-ba47-748e4b469ccc)


System_Admin reply "2" to view all information provied by the CafeAdmin. Then reply "1" to view cafe_admin information

![systemAdmin_viewInfo](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/57ce95a9-ed35-49d0-83ba-da5e071a4d01)

![systemAdmin_viewInfo2](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/cfc9a16c-42fa-4ec8-ac03-f290120109d8)


System_Admin reply "2" to view all information provied by the CafeAdmin. Then reply "2" to view food details providded by the cafe_admin

![systemAdmin_viewFoodDetails](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/02cd9dc4-2b13-43ac-a856-989ab1a55a1e)

![systemAdmin_viewFoodDetails2](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/0bc1be11-3b69-4b8b-92e0-6ec19408d6c7)


System_Admin reply "2" to view all information provied by the CafeAdmin. Then reply "3" to view food command providded by the cafe_admin

![systemAdmin_viewComments](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/ea6413f3-9044-453e-9e9b-dabad5fe64a0)


For Cafe_Admin: 

Select Cafe_Admin

![CafeAdminRegistration1](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/b1569dca-c4f9-4ec9-9829-3cdbe95e64b5)


The applicant that have got the approval from the System_Admin successfully have to reply 1 

![CafeAdminRegistration2](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/ab7d181e-fdbf-4ce3-85b7-6240bb2ea416)


Bot reply to the success applicant that they have to register an account (1)

![CafeAdminRegistration3](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/2cca607e-b399-4545-8aac-5a9545af6e7c)


Bot reply to the success applicant that they have to register an account (2)

![CafeAdminRegistration4](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/7fb5fef1-e959-451f-8e3d-ab46e96eb533)


Bot prompt the success applicant who have got the approval to register an account

![CafeAdminRegistration5](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/b1395b58-9806-462b-b5a8-f069018643fb)


The applicant have to follow the instruction sent by the bot to fill up the registraton data

![CafeAdminRegistration6](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/02d63da6-585d-4b3b-95b2-b13117faaf49)


The bot will send back a message to the applicant if their registration is successful. Once the user have register the Cafe_Admin account successfully, then they can add food details.

![CafeAdminRegistration7](https://github.com/STIW3054-A222/groupproject-tastebot/assets/102460032/2cefae42-9990-48eb-900e-caadf7e98047)


System_Admin reply "3" to delete the cafe_Admin registration. Once the cafe_admin have been deleted successfully, it will display a successful message to the system_admin. 

![systemAdmin_deleteRegistration](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/796cb1e0-60a9-4384-8e7f-ee807eef9972)


Output: Cafe_Admin Add, Update, Delete the food details

First, User choose "Cafe_Admin" and then reply "f" in order to manage the food details. 

![WhatsApp Image 2023-07-11 at 00 33 30](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/9e199ce3-2cd5-4a9e-9b70-db6c31937a7a)

Cafe_Admin add food. 

![WhatsApp Image 2023-07-11 at 00 33 32](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/c6f8addd-d63c-4c04-9661-47d4431bb4a7)

Cafe_Admin provide email_address to update food. 

![WhatsApp Image 2023-07-11 at 00 33 33](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/5709d08f-fe1b-4bfc-bc1a-1bb1cd3b8ba1)

Cafe_Admin update the price by providing the food name. 

![WhatsApp Image 2023-07-11 at 00 33 34](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/1d629013-bff4-409e-9e94-735d2c98b857)

Cafe_Admin delete food by food name. 

![WhatsApp Image 2023-07-11 at 00 33 36](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/9227a90e-32d6-4d7a-b6a0-4a5d34979785)

The bot will send a message to indicate the food have been delected successfully. 

![WhatsApp Image 2023-07-11 at 00 33 34](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/de35810b-a501-4739-bd14-a3e91c63e721)

Cafe_Admin update food status by providing the food name. 

![WhatsApp Image 2023-07-11 at 00 35 03](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/3280c897-b83f-4df0-b22f-c386e281c699)

Cafe_Admin reply "c" to view the food comments.

![WhatsApp Image 2023-07-11 at 00 38 18](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/cf6c2d9c-ebe6-4409-b13b-a0b99e2cdeb4)

Cafe_Admin reply "r" to view the rating of the food. 

![WhatsApp Image 2023-07-11 at 00 38 19](https://github.com/STIW3054-A222/groupproject-tastebot/assets/80876660/3ecdd7a7-62be-4124-9628-c75333ddedc9)

User select user. 

![Screenshot (67)](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103965506/f65ce0e9-9d28-471b-b7b9-7de9ab6aabc3)

User reply "2" to view the list of available food at each cafeteria. Then reply number correspond to the cafe in the list. 

![Screenshot (68)](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103965506/f98d82c0-0c47-4ab6-b07b-16792428b3b4)

User reply "3" to view the location link.

![Screenshot (69)](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103965506/81dab77f-0881-4135-b76c-10ebeb6e0a31)

User reply "4" to leave a comment, giving rating and view best food. 

![RT1](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103985766/cf556327-6b12-4afc-b3fe-1bb48f0e76d4)

The bot provide the inlined keyboard for the user to choose. 

![RT2](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103985766/de2573bf-568b-43f8-9728-497f5479a455)

User input the food_comment and the food_id. The bot display successfully message. 

![RT3](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103985766/7282dc4e-84d2-4f31-a489-eb4b16519121)

User input food_rating and food_id.

![RT4](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103985766/b0635824-fb9e-48bd-b56c-f6849af3edd1)

User reply "1" to view the best food suggestions. 

![RT5](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103985766/1eb4f0fd-dd13-4011-baf4-00e91155004d)

The bot will send a list of the best food suggestion. 

![RT6](https://github.com/STIW3054-A222/groupproject-tastebot/assets/103985766/6e8a3019-4000-4295-98e6-74b1eb8028eb)

Cafe_Admin send the promotion status

![cafeAdmin_sendPromotionStatusCode](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/431b65d8-f184-4c87-b742-9a7f296fc17d)

![cafeAdmin_sendPromotionStatus](https://github.com/STIW3054-A222/groupproject-tastebot/assets/77046925/75e70be4-8111-47a8-a75d-4f53536aed70)



## References (Not less than 20)
1. Abd Samad, N. A., Embong, Z., & Nor, M. (2022, June). Development of Telegram Bot in Supporting the Learning Process of Object-Oriented Programming.
2. Ahmadi, A., Setiawan, D., Suprayitno, S., & Hartoko, P. (2020). Design of Academic Information System Based on Bot Telegram in Smart Campus Concept. Journal Asro, 11(03), 88. https://doi.org/10.37875/asro.v11i03.310
3. Ahmadin, A., Palenewen , E., & Akhmad, A. (2021). The Telegram Bott Based Learning Model. Indonesian Journal of Education Review (IJER), 8(2), 6-11. https://journal.unj.ac.id/unj/index.php/ijer/article/view/26993
4. Alharethi, T. M. (2023). Autoresponder using Chatbot for Educational Services. 2023 1st International Conference on Advanced Innovations in Smart Cities (ICAISC), 1–5. https://doi.org/10.1109/ICAISC56366.2023.10084956
5. Apriela Trirahma. (2021). Telegram Bot as a Data Collection Tool for Progress Reports in Area Mapping Progress Monitoring System. Jurnal RESTI (Rekayasa Sistem Dan Teknologi Informasi), 5(6), 1182–1192. https://doi.org/10.29207/resti.v5i6.3654
6. Bots: An Introduction for Developers. (n.d.). https://core.telegram.org/bots
7. Dziadkiewicz, A., Nieżurawska, J., & Karaszewska, H. (2016). Attractiveness of Cafeteria Systems as Viewed by Generation Z. World Academy of Science Engineering and Technology WASET.
8. Graf, B., Krüger, M., Müller, F., Ruhland, A., & Zech, A. (2015). Nombot. Proceedings of the 14th International Conference on Mobile and Ubiquitous Multimedia, 360–363. https://doi.org/10.1145/2836041.2841208
9. Ilic, A., Licina, A., & Savic, D. (2020). Chatbot development using Java tools and libraries. 1–4. https://doi.org/10.1109/IT48810.2020.9070294
10. Modrzyk, N. (2019). Building Telegram Bots. Apress. https://doi.org/10.1007/978-1-4842-4197-4
11. Mondal, A., Dey, M., Das, D., Nagpal, S., & Garda, K. (2018). Chatbot: An automated conversation system for the educational domain. 2018 International Joint Symposium on Artificial Intelligence and Natural Language Processing (iSAI-NLP), 1–5. https://doi.org/10.1109/iSAI-NLP.2018.8692927
12. Morze, N., Buinytska, O., & Varchenko-Trotsenko, L. (2017). Use of Bot-Technologies for Educational Communication at the University.
13. Rianto, R., Rahmatulloh, A., & Firmansah, T. A. (2019). Telegram Bot Implementation in Academic Information Services with The Forward Chaining Method. Sinkron, 3(2), 73–78. https://doi.org/10.33395/sinkron.v3i2.10023
14. Rizki, P., & Arista, P. (2020). Realtime Student Information Center Application Based on Telegram Bot Case Study at the Faculty of Computer Science, UPN “Veteran” East Java. Nusantara Science and Technology Proceedings, 135–143. https://doi.org/10.11594/nstp.2019.0419
15. Rubenlagus. (n.d.). Telegram Bot Java Library. GitHub. https://github.com/rubenlagus/TelegramBots
16. Sebastian, D., & Nugraha, K. A. (2021). Academic Customer Service Chatbot Development using TelegramBot API. 2021 2nd International Conference on Innovative and Creative Information Technology (ICITech), 221–225. https://doi.org/10.1109/ICITech50181.2021.9590140
17.  Setiaji, H., & Paputungan, I. V. (2018). Design of Telegram Bots for Campus Information Sharing. IOP Conference Series: Materials Science and Engineering, 325, 012005. https://doi.org/10.1088/1757-899X/325/1/012005
18.  Sugiartha, I. K., & Swari, D. A. A. I. (n.d.). Android Based Restaurant Finder Application Using Location Based Service in Bali.
19.  Telegram Bot API. (n.d.). https://core.telegram.org/bots/ap
20.  Vijjali, R., Mishra, A., Nagamalla, S., & Sathyanarayna, J. (2020). Semantic Embeddings for Food Search Using Siamese Networks. Proceedings of the 4th International Conference on Natural Language Processing and Information Retrieval, 138–143. https://doi.org/10.1145/3443279.3443303


## Youtube Presentation (10%)
https://youtu.be/jld1qbXOpMo
