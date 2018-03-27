# **Gesture-Based-UI**

## **Repository Table of Contents**
1. [Project Specification](https://github.com/DonalMcGahon/Gesture-Based-UI-#project-specification)
1. [Purpose of the application](https://github.com/DonalMcGahon/Gesture-Based-UI-#purpose-of-the-application)
1. [Purpose](https://github.com/DonalMcGahon/Gesture-Based-UI-#purpose)
1. [How it works](https://github.com/DonalMcGahon/Gesture-Based-UI-#how-it-works)
1. [User Interface](https://github.com/DonalMcGahon/Gesture-Based-UI-#user-interface)
1. [Screenshots](https://github.com/DonalMcGahon/Gesture-Based-UI-#screenshots-of-user-interface)
1. [Gestures identified as appropriate for this application](https://github.com/DonalMcGahon/Gesture-Based-UI-#gestures-identified-as-appropriate-for-this-application)
1. [Hardware used](https://github.com/DonalMcGahon/Gesture-Based-UI-#hardware-used-in-creating-the-application)
1. [Architecture](https://github.com/DonalMcGahon/Gesture-Based-UI-#architecture-for-the-solution)
1. [Conclusions & Recommendations](https://github.com/DonalMcGahon/Gesture-Based-UI-#conclusions--recommendations)

### **Project Specification:**
Develop an application with a Natural User Interface. You have a choice of technologies available to you and an opportunity to combine a lot of technology that you have worked with over the past four years.

At the very least, this should be a local implementation of the application using gestures to interact with it. You can expand out to include real-world hardware and use this as an opportunity to prove a concept. The Internet of Things is a common phrase, so you could implement a solution taking advantage of hardware like the Raspberry Pi, using the cloud for data transfer and creating a realworld scenario through this medium.

The programming language is your choice and there are several options including JavaScript C#, C++ and Lua.

## **Purpose of the application:**
### **Purpose:**

The purpose of this application is to allow the user to interact with muliple instruments by using gestures. The user will be able to select a certain instrument, weather it be a piano, guitar, drum set or trumpet, and create sounds using gestures with these instruments. As well as creating sounds the user will be able to record the music they created and play it back.

### **How it works:**

The application is a Windows universal app, so the application is launched using Visual Studio. The user of the application must have a [Myo Armband](https://www.myo.com/) to interact with the application. When the app is launched the user is greeted with an opening page displaying a curtain and a hamburger view. Inside the hamburger view the user can navigate to 4 different instruments which include a piano, a guitar, drum set and a trumpet. Once the user navigates to any of these instruments, the instrument itself will appear on the screen and the user can now use that instrument and create sounds. The user makes gestures to interact with the instrument they have choosen. The gestures that are avaliable with the myo armband are creating a "Fist", "Finger tap", "Finger spread", "Wave out" and "Wave in". All of these gestures will create a sound with the instrument the user has choosen. When the user chooses, they can record the sounds they are making with the instrument by pressing the record button on the bottom of the screen. Once finished recording they can press stop. To play back the music they just created they can press the play button.

### **User Interface:**

The user interface has a simple user friendly appeal. Their is a hamburger view on the left hand panel. The user can click this hanburger view and it will have a list of instruments for the user to choose from. 1 - Piano, 2 - Guitar, 3 - Drums, 4 - Trumpet.
The users can navigate from one instrument to the next using this hamburger view.
On the bottom of each of the instruments xaml pages their is a bottom app bar. On this bar is the record, stop and play buttons.

### **Screenshots of user interface:**

#### Piano:

![image](https://user-images.githubusercontent.com/14197773/37923388-efae2726-3126-11e8-8b8c-20e329b557fe.png)

#### Guitar:
![image](https://user-images.githubusercontent.com/14197773/37923454-1221d7d0-3127-11e8-8add-7dda87f9ca88.png)

#### Drums:
![image](https://user-images.githubusercontent.com/14197773/37923517-35f6c1a2-3127-11e8-9cb0-12e3bcc0a4f3.png)

#### Trumpet:
![image](https://user-images.githubusercontent.com/14197773/37923597-68fcd942-3127-11e8-86c8-d7ef2496148b.png)


## **Gestures identified as appropriate for this application:**
When we came to an agreement to use the Myo armband for our application we first researched what gestures were available with this technology. We found out that the Myo armband recognizes 5 pre-set gestures out of the box. They are as follows:

**Wave Left:**

![wave-in](https://user-images.githubusercontent.com/14197773/37971999-3840b4e2-31cf-11e8-8550-de2a66a2a585.gif)

**Wave Right:**

![wave-out](https://user-images.githubusercontent.com/14197773/37972291-ed4c308c-31cf-11e8-885d-f7e915ed7cbb.gif)

**Double Tap:**

![double-tap](https://user-images.githubusercontent.com/14197773/37972557-84faf4b8-31d0-11e8-9211-99afe084e4ae.gif)

**Fist:**

![fist](https://user-images.githubusercontent.com/14197773/37973027-7d5e8dcc-31d1-11e8-835d-26a744925626.gif)

**Fingers Spread:**

![finger-spread](https://user-images.githubusercontent.com/14197773/37973242-f60c4e80-31d1-11e8-8dd7-21f12081fd84.gif)

For each of these gestures we found a way to integrate them into our app. We came up with the idea of allowing the user to use any of these gestures to play a certain note or sound from an intrument of their choosing.
We also looked into how user friendly the myo armband was for our application. As our lecturer kindly gave us a myo armband to work with we were able to figure out for ourselves just how user friendly the myo armband actually is. We found that the armband fits very comfortably on the users arm. No matter what size arm the user has it streches and adjusts itself to the arm of the user. We then tested the gestures, each new user can create a custom profile with the Myo armband to allow for better reactions of the gestures. Once your profile is created, their is a series of gesture tests that can be preformed and we can say that the myo armband reacts quite well with all the available gestures.

## **Hardware used in creating the application:**
You are not limited to the hardware listed above. If you have your own hardware, or hardware simulator that you wish to use, then feel free. The purpose of each piece of hardware should be given with a comparison to other options available.

## **Architecture for the solution:**
The full architecture for the solution, including the class diagrams,
any data models, communications and distributed elements that you are creating.

## **Conclusions & Recommendations:**
Conclusions are what you have learned from this project and
the associated research. Recommendations are what you would do differently if you were to undertake the project again. The Reflective Piece – what I learned and “enjoyed” 