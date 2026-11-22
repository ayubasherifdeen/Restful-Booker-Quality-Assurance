# **REQUIREMENTS REVIEW LOG**

1. As a user, i want to navigate the website so i can see all the services the website/hotel has to offer

    **Acceptance criteria**

i. Given that i have accessed the website, when i click on the "Rooms" tab, i should be redirected to the rooms section of the website
ii. Given that i have accessed the website, when i click on the "Booking" tab,i should be redirected to the section for checking the availability for rooms
iii. Given that i have accessed the website, when i click on the "Amenities" tab, i should be redirected to the section of the website about amenties
iv. Given that i have accessed the website, when i click on the "Location" tab, i should be redirected to the section that details the location of the hotel
v. Given that i have accessed the website, when i click on the "Contact" tab, i should be redirected to the section that allows me to contact and message the hotel
vi. Given that i have accessed the website, when i click on the "Admin" tab, i should redirected to the admin log in page

2. As a user, i want to check to availability so i can confirm which rooms are available for the days i would like to book rooms

    **Acceptance criteria**

    i. Given that i have navigated to the Bookings section, when i select days and click on  "search availability", then rooms available for selected days should be displayed

    **Open questions**
i. Should the system show an error when start date selected > end date? What error?


3. As a user, i want to send message to hotel management so that i can ask a question or lodge a complaint without needing to phone them.

    **Acceptance Criteria**
    i. Given that i have filled all fields with valid inputs, when i click on "Send" then a confirmation message should appear
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

6. As an admin, i want to receive messages sent by visitors and guests so i can view messages sent by them.
    **Acceptance Criteria**
    i. Given i have logged into the admin site, when i click on the messaes tab, i should be redirected to the messages page
    ii.Given i am on the messages page, when i click on a message, i should be redirected to the page containing the full details of the message

    **Open questions**
    i. Should the admin be able to view the entire message and not just the sender and subject?

7. As an admin, i want to be able to be able to create rooms so i can add more rooms/services to what we already provide
    **Acceptance Criteria**
    i. Given that i have logged into the admin site, when i click on the Rooms tab, i should be redirected to the rooms page.
    ii. Given that i am on the rooms page, when i fill the room fields and click create, then a new room is added

    **Open questions**
    i. What input fields exactly should be field?
    ii. Should all be mandatory? which ones should be mandatory?
    iii. What error handlind and validations should be made and considered?

8. As an admin, i want to be able to modify already existing rooms so i can make to the information of the rooms on the website as required
    **Acceptance Criteria**
    i. Given i am on the rooms page, when i click on an any room, i should be redirected to a page that details the room.
    ii. Given i am on the room details page, i should see the room number, amenities available, price, bookings and reservations details.

9. As an admin, i want to be able to recieve information of booked dates so i can see and monitor days with booked rooms and the people booking them
    **Acceptance Criteria**
    i. Given that i am on the admin site, when i click on the Reports tab, i should be redirected to a calender like page with dates booked indicated
    ii. Given that i am on the reports page of the admin site, the date should contain both the name of the guest as well as as room booked/reserved for said dates

    **Open questions**
    i. Should the admin be able to see more details about the reservation rather than just the name, date and room number?

