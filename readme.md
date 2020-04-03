## myCaffeine
* [General info](#general-info)
* [Technologies](#technologies)
* [Contents](#content)

## General Info
This browser based web application tracks a user's coffee/caffeine consumption. 
First the user must login.  Then they can add (log) cups, and see their history.
There is an optional profiles page to set goals (in construction).
This small project demonstrates:
* read and write to firestore, a non-sql database
* use of firebase authentication and creation of a users collection in firestore
* customized user experience after login/signup
* tracking of a data point provided by the user
* display of a user's history of events
* use of navbar in boostrap

	
## Technologies
Technologies that were used for this project:
* Firebase Hosting
* Firebase Firestore Database
* HTML, CSS
* JavaScript
* Bootstrap 
	
## Content
Content of the project folder:

```
 Top level of project folder: 
├── .gitignore               # Git ignore file
├── 404.html                 # File for error
├── index.html               # landing HTML file, this is what users see when you come to url
├── login.html               # login HTML file, contains logic for user authentication
├── main.html                # after logged in, you can add cups, and see history here
├── profile.html             # page to edit, save your own profile preferences
└── README.md

It has the following subfolders:
├── .firebase                # Folder for firebase
├── .git                     # Folder for git repo
├── images                   # Folder for images
├── scripts                  # Folder for scripts
    /scripts.js              # This is where all the core functions are located
├── styles                   # Folder for styles

Firebase hosting files: 
├── .firebaserc              # Firebase file
├── firebase.json            # Firebase file
├── firestore.indexes.json   # Firebase file
├── firestore.rules          # Rules for read/write to firestore


```

Tips for file naming:
* user lowercase with no spaces
* use dashes (not underscore) for word separation


