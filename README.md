# CS-360-Mobile-Architect-Programming

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The Event Tracker app was designed to help users create, view, and manage upcoming events in one place. The app allows users to log in, add event information such as the name, date, time, location, and description, and view upcoming events. The goal was to provide a simple way for users to keep track of important events and receive reminders so they do not forget them.

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app includes a login screen, event list, add event screen, and notification settings screen. Features include creating and deleting events, storing event information in a database, and setting up event reminders. I designed the screens to keep the layout simple and easy to understand, with clearly labeled buttons and fields. Keeping the number of screens and controls focused on the main tasks helped make the app easier to navigate.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached development by building the app one feature at a time and testing each part before moving on. I used Java and Android Studio and separated different responsibilities into activities and a database helper. I also used debugging tools and error messages to identify problems as they occurred. This step-by-step approach can be applied to future projects because it makes larger applications easier to manage and troubleshoot.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the app by running it in the Android emulator and interacting with each screen and feature. I tested logging in, adding and deleting events, displaying event information, database operations, and notification functionality. Testing revealed problems such as navigation issues, crashes, and reminder functionality that needed additional work. This process was important because code that compiles successfully can still have problems when a user actually interacts with the application.

## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of the biggest challenges was implementing the event reminder functionality. I initially worked toward using SMS reminders, but testing showed that this approach was not working as expected. I had to rethink the implementation and work through Android permissions, scheduling, and notification-related functionality. This required adapting my original approach instead of simply following the initial design.

## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was particularly successful with the database and event-management portion of the application. I created a database structure for users and events and developed the functionality needed to add, retrieve, and delete event information. Connecting the database to the user interface demonstrated my ability to apply Java programming, Android development, and database concepts together to create a functional application.
