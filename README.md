# educloud

## Project: Capstone, Stage 1 - Design
#### _Udacity Android Developer Nanodegree Project# 7_

### Project Overview
In the Capstone project, you will build an app of your own design in two stages. In Stage 1, you will design and plan the app, using a template that we provide in the "Instructions" node.

Creating and building your own app idea can be both exciting and daunting; ultimately, we want the experience to be rewarding. You'll apply a wealth of different concepts and components that you've learned across the Nanodegree to bring you own app idea to life.

To keep the process from becoming overwhelming (or simply chaotic), you will design and plan your app, and receive feedback, before you start building. This will help prevent and mitigate pain points you might run into along the way, and also replicates the process of professional Android Developers.

### Why this Project?
To become a proficient Android Developer, you need to design apps and make plans for how to implement them. This will involve choices such as how you will store data, how you will display data to the user, and what functionality to include in the app.

### What Will I Learn?
Through this project, you'll demonstrate the ability to communicate an app idea formally, using:

- An app description
- UI flow mocks, similar to what you've seen in other Nanodegree projects, like the Popular Movies overview
- A list of required tasks that you will complete to build the app, in order

The Capstone project will give you the experience you need to own the full development of an app. This first stage replicates the design and planning experience that proficient Android Developers are expected to demonstrate.

---
## Proposal Submitted

## eduCloud

### Description 

This app aims to ease the process of sharing studies related material e.g. lecture notes, ebooks, research material, etc. with the world. 

### Intended User
Any one related to the field of studies e.g. students, teachers, researchers, etc.

### Features

- Upload docs
- Download docs
- Search for docs

### User Interface Mocks

#### Main screen
![Main screen](https://github.com/hmhamza/educloud/blob/master/User%20Interface%20Mocks/main%20screen.jpg)
 
This is the main screen of the app. User can search his query which can lead him to the Search Results Screen. User can also do the advanced search on Advanced Search Screen which allows him to apply some filters on his query. User can click on Contribute button which leads him to the Contribute Screen.


#### Search results
 ![Search results]()
This screen displays the search results that the user searched for on the main screen. User can also search for a new query on this screen.

#### Advanced search
![Advanced search](https://github.com/hmhamza/educloud/blob/master/User%20Interface%20Mocks/advanced%20search.jpg)
This screen displays the search results and also allows the user to apply some filters on his query.

#### Contribute screen
![Contribute screen](https://github.com/hmhamza/educloud/blob/master/User%20Interface%20Mocks/contribute%20screen.jpg)
 
On this screen, user can upload any material that he wants to share with the learning community of the world. User can fill out the different fields and attach docs to the post.

#### App's widget
![App's widget](https://github.com/hmhamza/educloud/blob/master/User%20Interface%20Mocks/widget.jpg)
 
This is the app’s widget which will display the downloaded or marked favorite docs.

### Key Considerations

- App will be written solely in the Java Programming Language
- Android Studio (version 3.1.3) will be used with Gradle version (3.1.3)

#### How will your app handle data persistence? 

As this app requires to upload and download documents, using Firebase would be a better option.

#### Describe any edge or corner cases in the UX.

I don’t think of any right now.

#### Describe any libraries you’ll be using and share your reasoning for including them.

- Firebase (16.0.1)
- Picasso (2.5.2)
- Retrofit (2.4.0)
- Butterknife (8.8.1)

#### Describe how you will implement Google Play Services or other external services.

- Google Mobile Ads
AdMob can integrated for the app’s business model
- Google Account Login
This can be implemented for user authentication

#### How you will support for accessibility?

Android devices have several settings to make screen easier to see:
- Display size and font size: To change the size of items on your screen, adjust the display size or font size
- Magnification gestures: To temporarily zoom or magnify your screen, use magnification gestures
- Contrast and color options: To adjust contrast or colors, use high-contrast text, color inversion or color correction

#### How resources will be stored in the project including colors, strings, and themes?

Color, strings and themes will be stored in their corresponding xml resource files i.e. colors.xml, strings.xml and themes.xml respectively.

#### How the application implements one or more of the following SyncAdapter/JobDispacter or IntentService or AsyncTask for backend communication?

AsyncTask can be implemented to aid the backend communication with the server e.g. for uploading and downloading documents.

### Next Steps: Required Tasks

This is the section where you can take the main features of your app (declared above) and break them down into tangible technical tasks that you can complete one at a time until you have a finished app.

#### Task 1: Project Setup

Create a project in Android Studio and create basic workflow of the application. Like create all activities (empty) and try to setup basic communication among them.

#### Task 2: Implement UI for Each Activity and Fragment

After creating the basic workflow, design and implement UI for every activity.

#### Task 3: Implement Upload and Download
Implement upload functionality which uploads some docs along with related information to the server. After that, download functionality will be implemented.

 #### Task 4: Implement Search Functionality
After successfully implementing the upload functionality, implement search which sends a query to the server, server then performs search in the database and returns the most meaningful results which are then displayed in the app.


---
## Proposal Review

Hi you have done a great job with your design and your app idea is unique and impressive.
Best of luck with its implementation happy learning :D

### Common Project Requirements

##### :heavy_check_mark: App is written solely in the Java Programming Language

Good job mentioning this in your design.

##### :heavy_check_mark: App utilizes stable release versions of all libraries, Gradle, and Android Studio.

Great work mentioning versions of all libraries, Gradle and Android Studio.

Design and Plan Review
##### :heavy_check_mark: Proposal contains an overview description.

##### :heavy_check_mark: Proposal contains a description of the intended user.

##### :heavy_check_mark: Proposal contains user interface mocks.(*including a UI mock for the app's widget)

Awesome work adding UI mock for your app's widget.

##### :heavy_check_mark: Proposal declares the app’s primary features.

##### :heavy_check_mark: Proposal outlines any key constraints such as data persistence, UX corner cases, and libraries used. App clearly outlines how a database will be implemented.

##### :heavy_check_mark: Proposal describes a plan to implement the main features of the app via a set of well structured technical tasks.

##### :heavy_check_mark: UI mocks depict interaction stories that adhere to [Core App quality guidelines](http://udacity.github.io/android-nanodegree-guidelines/core.html).

##### :heavy_check_mark: App design specification demonstrates implementing all features required for Project 8: Capstone, Stage 2 - Build.

Great work providing all the required information and using AsyncTask for background operations.

---

## Project: Capstone, Stage 2 - Build
#### _Udacity Android Developer Nanodegree Project# 8_

## Coming Soon
