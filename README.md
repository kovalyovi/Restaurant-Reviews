# Restaurant Review App
---

## Background
This app was created as the final project with Udacity. I wanted to thank them for 
providing such a course where I could learn so many things about Web Development.
This particular project simulates an HTTP request and reads from the file ./data/restaurants.json
the data and then fetches this data on the screen. One of the biggest parts of this 
project was registering ServiceWorker to keep cache and make it available to run the app 
without the Internet. Also, the page is designed to be accessible. 

## Running Guidelines (+ testing)
The application itself is run under [this link](https://kovalyovi.github.io/Restaurant-reviews). However,
the code is found in my repository, which is [here](https://github.com/kovalyovi/). In order
to run this code from a computer (index.html) - it should work without any issues but it
needs the Internet connection to load data from my folder. However, if you are going to run it
through the localhost - go to the js/dbhelper file and modify `getProjName` method with
your root directory (folder name) and make sure `DATABASE_URL` is pointing to the right spot.
Also, all `<a href="./">` might be changed to something that fit your system

## Credits
Special thanks to the Udacity team who supported me throughout the course. Also, I'm very 
grateful to other students who participated in this project who shared ideas on how
to solve some problems.