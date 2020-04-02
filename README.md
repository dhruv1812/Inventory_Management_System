Inventory_Management_System – Readme File


Overview 
A simple inventory management system made in Django framework of Python
Follow the steps below to run it on your system - 

 
Step 1 - Install python libraries – django and django-import-export

 - Open command line (start menu, search cmd) and run these two commands

pip install django

press enter and let django install

pip install django-import-export

press enter and let django-import-export install

Step 2 – Download the application folder and run it

-	Copy the attached folder and save it on desktop or a place of your choice and unzip it (if it is zipped).

-	Open the (unzipped) folder, click on the address bar and type CMD and press enter. This will open command prompt from this location. 

-	In the command prompt window, type the below command and press enter -

python manage.py runserver

press enter to run the above command on command prompt

-	The output from the above command on command prompt should look like the yellow colour part below -

Watching for file changes with StatReloader

Performing system checks...

System check identified no issues (0 silenced).

April 01, 2020 - 12:52:46

Django version 3.0.4, using settings 'stock_management.settings'

Starting development server at http://127.0.0.1:8000/

Quit the server with CONTROL-C.

-	Copy this part from the generated output - http://127.0.0.1:8000/

-	Paste it on the address bar of a web browser window and run it

-	This will open the application on the web browser and you will be able to make additions, edits and changes to the application through the products, customers and orders buttons.


How to Use the Application (Functionalities) – 

Step 1- Click on products, customers and orders buttons to see the details of existing data.

Step 2 - Click on the + sign next to each of the three buttons to enter a new data row (a new product, customer or order)

Step 3 - Use the edit or X symbol in front of each row across the products, customers or orders column to edit or delete the entries.

Extra Information – The application also lets you to upload data through an excel file. This can be done by creating admin rights and logging in as admin through the following link – 

-	http://127.0.0.1:8000/admin

Create a super user for admin access 

While uploading data from excel, make sure each table (customers, products and orders) is on a separate tab and the exact same column names are used as in the application.


