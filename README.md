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
 ![Search results](https://github.com/hmhamza/educloud/blob/master/User%20Interface%20Mocks/search%20results%20screen.jpg)
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

### Project Overview
In Stage 1, you designed and planned your Capstone app. Now, it's time to build it!

### Why this Project?
In this project, you will demonstrate the skills you've learned in your Nanodegree journey, and apply them to creating a unique app experience of your own. By the end of this project, you will have an app that you can submit to the Google Play Store for distribution.

### What Will I Learn?
The Capstone project will give you the experience you need to own the full development cycle of an app.

---
## Project Review

Congratulations! You made it! :fireworks::fireworks::fireworks:

It's been a long way, and after all the efforts you have put in to learn new concepts and pass the projects, you can proudly say that you are an Android Developer!

I hope you enjoyed the course and our support to help you improve your skills! Bear in mind that you'll always be part of the Udacity community, so take your time to share your success with your peers, and keep catching up with them on the Slack channel!

I look forward to seeing your App on the Play Store!
Congratulations again, and recall staying :udacious:!

### Common Project Requirements
##### :heavy_check_mark: App conforms to common standards found in the [Android Nanodegree General Project Guidelines](http://udacity.github.io/android-nanodegree-guidelines/core.html)

Well done in following the guidelines. It's always critical to follow the standards when it comes to providing a good UX. The earlier a user get used to using your App, the easier he will keep using it.

##### :heavy_check_mark: App is written solely in the Java Programming Language

Cool! Java is the primary language we have to know as Android Developers. Even though Kotlin has been recognized by Google as an official programming language to develop Apps (and it's super handy, let's admit it), it's better to have a good grasp of the Java language first.

##### :heavy_check_mark: App utilizes stable release versions of all libraries, Gradle, and Android Studio.

Good job in taking advantage of stable versions of tools, libraries, and Android Studio. I know that sometimes we are tempted to test new stuff as soon as they are put out because they are too cool to wait for a stable version, but as you already know, Beta or even Alpha versions can be plagued by bugs and we, as developers, can't risk providing a bad UX to our users.

### Core Platform Development

##### :heavy_check_mark: App integrates a third-party library.

Good job! You have integrated third-party libraries, and this is a critical thing to learn, cause it's plenty of great libraries out there that you can take advantage of to avoid reinventing the wheel and be more productive.

##### :heavy_check_mark: App validates all input from servers and users. If data does not exist or is in the wrong format, the app logs this fact and does not crash.

Checking everything that comes in your App is a critical aspect to bear in mind, cause when you have control of data your logic works with, you narrow down the possible cases that could make your App crash. Good job!

##### :heavy_check_mark: App includes support for accessibility. That includes content descriptions, navigation using a D-pad, and, if applicable, non-audio versions of audio cues.

Awesome job! As Android Developers we have to take care of anyone, and people with visual or audio impairments should always be put in our priority lane.

##### :heavy_check_mark: App keeps all strings in a ```strings.xml``` file and enables RTL layout switching on all layouts.

Perfect! The App has been set to support the RTL layout, and you have used the correct attributes to make sure to keep the same relative positions among the views in both RTL and LTR mode. Further, good job in taking advantage of the strings.xml properly. That's a super convenient file where you can group all the hard-coded strings in one place. One of the advantages of declaring strings as resources is that you can easily localize your App, and support different languages as explained [here](https://developer.android.com/training/basics/supporting-devices/languages).

##### :heavy_check_mark: App provides a widget to provide relevant information to the user on the home screen.

Cool! The Widget is available for your App to get added to the Home Screen, and it works smoothly.

### Google Play Services

##### :heavy_check_mark: App integrates two or more Google services. Google service integrations can be a part of Google Play Services or Firebase.

##### :heavy_check_mark: Each service imported in the ```build.gradle``` is used in the app.

Good job! You have imported only the libraries that matter, and in this way, the APK won't contain unnecessary code. As a result, it will be as small as possible, and your project will take less time to build.

##### :heavy_check_mark: If ```Location``` is used, the app customizes the user’s experience by using the device's location.

##### :heavy_check_mark: If ```Admob``` is used, the app displays test ads. If ```Admob``` was not used, student meets specifications.

##### :heavy_check_mark: If ```Analytics``` is used, the app creates only one analytics instance. If ```Analytics``` was not used, student meets specifications.

##### :heavy_check_mark: If ```Maps``` is used, the map provides relevant information to the user. If ```Maps``` was not used, student meets specifications.

##### :heavy_check_mark: If ```Identity``` is used, the user’s identity influences some portion of the app. If ```Identity``` was not used, student meets specifications.

### Material Design

##### :heavy_check_mark: App theme extends ```AppCompat```.

Well done! I leave you [a link to a great article](https://medium.com/google-developers/theming-with-appcompat-1a292b754b35) and an [excellent short video from Ian Lake](https://www.youtube.com/watch?v=BaWMVNRhy_A) that talk about AppCompat and why it's essential to use it to end up having a consistent design across all the API.

##### :heavy_check_mark: App uses an app bar and associated toolbars.

##### :heavy_check_mark: App uses standard and simple transitions between activities.

Well done! Standard and simple transitions are implemented as per default by Android, and most of the time they are what our user expects to see on the Layout as he interacts with the App and its views. If you want to read a good tutorial about transitions, take a glance at [this link](https://guides.codepath.com/android/animations).

### Building

##### :heavy_check_mark: App builds from a clean repository checkout with no additional configuration.

Good job! The project has been shipped with all the things required to build and deploy the Release variant.

##### :heavy_check_mark: App builds and deploys using the ```installRelease``` ```Gradle``` task.

##### :heavy_check_mark: App is equipped with a signing configuration, and the keystore and passwords are included in the repository. Keystore is referred to by a relative path.

##### :heavy_check_mark: All app dependencies are managed by ```Gradle```.

You made a good use of the Gradle tool! Good job in getting the most out of this fantastic build tool. Make sure to keep studying it to get the most out of the new features the Gradle team keeps adding day by day.

### Data Persistence

##### :heavy_check_mark: App stores data locally either by implementing a ContentProvider OR using Firebase Realtime Database OR using Room. No third party frameworks nor Persistence Libraries may be used.

Good job in taking advantage of the Firebase Realtime Database to read data.

##### :heavy_check_mark: Must implement at least one of the three.
If it regularly pulls or sends data to/from a web service or API, app updates data in its cache at regular intervals using a SyncAdapter or JobDispacter.
OR
If it needs to pull or send data to/from a web service or API only once, or on a per request basis (such as a search application), app uses an IntentService to do so.
OR
It it performs short duration, on-demand requests(such as search), app uses an AsyncTask.

##### :heavy_check_mark: If Content provider is used, the app uses a Loader to move its data to its views.

##### :heavy_check_mark: If Room is used then LiveData and ViewModel are used when required and no unnecessary calls to the database are made.
