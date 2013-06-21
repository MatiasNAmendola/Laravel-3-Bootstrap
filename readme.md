## Laravel 3 Bootstrap - Simple CMS / Backend

I built this for use with some really simple client work. It's not the cleanest code, doesn't utilise templating properly etc however it's a great starter point for people to see how various parts of Laravel 3 works. In development is a Laravel 4 version, utilising more advanced design patterns / features of the framework.

### Feature Overview

- News Articles (with image uploads)
- User Management
- Role Management
- Help and Support (sends an email from a form in the backend)
- Gallery and Images
- Setup Of Database and User Automatic

### Setting Up The Database

- Edit application/config/database.php
- Find the values saying "laravelbootstrap" and change to your own configuration
- Then goto your application URL and append: /admin/setup
- You will need to remove the routes for this in application/routes.php as this isn't automated yet.

### Notes

Things in here are unfinished and a lot of it is undocumented. I've done most of what I can and there will be lots of bugs. This is just a starting point for what I'm hoping will turn into a nice bootstrap for plonking into a new client's website or even your own.

### Contributing to Laravel Bootstrap CMS

Contributions are encouraged and welcome. All commits must be signed off using the "-s" switch.

	git commit -s -m "this commit will be signed off automatically!"
