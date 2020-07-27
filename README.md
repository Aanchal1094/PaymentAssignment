# PaymentAssignment

Hi, this demo appliction is based upon python( HTML,CSS, Javascript).
In order to run the above code, we need to have visual studio code or any other ide which is suitable to run django application.
Download the code into the local machine and un-zip the folder.
Then open the folder in the visual studio code.
After that open a terminal and browse to the current directory where the project is present.
Now run python manage.py runserver command and open the mentioned development server at http://127.0.0.1:8000/ in the browser.
The test cases are written in test.py for the reference 
Functionality - user can a valid card number followed by CVV, expiry date and zip code.
A user is registered into the stripe admin page which can only be accessed by the admin. But the card details are encyrpted so that user data is preserved.
Application is developed using Stripe payment gateway.
