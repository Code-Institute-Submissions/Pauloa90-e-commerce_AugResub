

# E-Go
Full Stack Framework with Django Milestone Project


This is an Ecommerce website built with Python, Django as a python’s framework from Code Institute.
E-go is a fictitious e-commerce website that provides holidays packages for users who want to buy this service to go on holidays. 
The website will provide the price and more details for different places to go, cultural aspects and curiosities about different coutries as well.

![Screeshot](https://ecommercego.s3-eu-west-1.amazonaws.com/homepage01.PNG)

This project has incorporated code pulled from other projects given by Code Institute:

1. django-e-commerce project
2. django-auth

The course of Code Institute guided me durnig this project.

This site is for any user interested in going on holidays, looking for a single site where you can find a package with hotels, experiences, curiosities about different
countries in just one web page.

E-commerce is only online at the moment, depending on customers' wishes, a special web application can be designed to have in a store.
A super user was created to add the products (packages) and the user can also register to send the payment.

As a new user of the webpage, I'd like to be able to:
- Find out what I can get to know on this website.
On the landing page the user can already see the e-commerce with all the products (packages) he is able to buy.

![screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/user01.PNG)

- Get to know more about travelling from different people. 
The user is able to check the session "Discover" and hear from different people their stories. On this session the user get the links of many blogs regarding travelling.
![screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/user02.PNG)

- If the user still doesnt know about where to go, they can check curiosities about places that the website is selling the packge to, such as Brazil, New Zealand and Thailand.
On the session "curiosities" the user will get to know some fun and interesting things about some places thar the website is selling the package to.
![screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/user03.PNG)

- The user is able to register themself in order to purchase some thing from the webpage.
The user will have to fill a form in order to do it.
![screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/user04.PNG)

- The user is able to choose packages of holidays and get to see it before finishing the order.
When the products are in the cart, the user can amend the order, deleting or adding a new product.
![screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/user05.PNG)

### Strategy 
E-go is a simple web ecommerce to make peoples lives eaiser regarding travelling. On the webpage they can get to know more about travelling through the blogs and also curiosities from diffenrent places.
The owner can negotiate with travel agencies and have more products on the webpage which can be really profitable for both.

### Scope
I wanted from the begging have a webpage easy to access from the user's side, and fun to get to know different blogs. On the navbar there are only 3 options being "Home" where the ecommerce is hoted,
"Curiosities" thar provides interesting stories and facts about places being sold on the ecommerce and "Discover" where users can access many Blogs that post things about trips, travelling and etc.

### Structure
The user who arrives at the main page can see a navigation bar at the top with the session they have access to on the left side and on the right side a Login area.
After the user is re-certified on the website, he can buy any product. To register, the user must provide a username, password and email for the Login. If the user forgets the password, they can access "Reset password" and receive
an email to have a new password. In both cases, a feedback message will be displayed.

The user can simply add the quantity of the packaging to the cart, by clicking on the blank field of the cart with the product he wants, and adding a number (people) to it and then clicking on "add".
The user is redirected to the main page again, giving the opportunity to add another product (package). If this is not the case, the user can access the "cart" at the top right of the navigation bar and be redirected to the checkout session.

OAfter the order is in accordance with what the user has chosen, click on "checkout" and add the necessary payment details, the order will be processed by bands. If there is something to change, the user can change the quantity in the respective field and click on "change".
If the user wants to delete the item, just type "0" in the field and "change" right after, and the product will be deleted.

In both scenarios, payment processed successfully or not, a feedback message will be displayed to the user. If the payment is processed, the user will be redirected to the main page again.

In the Discover section, the user can click on the Blogs most interesting to you and another tab will open in the browser to ensure that the user does not lose control and stay away from the web page.

In the "Curiosities" section, Jumbotrons with images and text with curiosities about different countries.

### Wireframes
Here are the 3 wireframes for each section of my project:
#### Home
![screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/wireframes01.jpeg)
#### Discover
![screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/wireframes02.jpeg)
#### Curiosities
![screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/wireframes03.jpeg)

## Live Demo
Please check the link to see the deployed version of the app: [link](https://ecommercego.herokuapp.com/)

Please check the link for Screeshots:
1. [Screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/screeshot01.PNG)
2. [Screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/screeshot02.PNG)
3. [Screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/screeshot03.PNG)
4. [Screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/screeshot04.PNG)
5. [Screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/screeshot05.PNG)
6. [Screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/screeshot06.PNG)
7. [Screenshot](https://ecommercego.s3-eu-west-1.amazonaws.com/media/screeshot07.PNG)
 


## User Experience(UX)

### User Stories
* **First Time Visitor Goals**
- As a First Time Visitor, I want to understand the concept of the website and its purpose.
- As a First Time Visitor, I want to able to navigate through the website to find the content that I'm looking for,
- As a First Time Visitor, I want to look at the blogs related to travelling and also about cultures from different places.
- As a First Time Visitor, I want to find if the webpage sells what I'm looking for.

* **Returning Visitor Goals**
- As a Returning Visitor, I want to know if there any update on the packages and prices.
- As a Returning Visitor, I want to get in contact with the company E-go.
- As a Returning Visitor, I wan to open the social media links to get to know more about the company.

* **Frequent Visitor Goals**
- As a Frequent User, I want to know there are is deal on the packages sold on the website.
- As a Frequent User, I want to be able to subscribe on the Newsletter.
- As a Frequent User, I want to search if the is a specif detination that I want to. 


## Design

**Colour Scheme**
Blue and white were used as the main two color for this application. Blue is gender neutral, so we can attract either men and women. 
It does also bring the idea of sky, travelling etc.
White is common used as a neutral color, it makes clear for the user and do not over load the webpage with dar colors.

**Typography**
Anton and Roboto were used as the main fonts for this project. They are commonly  used in a project designed to be neat and tidy.
It does also bring identity to this application.

**Imagery**
Imagery it is also very important. For that reason, the images standing for the products sold on the web page, were carefully selected to 
bring a bit of what the user can expect to be, if they buy that product.

## Technology used

1. HTML5 - The project used HTML to define the layout of the page.
2. CSS3 - The project is styled using css.
3. Python - The back-end fucntions are code based in Python.
4. JavaScripT/JQuery - To implement Stripe for payment, I used Javascript and Jquery.
5. Django - It is framework using python.
6. Bootstrap - This library was used to make the design responsive
7. GitHub/GitPod - I'm using this open source repository for my code.
8. Font Awesome - I got the icons from Font Awesome website.
9. Stripe - Stripe made the eccomerce fucntional in terms of payments, receiving payments by card.
10. Heroku - This ecommerce is hoted on Heroku.
11. Travis-CI - Is used to build and test project hoted at GitHub.
12. AWS S3 - Storages all the media and static files of this project.


# Testing
HTML and CSS validators (W3C) were used to ensure identation and error wont accur.

### Testing User Stories from User Experience section

* **First Time Visitor Goals**
- As a First Time Visitor, I want to understand the concept of the website and its purpose.
    a. Upon entering the webpage, users are greeted with simple and neat Navbar with the 3 mais sections.
    b. There is a search bar, with the text "Find your destination!
        You will find the best holiday package all inclusive that suits you best!".
        That is a call and also it stands for the website purpose, making the subject approarched on the app very clean.
    c. Just right under the search bar, all the packages sold on the the website are being displayed.
    d. The user will know right after entering on the web page the purpose of the website.

- As a First Time Visitor, I want to able to navigate through the website to find the content that I'm looking for,
    a.  The search bar is a blue and white Jumbotron with a call out. The user is able to simple type what the destination they are looking for.
        of this webpage provides it, it will be displayed.
    b. If the user is looking for blogs, and they are interested in subject about travelling, there is a section called "Discorver".
    c. The user will be able to also get to know a bit more about the countries and cities that this webpage is selling the packages for. 
        The section is "Curiosities" where there is a little more information and curiosities about those contries.
    d. Those sections are pretty well displayed and separeted, making clean and organized for the users.

- As a First Time Visitor, I want to look at the blogs related to travelling and also about cultures from different places.
    a. As mentioned before, those sections are on the Navbar of the webpage.
    b. The user can navigate on those sections by clicking on the desired section on the Navbar.
    c. For whatever the user decided to go to, there will be another tab opened. This is for the user no tlose track on the web page.

- As a First Time Visitor, I want to find if the webpage sells what I'm looking for.
    a. The main page contains all the services/destinations that this company provides.
    b. In case of many services/destinations, there is also a Search bar where the user can easily find the place that they want to go to.
    c. If the destination in not found, the user can go back on the page and reloaded it with the packages that E-go provides.

* **Returning Visitor Goals**
- As a Returning Visitor, I want to know if there any updates on the packages and prices.
    a. Any updates made on the webpage will be displayed first.
    b.  If a returning visitor is checking on E-go again, any updates on services will be shown first.
    c. The offers will be displayed as the negotiation  goes with the other companies.
    d. There is also a Newsletter (to be Implemented for Frequent users).

- As a Returning Visitor, I want to get in contact with the company E-go.
    a. Contact us is a feature to be implemented. In this section the user will be able to fill up a form.
    b. On this form the user can let the company the subject and reason for the contact and describe it in a text box.
    c. The "contact" link is on the footer of all the pages. The user will be clearly able to reach out the management of the company.

- As a Returning Visitor, I want to open the social media links to get to know more about the company.
    a. Social media links were put on the footer of the application.
    b. Those links will be displayed  in any page open on the webpage.
    c. E-go is fictitious company, being the reason why there is E-go social media profiles.
    d. The links will bring the users to the main page of respectively : Twitter, Facebook, Instagram and Youtube.
    e. All the links will be open in another tab not letting the user lose track on the webpage.

* **Frequent Visitor Goals**
- As a Frequent User, I want to know if there are deals on the packages sold on the website.
    a. If the price is changed as a deal, a bold font text will appear on the package affected.
    b. Deals and promotions can be sent to the users if they subscribe on the Newsletter.
 
- As a Frequent User, I want to be able to subscribe to the Newsletter.
    a. This feature is to be implemented. The user will have to fill the field on the bottom right Newsletter with the email.
    b. Users will receive any updates on the webpage including the sections "Discover" if there is any new blog posted or "Culture".
    c. The user will be able to cancel the Newsletter by requestins it by email.
 
- As a Frequent User, I want to search if this is a specific destination that I want to go to. 
    a. Using the search bar the user can search for any destination they wish.
    b. If the destination is not found, that means that the company does not provide this service.
    c. By reloading the page on going back, all the services will be displayed normally again.

### Futher Testing
- The following browser were used to test this web page: Google Chrome and Internet Explorer.
- The website was viewed on different size of monitor, laptops and smartphones.
- Travis has been used for testing the project with a "passing" mark.
    Please see below:<br/>
    [![Build Status](https://travis-ci.org/Pauloa90/e-commerce.svg?branch=master)](https://travis-ci.org/Pauloa90/e-commerce)<br/>

- Simple tests were written on the app "hotels" and "products". They ran with "OK" mark.



## Features

Navigation bar is visible on all pages and also the search field in a Jumbotron. If the screen becomes smaller it toggles and the user is able to visualise it on click.
Footer is also visible in every page with social media links.
E-commerce as the main page the user can purchase a product.


## Features do be Implemented
There were a few Features left to be Implemented:
- Contact form - will make the user able to contact the owner of the ecommerce.
- Newsletter - the users will receive any update from the webpage with deals and good offers.
- Social media - the webpage is ready to change the link if the ownerhas other social medias such as Facebook, Instagran, etc.

## Database 
A simple database scheme is represented by the image below.

![Scheme](https://ecommercego.s3-eu-west-1.amazonaws.com/static/wireframes/databsae+schema.png)

## Installation
To be able to create the app the folowing steps were taken:

1. Start with gitpod full template and install Django with the following comand: pip3 install django==1.11.24

2. Create a project with django: django-admin startproject ecommerce

3. Download this project by cliking the [link](https://github.com/Pauloa90/e-commerce)

4. Create env.py and .gitignore to keep your secret keys safe.

5. Set up a Strip account and keep the secret key safe on .gitignore

6. Create an Amazon account and crate a bucket to store your media on S3 services provided by amazon.

7. Type on the terminal "python manage.py migrate" to apply migrations to your local sqlite database.

8. "python3 manage.py createsuperuser" will create a user able to add files to the database or create a new database.

9. To run the project type on terminal "python3 manage.py runserver".



## Deployment
### Amazon 
I created an Amazon account in order to user the service called S3. S3 is a cloud based service tha AWS provides to storage any media or static file for my project. After creating the account, I created a bucket with a name realted to my project.
In this case called "ecommercego". After created the bucket, I went to properties to make it able to hot the static file and media from my project.  
Then I created a policy and a user in Amazon, using the service called IAM(identity and Access Management). 
Those were necessary to manage which user is allowed to change and change the buckets propertie.
Then we go on CORS configurations and prefilled with a default code config. Going on the created bucket policy and attaching the policy to the bucket, it will allow the our account to accsess all the content across all web.
Going again on IAM, we createad a group and set the policies to all. That will create a file that must to be kept safely with the ID and Key to have access to the policy.

When all this is set, we install Boto3, that will allow the storaging on S3. Go to installed apps and add Django Storages.

Once that everything is fine run "python3 manage.py collectstatic" and confirm when asked "yes" to collect all files from our project and host them into S3.

In order to deploy this project a python package Gunicorn was installed and Heroku is the hoster of this project.

### Heroku
Heroku is the service the we are using to host our website. It is synced to the master branch of the Git repository.

In order to deploy please go through the following steps:
- Log in into Heroku and create a "New app".
- Choose a name for you app and region to be hosted and click on "create app"
- Click on "config Vars" once that you select your app just created and set all the variable in Heroku. You can check your env.py where the secret keys are.
- Create the requirements.txt file with all the libraries installed to make your app run typing: pip3 freeze -- local > requirements.txt.
- Create  Profcile typing: echo web: gunicron < NAME OF YOUR PROJECT >.wsgi:application > Profcile
- On Heroku's settings copy http://< app_name.herokuapp.com >
- On the tab "Deploy" find the method of deployment "GitHub" selecting the project your Git Hub account.
- Click on "Deploy" and your project will be hosted by Heroku once the build is complete.
- Once that all is done go to "Open app" to check your project.


## Credits

Thoses are the links for the pictures posted on the Home page of the ecommerce:

[New Zealand](https://www.newzealand.com/in/nature-and-wildlife/)<br/>
[Cancun](https://www.mexicancaribbean.travel/cancun/)<br/>
[Madagascar](https://www.booking.com/hotel/mg/heure-bleue.html)<br/>
[Angra Dos Reis ](https://media-cdn.tripadvisor.com/media/photo-s/0f/73/be/04/img-20170423-125021-360.jpg)<br/>
[Coles Bay](https://en.wikipedia.org/wiki/Coles_Bay,_Tasmania)<br/>
[Pink Bay](https://cdn.broadsheet.com.au/cache/ba/f0/baf05ddfb005ae00d701ec6a69abb59e.jpg)<br/>
[Autralia](https://www.cntraveler.com/galleries/2015-12-18/the-10-best-beaches-in-australia)<br/>
[Turkey Beaches](https://travelaway.me/best-beaches-turkey/)<br/>
<br/>

The text of both section "Discover" and "Curiosities" were not written and also the pictures taken by me but by the authors below:<br/>
- Discover:


[Thailand](https://www.austinadventures.com/travel-resources/20-fun-facts-about-thailand/)<br/>
[Australia](https://www.travelnation.co.uk/blog/10-interesting-facts-about-australia-that-may-surprise-you)<br/>
[New Zealand](https://www.swedishnomad.com/facts-about-new-zealand/)<br/>
[Brazil](https://www.natgeokids.com/nz/discover/geography/countries/country-fact-file-brazil/)<br/>

- Curiosities <br/>
[All the blogs](https://www.under30experiences.com/blog/top-10-travel-bloggers-you-should-already-be-following)
<br/>

## Acknowledment
- Thank you Code Institute for this amazing course.
- Thank you Aaron Sinnott for your feedback and your time.
- Thank you Kerry College for providing us an amazing place to study.
- Thank to all Code Institute tutors from the Tutor Assistance Tab.