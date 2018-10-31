NLU Rasa - Building a Chatbot - ReadME
Problem Statement
-----------------------------------------------------------------------------------------------
An Indian startup named 'Foodie' wants to build a conversational bot (chatbot) which can help users discover restaurants across several Indian cities. You have been hired as the lead data scientist for creating this product.
The Bot accesses Zomatopy API to provide result for the favourite restaurant.
---------------------------------------------------------------------------------------------
Version Details:-
rasa-core                        0.10.1
rasa-core-sdk                 0.11.5
rasa-nlu                           0.12.3
slackclient                        1.2.1
---------------------------------------------------------------------------------------------
Sample Conversation:-
---------------------------------------------------------------------------------------------
Hi
hey there! I am Foodie, How may i help you
can you please help me search for some restaurant in Kolkata
What kind of cuisine would you prefer?
 1. Chinese
 2. Italian
 3. South Indian
 4. North Indian
 5. Mexican
 6. American
Chinese
What price range are you looking at?
1. < 300
2. 300 - 700
3. > 700
< 300
Showing you top rated restaurants:

Following are the search results:-
Chittoda's Suruchee Restaurant in 2, Dacres Lane, Near Pearless Bhawan, Esplanade, Kolkata has been rated 4.6
Solid Gulp (Bapi Dar Momo) in Karunamoyee Bus Stop, Sector 2, Salt Lake has been rated 4.6
Beans n Bites in 23/20/3 Gariahat Road, Near Kotak Mahindra Bank, Golpark, Kolkata has been rated 4.5
Shim Shim in 31A Bright Street, Park Circus Area, Kolkata has been rated 4.5
WTF! - Where's The Food in E-75, Sukant Nagar, Sector 4, Salt Lake, Kolkata has been rated 4.5

Should I send you details of all the restaurants on email?
sure, please send to xxxx.xxxx12@gmail.com
Sent to xxxx.xxxx12@gmail.com , Bon Appetit!
goodbye :(
---------------------------------------------------------------------------------------------
