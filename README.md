# CS360

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The inventory app developed in Android Studio was designed to help users manage inventory efficiently by allowing them to log in, add, update, delete, and view data items, while also receiving SMS notifications for critical updates. The main goal was to create a user-friendly application that would serve as a simple, scalable solution for individuals or businesses to track their items, events, or daily goals. It addressed user needs for secure login, persistent data storage through an SQLite database, and a responsive interface that facilitated easy interaction with inventory data.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The app included three primary screens: a login screen, a data display screen, and an SMS permission screen. The login screen supported user authentication, with fields for username and password as well as an option to create an account. The data display screen incorporated a grid layout to display inventory items with add, update, and delete functionality, ensuring users could easily manage their inventory. Lastly, the SMS permission screen handled requests for SMS permissions and ensured fallback behavior if permissions were denied. The UI design emphasized simplicity and clarity by using logical groupings, consistent themes, and intuitive navigation, making it successful in meeting user needs.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
When coding the app, I followed a modular approach, breaking down functionality into manageable components like the database helper, activities, and adapters. Techniques such as testing in increments, writing reusable methods, and leveraging Android Studio's debugging tools ensured the code remained organized and functional. These strategies made it easier to identify and resolve issues and can be applied in future projects to streamline development and maintain scalability.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
To ensure the app worked as intended, I extensively tested it using the Android Emulator and debugged edge cases like denied permissions or invalid inputs. This process revealed areas for improvement, such as ensuring smooth transitions and handling empty states in the database, which were resolved by refining the code. Testing was critical to delivering a reliable user experience.

## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
Throughout the design and development process, innovating to handle challenges like scaling the database to include a "Location" field for each item was necessary. Modifying the database schema while maintaining data consistency required careful planning and testing.

## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The component where I demonstrated the most success was the integration of CRUD operations with the SQLite database, which showed my ability to connect backend functionality with a user-friendly interface effectively. This project strengthened my technical skills and emphasized the value of a user-centered approach in app development.
