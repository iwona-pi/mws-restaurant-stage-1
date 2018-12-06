
#### Restaurant Reviews

## About Project

For the **Restaurant Reviews** projects, I incrementally converted a static webpage to a mobile-ready web application. I took a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. I also added a service worker to begin the process of creating a seamless offline experience for all users.


## How to run?

1. Simple clone this repo.
2. Run the server:   
   * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
    * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
3. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.


## Note

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/).
### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
