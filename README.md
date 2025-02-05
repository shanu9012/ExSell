# ExSell

DOCUMENTATION For ExSell ( Project 2 ) **Online Marketplace for College Students.**

> Developed By
>
> ***Adarsh Kumar Jain*** ( SID 65 )
>
> ***Ravi Kiran Attili*** ( SID 885 )
>
> (Under guidance of **SophomoreS.in**)

<br/>

## About
- ExSell is a website that serves as an online marketplace for college students.
- Students can go to the website to sell their used items or browse items put on sale by other students of the same or from different colleges.
- This website purely uses core PHP, HTML, CSS, JAVASCRIPT, My SQL, and SQL. 
- Any third party CSS or PHP framework/library say BOOTSTRAP, Codeigniter, CS50 library or the likes are not used for the devlopment of website.

<br/>

## Setting username and password for mysql server
In **line 13** of ***config.php*** and in **line 69** of ***helpers.php***, you have to change the username depending upon the login id. Password need not to be changes as it is same for both.
- If you are on CS50 IDE using email-id of SID 67 (username : adarsh_jain) than
 ```
    //connecting to database
    $link = mysqli_connect('localhost', 'adarsh_jain', 'v1kCjsvLYytrBTGV', 'store');
 ```
 - If you are on CS50 IDE using email-id of SID 885 (username : avravikiran) than
 ```
    //connecting to database
    $link = mysqli_connect('localhost', 'avravikiran', 'v1kCjsvLYytrBTGV', 'store');
 ```
 
 So change the username depending upon the user_id.

<br/>

## Starting the server
- To start the server type the following command
  - If you are logged in with email-id of **SID 67** (username : adarsh_jain) than use the following commands-
  ```
      apache50 start ~/workspace/Online\ Store/public/
      mysql50 start
  ```
  - If you are logged in with email-id of **SID 885** (username : avravikiran) than use the following commands-
  ```
      apache50 start ~/sopho-project2/public
      mysql50 start
  ```
  
- Than click on the ***webserver*** option in drop-down list of **CS50 IDE** on top-left menu.

<br/>

## Navigating the website

### Login page
This is the login page for the website. You have to use your registered email-id and password for login.

![Login](/images/login.PNG?raw=true "Login Page")

### Register Page
If you are new on the website, than first register on the website. Otherwise you can only visit the store, but can not see the seller details or simply can not buy any item put for sell.

![Register](/images/registration.PNG?raw=true "Register Page")

### Dashboard
Dashboard is the place where you will see all the items that you have put on the sell. You can also remove items from the sell. You can filter the results using their category.

![Dashboard](/images/dashboard.PNG?raw=true "Dashboard")

### Selling item form
To put a item on sell, you have to fill this selling form. You can also upload image of your product.

![Selling item form](/images/sell.PNG?raw=true "Selling item form")

### Changing Password
Here you can change your password.

![Change Password](/images/pwchange.PNG?raw=true "Change Password")

### Chaning Account Information
If you want to change your account information, you can change.

![Chaning Account Information](/images/account.PNG?raw=true "Chaning Account Information")
