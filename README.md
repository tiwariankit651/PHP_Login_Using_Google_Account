# PHP_Login_Using_Google_Account
PHP Google OAuth API allows users to login in a website with their Google credentials. A user with a Google account need not remember yet another username/password for a web application.
Google OAuth Prerequisites

# Create Google API project and get OAuth credentials.
click here Google Developers Console

# Here are the steps
After this click on Create New Project link for create new project.
Enter Project Name and click on Create button.
Once you have created a new project then you can see your project list on web page.
After this click on Google API logo for go to the home page.
Once you have redirected to home page then select project from the project select box.
After click on project select box, then one modal will popup and under this, you can find a list of project, so select your project.
Now from left menu, you have to click on OAuth consent screen.
Once you have click on OAuth consent screen, then one page will load, here you have to define application name and after this click on save button.
When you have to click on save button, then after page will redirect another page, and here you have to click on Create credential button, so one drop-down menu will appear and from this, you have to select OAuth client ID.
After click on OAuth client ID menu then you have redirected to another page, and here you can find different Application type.
From different Application type option, you have to select Web application. Once you have select the Web application option, then one form will appear on the web page. Here you have to define Name and you have also define Authorized redirect URIs field and lastly click on Create button.
Once you have click on create button, then you can get your Client ID and your client secret key. You have to copy both keys for future use for implement Login using Google account using PHP.
Download / Install PHP Google API client library.
copy this on CMD:- composer require google/apiclient:"^2.0"

# Steps to implement Google authentication

Create / Send authentication request.
Access user data from Google.

# Create Google OAuth Credentials

1: Create a new project and get the corresponding OAuth credentials using Google developer console page.

# Language-specific requirements


To run any of the code samples in this document, you'll need a Google account, access to the Internet, and a web browser. If you are using one of the API client libraries, also see the language-specific requirements below.


# To run the PHP code samples in this document, you'll need


PHP 5.4 or greater with the command-line interface (CLI) and JSON extension installed.
The Composer dependency management tool.
The Google APIs Client Library for PHP:
composer require google/apiclient:"^2.0"
