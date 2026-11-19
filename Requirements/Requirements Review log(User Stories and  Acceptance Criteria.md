# **REQUIREMENTS REVIEW LOG**

1. As a user, i want to navigate the website so i can see all the services the website/hotel has to offer

###### &#x09;**Acceptance criteria**

**i.** Given that i have accessed the website, when i click on the "Rooms" tab, i should be redirected to the rooms section of the website

ii. Given that i have accessed the website, when i click on the "Booking" tab,i should be redirected to the section for checking the availability for rooms

iii. Given that i have accessed the website, when i click on the "Amenities" tab, i should be redirected to the section of the website about amenties

iv. Given that i have accessed the website, when i click on the "Location" tab, i should be redirected to the page that details the location of the hotel

v. Given that i have accessed the website, when i click on the "Contact" tab, i should be redirected to the page that allows me to contact and message the hotel

vi. Given that i have accessed the website, when i click on the "Admin" tab, i should redirected to the admin log in page



2. As a user, i want to check to availability so i can confirm which rooms are available for the days i would like to book rooms

&#x09;

###### &#x09;**Acceptance criteria**

**i.** Given that i have navigated to the Bookings section, when i select days and click on  "search availability", then rooms available for selected days should be displayed

ii. Given that i have selected a start date > an end date, when i click on "search availability", a "start date cannot be greater than end date" validation error should be appear

iii. Given that i have navigated to the Bookings section, 


**Open questions**




3. As a user, i want to send message to hotel management so that i can ask a question or lodge a complaint without needing to phone them.

    **Acceptance Criteria**
    i. Given that i have filled all fields with valid inputs, when i click on "Send" then a confirmation page should appear
    ii. Given that i have left all input fields empty, when i click on "Send" then an error message should apear naming empty fields
    iii. Given i have sent a message, then it appears on admin site


    **Open questions**
    i. What message should appear on the confirmation page
    ii. Should a confirmation message also be sent through other channels(eg.sms, email)
    iii. What input fields exactly will be available for user to fill
    iv. Are all fields mandatory?


4.  As a user, i want to be able to book a hotel so that i can make reservation for my staying

    **Acceptance Criteria**
    i. Given that i have selected valid availability dates, when i click on "Book now" i should be redirected to confirmation page.
    ii. Given that i have been redirected to a confirmation page, when i click on "Confirm" a success message should appear to confirm success

    **Open questions**
    i. What information should the confirmation page contain
    ii. What is the definition of success
    iii. Should the success message be sent through other channels(sms, email)
    iv. What happens when the number of people confirming room reservation > the rooms available? eg, what happens when three people confirm booking for two rooms at the same time?

5. As an admin,i want to be able to log into the admin site so i can monitor and modify hotel activities
    **Acceptance Criteria**
    i. Given i am on the website, when i click on admin tab on the navigation bar, it should redirect me to the admin log in page
    ii. Given i am on the admin log in page, when fill i with valid log in credentials and click on "login", it should redirect me  to the the admin page
    iii. Given i am on the admin login page, when i fill the input fields with invalid login credentials and click on "login", i should get an "invalid credentials" error message

    **Open questions**
    i. What input field should be used for the login page
    ii. How should the login page handle empty input fields
    iii. 

6. As an admin, i want to receive messages sent by visitors and guests so i can view messages sent by them.
    **Acceptance Criteria**
    i. Given i have logged into the admin site, when i click on the messaes tab, i should be redirected to the messages page
    ii.