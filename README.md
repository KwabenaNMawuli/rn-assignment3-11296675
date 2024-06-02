# rn-assignment3-11296675
This React Native app features a simple user interface with a greeting, task count, profile icon, and a search bar. Below is a brief description of each major component used in the application.

Major Components
SafeAreaView
Purpose: Ensures content is displayed within the safe area boundaries of a device, avoiding overlap with hardware elements like the notch, status bar, or navigation bar.
Usage: Wraps the main content of the app to provide a safe rendering area.
View (Content Container)
Purpose: Acts as the main container for the app's content, organizing the layout and spacing.
Style: Adds padding and gap to space out the child components within the view.
Header
Purpose: Displays a greeting message and a profile icon, providing an introduction to the user and a way to access the profile.
Sub-components:
Greeting Text: Shows a personalized greeting ("Hello, Devs") to the user.
Task Count Text: Displays the number of tasks ("14 tasks devs") the user has.
Profile Icon: A touchable area that includes an image of the user's profile picture.
Style: Aligns the items horizontally and spaces them out evenly.
Search Bar
Purpose: Provides a search input field for users to type queries and includes a filter icon for additional search options.
Sub-components:
Search Input (TextInput): Allows users to enter search queries.
Filter Icon (View): Contains an image acting as a filter button beside the search input.
Style: Aligns the search input and filter icon horizontally and spaces them out.