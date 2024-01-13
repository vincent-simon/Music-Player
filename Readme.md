# Music Player

## Project Overview

Welcome to the project, an exciting music streaming website developed to provide users with an immersive and enjoyable audio experience. It serves as a platform where music enthusiasts can discover, listen to, and curate their favorite songs and playlists.

## Project Goals

The primary goals of the project are to:
- Develop a user-friendly and aesthetically pleasing music streaming website.
- Implement user profiles, including general user profiles and creator profiles for music artists.
- Enable song management features, allowing users to add, edit, and organize their music.
- Provide playlist management capabilities for creating and curating playlists.
- Implement a robust search functionality for songs and playlists.
- Support the addition and playback of .mp3 audio files.
- Create APIs to interact with albums, songs, and playlists.
- Implement CRUD (Create, Read, Update, Delete) operations for songs and playlists.
- Develop additional APIs for generating graphs and statistics for the admin dashboard.
- Implement robust validation for all form inputs, ensuring data integrity.
- Enhance the styling and aesthetics of the website to offer an enjoyable visual experience.
- Establish a secure login system for user accounts and authentication.
- Explore subscription or paid versions of the application for premium features.
- Include features like autoplay and shuffle songs in a playlist to enhance the user experience.

## Technology Stack

Music Player is developed using the following technologies and tools:
- Flask: A Python web framework that provides the foundation for building web applications.
- SQLite: A lightweight and efficient relational database system, ideal for managing music data.
- HTML: The standard markup language for structuring web content.
- CSS: Cascading Style Sheets for designing and styling web pages.
- JavaScript: A versatile scripting language used to add interactivity and dynamic features to the website.


## How to run webapp localy

### create virtual env
```bash
python3 -m venv env
```
### activate virtual env

```bash
source env\bin\activate
```
### install dependencies
```bash
pip install -r requirements.txt
```

### finally run and enjoy the webapp
```bash
python3 main.py
```
### Having issue running this on windows
```bash
switch to Linux 
```



## Project Structure
```bash
your_project/
    ├── app/
    |   ├── __init__.py
    |   ├── admin/
    |   |   ├── __init__.py
    |   |   ├── routes.py
    |   |   ├── templates/
    |   |   |   ├── admin_dashboard.html
    |   |   |   └── ...
    |   ├── auth/
    |   |   ├── __init__.py
    |   |   ├── routes.py
    |   |   ├── templates/
    |   |   |   ├── login.html
    |   |   |   ├── register.html
    |   |   |   └── ...
    |   ├── main/
    |   |   ├── __init__.py
    |   |   ├── routes.py
    |   |   ├── templates/
    |   |   |   ├── index.html
    |   |   |   ├── playlist.html
    |   |   |   └── ...
    |   ├── static/
    |   |   ├── css/
    |   |   |   ├── styles.css
    |   |   |   └── ...
    |   |   ├── js/
    |   |   |   ├── main.js
    |   |   |   └── ...
    |   ├── templates/
    |   |   ├── base.html
    |   |   ├── layout.html
    |   |   └── ...
    ├── instance/
    |   ├── config.py
    ├── migrations/
    ├── tests/
    ├── venv/
    ├── config.py
    ├── run.py
```

## Document Author

Vincent Simon
