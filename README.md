# Mystoryhub
This repository contains the source code for a cross-platform mobile application built using Flutter. The app retrieves and displays albums and posts for a user from various API endpoints. It is compatible with both iOS and Android platforms.

![Frame 87](https://github.com/abhi-staark/Mystoryhub/assets/88762793/e477e831-181f-4b2d-9707-f471fb54d6cc)
**Features:**

1. **Homepage:**
   - Displays user profile with options to upload a photo or take a selfie using the camera.
   - Includes the user's location.
   
2. **Album Detail View:**
   - Presents albums in a grid view with two items per row.
   - Each album is represented by a box with a folder icon and title.
   - Tapping on an album navigates to a detailed view with photos associated with that album.
   
3. **My Posts Section:**
   - Displays posts retrieved from the Posts API for the user.
   - Each post shows the title and body.
   - Tapping on a post opens a detailed view with comments.
   
4. **Shared Elements:**
   - Ensures a consistent and visually appealing UI across the entire application.
   - Implements proper navigation between different sections.
   
5. **Offline Handling:**
   - Implements offline data handling, enabling users to view previously fetched data even without an internet connection.
   
6. **Code Quality:**
   - Utilizes the **BLoC architecture** for state management.
   - Follows **SOLID** principles in the codebase.
   - Organizes project structure into folders like `business_logic`, `common`, `constants`, `config`, `lib`, `data`, `presentation`, and `services` for structured understanding.
   
This repository serves as a demonstration of building a Flutter application with features such as API integration, offline support, and UI design while adhering to best practices in software development.

Feel free to explore the code and use it as a reference for your own projects. If you have any questions or suggestions, please open an issue or reach out to the project maintainers.







