## myCaffeine
* [General info](#general-info)
* [Technologies](#technologies)
* [Contents](#content)

## General Info
This project tracks a user's coffee/caffeine consumption. 
First the user must login.  Then they can add (log) cups, and see their history.
There is an optional profiles page to set goals (in construction).
	
## Technologies
Technologies that were used for our project:
* Firebase Hosting
* Firebase Database
* HTML, CSS
* JavaScript
* Bootstrap 
	
## Content
Content of the project folder:

```
 Top level of project folder: 
├── .gitignore               # Git ignore file
├── 404.html                 # File for error
├── index.html               # landing HTML file
├── login.html               # login HTML file
├── main.html                # after logged in, you can add cups, and see history here
├── profiles.html            # page to edit, save your own profile preferences
└── README.md

It has the following subfolders:
├── .firebase                # Folder for firebase
|-- .git                     # Folder for git repo
├── images                   # Folder for images
├── scripts                  # Folder for scripts
    scripts.js               # This is where all the core functions are located
├── styles                   # Folder for styles

Firebase hosting files: 
├── .firebaserc              # Firebase file
├── firebase.json            # Firebase file
├── firestore.indexes.json   # Firebase file
├── firestore.rules          # Firebase file


```

Tips for file naming:
* user lowercase with no spaces
* use dashes (not underscore) for word separation


