# This is a modification of project https://github.com/Ahmed-Waleed-01/Fawry_like_System (to make API that serve same Functionalties.)

This is a Maven project made with JAVA 17 (Jar packaging) spring boot 3.0.1
the server runs on localhost:8080 by default in the project

----------------------------------------------------------------
-To open the project and run it using :

-> Intellij ultimate :
you can just open the folder which contains the project then run Phase2Application.java

->Eclipse :
you need to have java ee installed on eclipse.
then from file menu choose import 
choose existing maven project and browse the project folder
then select pom.xml 
if you see message (Add a version or custom suffix using "Name template" in "Advanced" settings)
then press on advanced in the bottom side 
and press on name template drop down menu and choose [groupId].[artifactId]-[version]
and make sure you have closed previous projects.
then run Phase2Application.java.

 --------------------------------------------------------------
 Testing :-
 
 you need postman application to test the api properly.
open postman and press on import button in team workspace and choose the (json file) included in the uploaded folder.
it contains all test cases for the system apis.

 --------------------------------------------------------------
 Clarification for paramaters :-
 
 any api can be accecced thru : localhost:8080/"servicelink + query paramaters".
 
 when an admin or user signs up they will get an id 
 where first admin would get id=1 then second admin would get id=2, and so on
 same with any user.
 
 in most apis it either requires admin id or user id and the id resembelse the user which we choose to make the api specific action
 so you need to first make a user or an admin before you can use some of the api functionalties.
 
 
 -in (admin_service_discount) service parameter can be : (Mobile,Internet,Landline,Donations)

 -in (Accept refund) order_placement means the positioning of order in show refund requests.

 -in (Mobile_service) provider value can be:(Etisalat,Vodafone,WE,Orange) , number parameter refers to phone number payment method can be:(wallet,cash,credit).
					  
 -in (Donation_service) provider can be: (Schools,NGO,Cancer).

 -in (Landline_service) Payment type can be: (quarter,monthly).

 -in (Request refund)	order id means the id of the order that you want to make a refund request on.
 
