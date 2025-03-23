# Meme Website using Reddit API

A   web app built using Flask that fetches random memes from the Reddit API `(/r/memes)` and displays them with a  HTML/CSS frontend. The meme refreshes every time the user reloads the page or clicks the _"Get New Meme"_ button.

## Features
- Retrieves random memes from the `/r/memes` subreddit.
- Backend built with Python and Flask.
- Frontend uses basic HTML and CSS for layout and styling.
- Automatically updates the meme on page refresh or button click.

## Technology Stack

- Backend: Python, Flask, Requests, JSON
- Frontend: HTML5, CSS3
- API: meme-api.com

## How It Works
- The Flask backend sends a GET request to the meme API.
- The API returns a meme image URL and subreddit name in JSON format.
- The backend passes this data to the HTML template.
- The frontend displays the meme along with the subreddit it was sourced from.
- The user can fetch a new meme by reloading the page or clicking the refresh button.

## Running the Project Locally
Clone this repository:
```
git clone https://github.com/your-username/reddit-meme-flask.git
cd reddit-meme-flask
```
**_Note: This project is based on Python, so I am supposing you are smart enough that Python is already installed in your PC, if not then install Python first in your PC: https://www.python.org/downloads/_**  
  
Install dependencies:
```
pip install flask requests
```
Also install flask:
```
pip install flask 
```
Run the Flask app:
```
python3 meme_flask.py
```
Copy the localhost URL:  
  
![image](https://github.com/user-attachments/assets/f39c336f-cca9-44b3-816f-17ead5aed142)

Paste this in your browser and everything is set!  
  
![githubmeme](https://github.com/user-attachments/assets/1cec0744-5dba-47af-9ff6-947c8242fe1d)



