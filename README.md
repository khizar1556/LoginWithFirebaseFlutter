# loginform

A new Flutter project.

## Getting Started

## Flutter Social Logins with Firebase google, facebook , email and number

## Architecture
![1_mJpDhhE-fOLnPzQhpKin4w](https://user-images.githubusercontent.com/93259715/182357251-af1b7529-8fae-4265-828b-67f99d825166.png)

This is a Social Login Project, in this you can signin through facebook, google & email

Stating with Login Screen
![Screenshot_20220802-155541](https://user-images.githubusercontent.com/93259715/183829454-732bb0f5-18e4-4220-8334-4b9298e5d037.png)

if you have an account then you will signin through login button otherwise you need to navigate signup page

![Capture](https://user-images.githubusercontent.com/93259715/183829518-9d41b6ca-537e-4d78-872c-7603796636a7.PNG)

after click on signup button you recieve 6 digit code on your Mobile Number after this you will be signin through Mobile

![Capture1](https://user-images.githubusercontent.com/93259715/183829554-48c40c91-d370-49c6-8ccd-582706bf9142.PNG)

& if you have already sign in then it will directly navigate to the Home Screen (Shared Prefrences pending)

///----///

## Forget Password (change password & Email OTP )

![Capture2](https://user-images.githubusercontent.com/93259715/183829678-848dae42-4d36-4bf2-8a91-6b1c95da28db.PNG)


in this TextField enter your email address and click on the Reset password Button, on this click you recieve a link in your email address,
open the link and change your new Password


![Screenshot_20220802-155513](https://user-images.githubusercontent.com/93259715/182361625-7a8d26a8-1122-484a-9799-7277977cab18.png)


when you press the (OTP Send), a new TextField added and OTP verification code send on your email address then put the condition on Confirm Button As your choice

![Capture4](https://user-images.githubusercontent.com/93259715/183829719-56909e1b-632d-4fb0-99ad-2c319fd376fd.PNG)


after clicking on facebook button Facebook Login Page will open

![Capture6](https://user-images.githubusercontent.com/93259715/183829766-605d425a-1682-4d8e-b9de-b8c31965eae2.PNG)


after clicking on Google Button new tab is open like this

![Capture7](https://user-images.githubusercontent.com/93259715/183829827-0076f838-5f6c-4a18-8e8d-939e4b80c130.PNG)


at the last this is our main screen this in we show the user profile,name and email address with the logout button


![Capture8](https://user-images.githubusercontent.com/93259715/183829870-dc0ad4f3-07b0-4c48-839e-09f24bd608f1.PNG)





## Steps
create signin & signup screens
in this screen create facebook & google signin button
set the authentication through firestore database (email & pass)
set the authentication through google & facebook signin
create function for email OTP,OTP validation, change password through email link
at the last store the user information input for signing form in firestore database
