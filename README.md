# Blueprint of a better UX for train ticket booking in India
This blueprint describes the improvements that can be made on the [irctc.co.in](https://www.irctc.co.in) website to enable a seamless and reliable ticket booking experience.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Blueprint of a better UX for train ticket booking in India](#blueprint-of-a-better-ux-for-train-ticket-booking-in-india)
  - [1. Changes to the login system](#1-changes-to-the-login-system)
  - [2. One-Click booking experience](#2-one-click-booking-experience)
  - [3. About `credScore`](#3-about-credscore)
  - [4. One-Click approach to report errors](#4-one-click-approach-to-report-errors)
  - [5. Annual open challenges](#5-annual-open-challenges)
  - [6. Community of users](#6-community-of-users)
  - [7. LIVE nudge](#7-live-nudge)
- [Extra](#extra)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## 1. Changes to the login system
 The first and foremost challenge with with current login system is that *the average Indian user* has to remember both the username and the password *(Mind you the passwords should be 8-15 characters long containing one uppercase and lowercase letter along with a number to pass the threshold required for acceptable level of security.!!)*

 The solution to this problem would be to remove the login with username and password and replace it with **login with mobile number and OTP only.** 

 Once logged into the website, users should not be logged out unncessarily. Logout should happen only on the expiry of the token or manual logout by the user.


## 2. One-Click booking experience
Provide the ability to save the journey details of the user and the ability to book a ticket at the click of a single button. This feature will be very useful at the time of tatkal ticket booking.
After clicking the book now button each user will face a `waitTime` that will be inversely proportional to the user's `credScore`

This will also eliminate the need for autofill applications.


## 3. About `credScore` 
`credScore` (short for credibility score) is a score that is calculated based on user's interaction with the website.
The purpose of `credScore` is to ascertain if a user is a genuine or an imposter. The higher the score, the lower will be the waiting time before booking the ticket.

The `credScore` can be a function of the following factors (but not limited to).

    * Whose login is used for booking the ticket ?
    * In whose name tickets are being booked ?
    * What is the frequency in which the tickets are booked ?
    * What is the variance in the source and destination when booking the tickets ?

The users will be clearly explained about the scoring process and all the factors that influence their `credScore`.

## 4. One-Click approach to report errors

Users should be provided with a One-click option to report their problems as well while booking. These reports should be duly addressed based on their priority and fixed.


## 5. Annual open challenges
Periodic open challenges should be conducted to identify and fix the potential vulnerabilities in the website/app.


## 6. Community of users
A discussion forum can be created as a part of its website, that enables users to share their travel experiences with others. This will enable users to get community answers for their queries and problems.

## 7. LIVE nudge
LIVE nudge is a notification system that informs users about the real time or trending events with the booking system.

Example 1. LIVE nudge can inform the user to choose an alternate payment method when a particular payment method is experiencing high rates of failure.

Example 2: LIVE nudge can also inform the user about a potential server overload (which then impacts the probability of booking a successful ticket) while booking during festive season.


# Extra
If you wish to contribute to this repository, please [create a new issue from here](https://github.com/yuva-dev/project_alpha/issues/new)
