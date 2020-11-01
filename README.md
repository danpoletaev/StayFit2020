# EduVest (by StayFIT).

Team **StayFIT** at **HackPrague2020** hackathon would love to introduce you to its
lovely HackPrague2020 hackathon child - **EduVest**. **EduVest** is a mobile platform
that helps people to become more financially literate, small businesses to recover
in the reality of economic crises and banks to become more popular and loved by the clients.

## Project description

The main idea of our project is to create an education platform for all online-banking users. This app will help people not only learn how to manage their finances efficiently, but also see improving using the statistics from his personal online banking account. We decided to use discount promotions for small business production as a motivation to study and growing financial freedom.

The user authorize by his phone number and choose his main financial goal. After that he has an access for courses. After completing each course the user has to take a test and if all his answers are right, he will get a promo. 

All discounts are listed in personal profile. There are another two sections in personal profile: Goals and My courses. In Goals all financial tasks(e.g. Spend 100$ less than last week) are listed. Another way to get a discount for small business production is to complete all tasks.

This way a person broaden his mind and improve his financial status. The progress is visible in Statistics, which was made with the help of personal online banking data.

## Installation and running

To successfully install and run **EduVest** you would need to:

* clone this repository to your local machine;
* install the requirements for the backend server and run it;
* install Expo app on your mobile device;
* install the requirements for the frontend client and run it.

Let's install and run the application step-by-step.

#### 1. Pull the repository

You can simply accomplish this by typing

`git clone https://github.com/salveron/StayFIT_HackPrague2020.git <project_directory>`,

where `<project_directory>` is your desired name to clone the repository into.
Then you can `cd` into this new directory.

#### 2. Install the requirements for the backend server and run it

The project's backend is written in **Python** with the usage of **Flask** web framework and
an **SQLite** database. To install these, make sure that you have Python3.6 or higher and pip installed
on your machine. It is also recommended to create a new virtual environment for
the project, so make sure to execute these:

`cd backend` \
`python3 -m venv venv` \
`source ./venv/bin/activate` 

After the virtual environment was created, you can install requirements for the backend part:

`(venv) pip3 install -r requirements.txt`

Finally, to run the server, execute this:

`(venv) python3 main.py`

If everything is correct, the **backend Flask server** should run on ip address 
`0.0.0.0` and be accessible from the port `5000`.

#### 3. Install Expo app on your mobile device

To install Expo on Android, go to Google Play Store and find it there. Then tap install and wait.

#### 4. Install the requirements for the frontend client and run it

Make sure that you have `npm` installed on your machine.

**Node.js**

Go to frontend folder, then install Expo CLI:
`sudo npm install --unsave-perm -g expo-cli`

Then install all packages:

`npm install`

`npm start`

Using android expo app scan QR and application will build.
