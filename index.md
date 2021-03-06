*Click [here](https://github.com/manoaswapshop) to view our GitHub organization page.*
# Table of Contents

* [About The Manoa Swap Shop](#about-the-manoa-swap-shop)
* [Installation Guide](#installation-guide)
* [Development goals](#development-goals)
* [Milestone 1](#milestone-1)
* [Milestone 2](#milestone-2)
* [Milestone 3](#milestone-3)
* [Initial User Study](#initial-user-study)


# About The Manoa Swap Shop

The Manoa Swap Shop is a Meteor application that provides a safe environment for University of Hawaii at Manoa students and faculty to exchange school related goods and services.

Click [here](http://themanoaswapshop.meteorapp.com/#/) to see the running deployment of our system hosted on Galaxy.

# Installation Guide

1. Install [Meteor](https://www.meteor.com/install)
2. Download a copy of [The Manoa Swap Shop](https://github.com/manoaswapshop/swapshop_source) from the GitHub page.  The repository is private so you will need to request for access from the authors.
3. Open up a terminal on your operating system and cd into the app directory of manoaswapshop.  Run the command:
`$ meteor npm install`
4. While you are in the terminal and in the app directory of manoaswapshop, run the command:
`$ npm install --save react-dropzone axios`
5. Once you have installed the libraries, run the command:
`$ meteor npm run start`


This will start the application, which you can see at [http://localhost:3000](http://localhost:3000/).

Lastly, you can run ESLint over the code in the imports/ directory with:

`$ meteor npm run lint`



# Development goals

We want to provide UHM students and faculty with a simple application that allows them to safely exchange goods.  We plan to implement:

* User accounts for students and faculty
* Administrator accounts for moderators
* Listing page for offered goods and services, sorted by categories
* Listing page for wanted goods and services, sorted by categories
* A search function for users to search for goods
* A listing feature for users to add their goods to the listing page
* Pre-designated meeting locations for student and faculty safety.


# MileStone 1

Click [here](https://github.com/manoaswapshop/swapshop_source/projects/1) to see a list of Milestone 1 issues and goals.
* Landing Page
* About Page
* Login and SignUp Page
* User profile page
* User Home Page 

Upon arriving at the website, the user will see the following
[landing page.](http://themanoaswapshop.meteorapp.com/#/)
![.](images/swapshoplanding_galaxy.png)

A brief description of our application can be found on the [about page.](http://themanoaswapshop.meteorapp.com/#/about)
![.](images/swapshopabout_galaxy.png)

When the user [signs in](http://themanoaswapshop.meteorapp.com/#/) to their account, additional options will appear in the navigation bar at the top of the page.
![.](images/LogInPageMockUp.png)

The user may view [their profile](http://themanoaswapshop.meteorapp.com/#/userprofile) once they have logged into their account.  On this page, the user's contact information will be displayed along with a listing of their items.
![.](images/UserProfilePageMockUp.png)

The user may also choose to [edit their profile](http://themanoaswapshop.meteorapp.com/#/editprofile) should any of the information provided becomes outdated.
![.](images/EditUserProfileMockUp.png)


# Milestone 2
Click [here](https://github.com/manoaswapshop/swapshop_source/projects/2) to see a list of Milestone 2 issues and goals.
* Item Category Pages
* Item Listing Creation
* Linked Item Cards
* Admin Tools
* Setup User Collection for User Profile Pages
* Create User Profile Page
* Edit Profile Functionality

1. To begin usage of the Manoa Swap Shop application, you must sign up for a new account. Immediately after you sign up, a [User Profile Creation Page](http://themanoaswapshop.meteorapp.com/#/create) will pop up that will add your information into your user profile.
![.](images/M2UserProfileCreationPage.png)
Once you have submitted your information the [User Profile](http://themanoaswapshop.meteorapp.com/#/userprofile) page will update to show all the changes that were added.
![.](images/M2UserProfilePage.png)
2. Now you have your user profile set up! If you made any errors you can always fix anything in your user profile by clicking on the edit button in the User Profile Page. This edit button will take you to an Edit Profile Page where you can make changes to any of the previously submitted fields.
![.](images/M2EditProfilePage.png)
After you submit your changes on the edit page your user profile page will update with these changes.
![.](images/M2EditedProfilePage.png)
3. Onto the items part of the app. If you click on the ["List an Item"](http://themanoaswapshop.meteorapp.com/#/add) in the nav bar it will take you to a page where you can create a new item listing.
![.](images/M2ListItemPage.png)
Once you have filled out all of the required fields and submitted, the item that you have just listed will show up on the [Listed Items](http://themanoaswapshop.meteorapp.com/#/list) page.
![.](images/M2ListedItemsPage.png)
In addition, all of the items that you yourself have listed will show up on your user profile page.
![.](images/M2UserProfileItemsList.png)

# Milestone 3
Click [here](https://github.com/manoaswapshop/swapshop_source/projects/3) to see a list of Milestone 1 issues and goals.
* Item Card Page
* Image uploading
* Item delete feature for sellers

1. An image uploading feature has been added to the profile creation page that will allow users to upload a user profile image.
![.](images/M3ProfileCreationImageUploading.png)

Uploading works by clicking on the box with a description of how to use it and then select a image file from your local device. The image url will fill out the image textfield once your image has been uploaded. Make sure to make some sort of button input into the text field to ensure that it registers properly.
![.](images/M3ImageUploading2.png)

2. The user profile image can be edited in the edit profile page.
![.](images/M3EditProfileImageUploading.png)

3. An item deletion button has been added to allow users to delete their listings after they have sold.
![.](images/M3ItemDeleteButton.png)

4. Image uploading has been added to the List Item page.
![.](images/M3ItemImageUploading.png)

5. The items listing page now contains links for evey item that leads to a more detailed item card page.
![.](images/M3ItemListWithLink.png)

The item card page contains some additional information about each item and includes the picture that is uploaded during the creation of the listing.
![.](images/M3ItemCard.png)





# Initial User Study

We recruited other college students to provide feedback on our almost completed app to find out things that they enjoyed and things that we could improve upon. The process of getting this feedback started with us giving a quick walkthrough of how to use all of the features in our app and then allowing them some time to play around with it and explore it for themselves. After they had a good amount of time using our app we, we asked them about their thoughts and how we can make the Manoa Swap Shop a better experience for users. 

Constructive Criticism: 
- Add a search bar and filters
- Allow users to sort items by categories within one page
- Add messaging system for users
- More streamlined image uploading process
- Make important features and links easier to see, such as the 'help' & 'categories' section.

Things they liked: 
- Aesthetically pleasing, theme matched with Manoa(school colors)
- Customizable profiles
- All available items are listed


