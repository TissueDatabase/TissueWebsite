

# Tissue Website

Setup instructions to get started with Tissue Website associated with Tissue Database. These instructions will help you set up and locally run a website that will display the data stored in your local database. 


**NOTE:** Ensure that you have completed the *databasePopulate* setup before attempting.

  

## Step 1: Clone from GitHub

    1. Open the command palette (Ctrl+Shift+X) in Visual Studio Code.

    2. Filter by typing "clone" then select "Clone from GitHub" and press Enter.

    3. Paste code link from tissueDashboard GitHub page.

    4. Save to your machine.

## Step 2: Command Line

Open your command line tool and run the following prompts in order.


**Install Django**
```bash
  pip install Django 
```

**Create Login**
```bash
  python3 manage.py createsuperuser
```
After running the above command, you will be prompted to enter a username, email, and password. **NOTE:** Save your email and password for later use. 


## Step 3: Run on Local Server

Open your command line tool and paste in the following prompt in order to run the application. 

```bash
  python3 manage.py runserver
```
The output to the command line will inlcude a link to view your application in the browser. It will look similar to the line below. Open the link to view the application. 

```
Starting development server at http://000.0.0.0:0000/
```

## Step 4: Accessing Admin page

After opening the server link from the previous step, update the url by adding **/admin/** at the end. You will be directed to a login page where you can enter the email and password that was set in step 2 when creating a user account. Now this will open your admin dashboard for the website. 