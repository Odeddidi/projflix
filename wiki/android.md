
# Android Application Documentation
## Table of Contents
- [Overview](#Overview)
- [User Activities](#user-activities)
- [Admin Activities](#admin-activities)
- [admin-instructions](#instructions-for-admin)

## Overview
This is a **Android** frontend for a **Movie Management System** that integrates with a **Node.js backend**. The system allows users to **browse, search, add, edit, and delete movies and categories** while maintaining user authentication and admin roles.

This android app availble in two languges, English and Spanish, depends on your phone settings.

## User Activities

### 1. Welcome Activity
- The landing page of the application.
- Displays a hero banner or introductory section.

  ![alt text](androidDoc/landing_page.jpg)

- In light mode:

![alt text](androidDoc/landing_page_light.jpg)

- In Spanish: 

![alt text](androidDoc/landing_page_spanish.jpg)



### 2. SignUp Activity
- Allows new users to **create an account**.
- Contains fields for **email, password, confirm password, and profile picture**.

![alt text](androidDoc/sign_up_activity.jpg)

### 3. LogIn Activity
- Enables existing users to **log in**.
- Requires **email and password**.

![alt text](androidDoc/log_in_activity.jpg)

### 4. Home Activity
- Displays **movies categorized by promoted categories**.
- Each category appears as a list of **small-sized movie component** using recaycler view.

  ![alt text](androidDoc/home_activity_user.png)


### 5. Search Activity
- Allows users to **search movies dynamically**.


![alt text](androidDoc/search_activity.png)

- Allows users to watch movies by category

![alt text](androidDoc/category_activity.png)


- In light mode:

![alt text](androidDoc/search_movie_light.png)

### 6. Profile activity
- Displays user **profile details**.
- Alows the user to sign out 

![alt text](androidDoc/user_details.png)

- In light mode:

![alt text](androidDoc/user_details_light.png)
 
 ### 7. Movie Details Activity

 - The Movie Details Activity open after clicking on a movie and uniqe to every movie.
 - This activity displayes all the info about the movie (name,duration,director...) and a play button. 
 - Also displays similar movies using recaycler view and adapter.

![alt text](androidDoc/movie_details_activity.png)

- In light mode:

![alt text](androidDoc/movie_details_light.png)

### 8. Video player
the page where you can watch the full movie

![alt text](androidDoc/video_player_activity.png)

---
    



## Admin Activities

### Home Activity

- Same as the users Home Activity but with extra button for the admin area in the action bar. 

![alt text](androidDoc/home_activity_admin.png)


### Admin Category activity 
- Clicking the admin button will open the admin activity
- The admin can choose between categories and movies 

![alt text](androidDoc/admin_categories.jpg)

### Add Catgory Activity
- In the categories admin activity the admin can add a category:
 ![alt text](androidDoc/admin_add_category.jpg)

- For example:

![alt text](androidDoc/admin_add_category_example.jpg)

### Admin Movies Activity
- The activity that alows the admin to manage all the movies 

![alt text](androidDoc/movies_activity.png)


### Add Movie Activity
- In the movies admin activity the admin can add a movie:
 ![alt text](androidDoc/admin_add_movie.jpg)

- For example:

![alt text](androidDoc/admin_add_movie_example.jpg)

### Edit Movie Activity
- In the movies admin activity the admin can edit a movie:

 ![alt text](androidDoc/admin_edit_movie.jpg)


## instructions for admin 
after you create a user you shuld go to the data base **nongoDB compass** 
then you will see the new user under **users** 

![alt text](webDoc/user.png)

- change the role from **user** to **admin** 

![alt text](webDoc/admin.png)

**important**: to use the admin fetures you should log out and log in again. 
