# CS360
SNHU CS360: Mobile Architecture and Programming

1) Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

  Of the three choices of scenarios for the final project, I decided to choose the weight tracking app. The requirements of this app were focused on the ability to track a user’s weight and alert them once their goal weight was met. In addition to the core functionalities, the app was to allow users to view, edit, and delete weight entries as well as creating a new account.

2) What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

  To facilitate the user experience, several different screens to serve the different functions of logging in, adding measurements, and enabling notifications. For the final UI design, it was decided that three unique screens would be implemented with navigation controls provided by a bottom navigation bar component. The UI was designed to present the data to the user clearly and the guiding principle was that the UI would be understood by most users upon first glance. This design was successful because all functionalities were able to be retained while still conforming to the Material Design Guidelines.

3) How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

  During the creation of the app, several different coding structures were required to satisfy the needs of each functionality. The app uses fragments to implement each of the three main screens in the app while alert dialogs implement most of the popup menus/options. This app required the use of an SQLite database to store and track weight data. There are several ways to integrate that API within an Android app, but I chose to use a database handler to control and process request made to the database. This database was then split into three tables to store three different data models corresponding to user accounts, goal weights, and weight measurement. All these techniques will benefit future projects by allowing for a deeper integration of APIs for expanded functionality and through repeatable modular components that can easily be migrated.

4) How did you test to ensure your code was functional? Why is this process important and what did it reveal?

  As I learned throughout the development process, testing had to be done frequently with the tests interweaving the development of the code. Each test uncovered new information on what not to do and insight on how to refactor the logic into a working program. Exception handling was created in some of the more complex areas to further ensure the reliability of the program.

5) Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

  Since this project was my first experience with Android app development, challenges arose around every step of the process. From the beginning I had a clear image of what the product should look like, and the development of the app was molded around that idea. The largest innovation came from the creation of a custom calendar that allowed for weight data to be shown on the corresponding dates. There was no existing component to modify into what was needed and the current implementation was built from the ground up to meet the requirements.

6) In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

  As mentioned previously, the calendar element to display weight data to the user was an incredible stretch of my coding abilities. Particularly, the use of a hash map pairing dates with corresponding UI components in a dynamic fashion gave me great experience in data modeling. This project presented a unique opportunity to grow and refine my existing skillsets into a package that is ready for the challenges of modern mobile application development.
