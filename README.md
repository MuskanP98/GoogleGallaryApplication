### Gallery Application Documentation  
**MUSKAN PATEL – Cloud Assignment**  

---

### Introduction  
The "Gallery" web application is built using Python Flask and Google Cloud Datastore. It is a simple yet powerful platform where users can create, manage, and explore photo albums. The application ensures secure user authentication and authorization, allowing users to log in, sign up, and manage their profiles. It combines essential features like album creation, photo uploads, and duplicate detection to offer an engaging and efficient user experience.  

---

### Project Outline  
1. **Core Features**:  
   - **User Authentication & Authorization**: Users can log in, sign up, and log out securely.  
   - **Profile Management**: Users can update their personal information, including name, username, and email.  
   - **Album Management**: Create, edit, and delete albums with custom cover images.  
   - **Photo Uploads**: Users can upload photos to specific albums, with built-in duplicate detection using checksums.  
   - **Gallery View**: Displays all user-created albums with individual photo previews.  

2. **Technical Overview**:  
   - **Backend (app.py)**: Handles HTTP requests, user authentication, album management, and interaction with Google Cloud Datastore.  
   - **Duplicate Prevention (checksum.js)**: Ensures no duplicate photos are uploaded by calculating and comparing file checksums.  
   - **Firebase Integration (app-setup.js)**: Provides secure storage, authentication, and real-time functionality.  

3. **HTML Templates**:  
   - **album.html**: Displays all albums and allows users to create, edit, or delete them.  
   - **login.html**: A simple login page for user authentication.  
   - **photos.html**: Allows users to upload photos with captions to specific albums.  
   - **signup.html**: Enables new users to register with required details.  

---

### Conclusion  
The "Gallery" application is a user-friendly platform that simplifies photo album management. It combines essential features like user authentication, profile management, album creation, and photo uploads to provide a seamless experience. By leveraging Google Cloud Datastore and Firebase, the app ensures security, reliability, and efficiency. The "Gallery" application is an excellent tool for organizing and sharing memorable moments, making it ideal for photographers and photo enthusiasts alike.
