# YelpCamp
This project was undertaken by Vivek Jaiswal, Shivansh Shukla and Likhith Reddy Morreddigari for the course Software Engineering Laboratory (CS29202).
## Objective
YelpCamp is an user interactive website which describes different campgrounds from different places and an authorised user can add a campground, edit or    delete it. It also allows an authorised user to add a reviews, edit or delete it.

## Setup and Build Instructions
Open terminal and check for Node version.

```bash
node --version
```
If node is not installed, then install it using the following command :
```bash
# Using Ubuntu
curl -fsSL https://deb.nodesource.com/setup_17.x | sudo -E bash -
sudo apt-get install -y nodejs
```
Now Navigate to the directory containing package.json and run the following command : 
```bash
npm install
```
This will install all the dependencies of the project in node_modules directory.

Now, execute the project by running 
```bash
node app.js
```
---
**NOTE**

If you get any error regarding database, then try to reconnect with different internet connection.
If any other error is encountered then try to delete node_modules directory and rerun the following command in directory containing package.json.
```bash
npm install
```
---

## Features
### Register
User can register in the the platform. 
### Login
User can logged in in the the platform.
### Campground
#### Create
User can create the Campground in the the platform by filling the credentials.
#### Show
User can view the Campgrounds in the the platform.
#### Delete
User can delete his/her Campground in the the platform.
### Review
#### Rating
User can give the rating to the particular Campground in the the platform.
#### Create
User can create the Reviews to the particular Campground in the the platform.
#### Delete
User can delete his/her Reviews to the particular Campground in the the platform.
