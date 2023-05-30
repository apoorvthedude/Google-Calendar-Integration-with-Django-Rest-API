Steps to Execute the project

<b> Step 1 </b>

Install requirements from requirements.txt

    pip install -r requirements.txt
  
<b> Step 2 </b>

Clone the repository:

https://github.com/apoorvthedude/Google-Calendar-Integration-with-Django-Rest-API.git

<b> Step 3 </b>

If you have your own google calender api credentials , replace the <b> client_secret.json </b> file with your credentials file

<b>Note : </b> You need to rename your credetials.json file as client_secret.json

If you don't have any credentials , you can test with my credentials or login to https://console.developers.google.com there you can create your own credentials.

<b> Step 4 </b>

After replacing the credentials file in project folder , Now we need to run the following commands in command prompt.
    
    cd GcalendarAPI
    
    python manage.py makemigrations
    
    python manage.py migrate
    
    python manage.py runserver
    
 
<b> Step 5 </b>

Now open in your Browser and enter the following url in searchbar.

    http://localhost:8000/rest/v1/calendar/init/
    
   
It redirects to your gmail and asks permission , after permission allowance it will automatically redirects to another page and shows your calender events .

# Thank You
