Welcome to the Gsoc2019Malaria wiki!

# Malaria Android App Extension Pitch

# About Me
My name is Mohak Gupta, pursuing BCA from Vivekananda Institute of Professional Studies, Delhi, India.    
I am a GSOC 2019 aspirant. I want to work on the Malaria Android App of the Systers organisation.

_Peace Corps is looking to build a mobile app that will aid the Volunteer in sustaining life-saving malaria prevention tactics over their 2+ years of service. Prevention is focused on sustained use of preventive medications, which are taken either daily or weekly, depending on the medicine. The application will feature a reminder system; an ability to indicate that medication was taken on time or missed; the ability for the volunteer to track their usage history; a trip indicator to help remind volunteers to pack certain supplies to prevent malaria if they leave their home village; and an Info Hub that will provide accurate information about Malaria and the medications they are taking._

**I want to work on extending and improving the Malaria Android App.  I have compiled a list of various things that can be improved and can be added in this project.**

1. **Kotlin**
2. **MVVM Architechture**
3. **RxJava + Room**
4. **Articles/Newsletter Related to Malaria**
5. **Daily Unknown Facts about Malaria**
6. **List Of NGOs with their Details fighting against Malaria**
7. **UI Improvements and implementing InfoHub feature(which is empty right now)**

### Kotlin
Refractor the entire Malaria Android App to use Kotlin instead of Java, because Kotlin has many advantages over Java. Few of them are listed below:-
* It's (way) More Concise Than Java
* Safer Code
* It Comes With a Smarter and Safer Compiler
* It Has Null in Its Type System
* And many more...

### MVVM Architechture
The current state of Malaria Android App is tightly coupled, because it is using MVP Architecture. Each Activity has its own presenter and own view. This leads to difficulty in Testing Environment.  With the use of MVVM Architecture, the application becomes loosely coupled resulting in less code and less number of classes as compared to MVP Architecture and with the use of MVVP Architecture, both UI and Unit Testing becomes easier to write.
Google introduced Android Architecture Components, which contains ViewModel rather than Presenter.  A single view can hold reference to multiple ViewModels.

![mvvm](https://user-images.githubusercontent.com/35039342/50704949-29d18a00-107f-11e9-9562-456ec5526975.PNG)

 
### RxRoom (RxJava + Room)
Recently, in 2.1 version of Room Persistence Library in Android Architecture Components, Google released new feature named as **RxRoom**.  It means that now, RxJava can be integrated with Room. And it comes with lots of benefits, that we can have async return types with Room. Right now, Malaria Android App is using only Room library, and I want to integrate RxJava with it.

### Articles/News Related to Malaria
I want to introduce new feature in Malaria Android Application. I want to integrate News feature in the Malaria Android App. It will be very beneficial for the users who are suffering from the Malaria, It will display the news related to Malaria so that the users who are suffering from Malaria (using our App) will get to know the latest updates regarding the disease like New ways to cure malaria, information regarding the disease, steps the government is taking to cure it or reduce it in the coming years, and many more...  

### Daily Unknown Facts about Malaria
This is the another feature that I am planning to integrate in the Malaria Android App. What this feature will do, Daily, it will show some unknown fact about Malaria in the form of Notification and on click of that notification the detailed view of that fact will be presented and from the app, User will have the option to disable the notification or enable it. Basically, It will increase the user engagement in the App and also it will serve as the another source of information regarding Malaria.

### List Of NGOs with their Details fighting against Malaria
This is the another feature that I would like to integrate in the App. One section of the App will shows the list of some NGOs in the World which are fighting against Malaria and how they are providing an organization to the patients who are suffering from Malaria. This feature will contain the details of that NGOs and **how they are saving the life of people suffering from Malaria, their Mission, Progress and how to get in touch with them, how they can be a part of such organizations.**
User will have the share option available in this feature, by which they can share the details about these NGOs and can spread awareness among people suffering from Malaria.

### UI Improvements and implementing InfoHub feature(which is empty right now)
At last, I want to refractor the UI of the Application. Currently, the UI of the App seems dull to me and I will enhance and improve the existing UI and will implement features in InfoHub Screen where currently, only UI is there and else nothing happens.


# Nice to have features(Under Consideration)
* **Add more games in the App or adding more questions in the game**
* **Add more badges and achievements**
* **Adding Profile image in User Profile Section**

### Follow me:-
* **Twitter:** @mohak_gupta20
* **Github:** mohak1283
* **Linkedin:** [mohak gupta](https://www.linkedin.com/in/mohak-gupta-885669131/)