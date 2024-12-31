# Ex09 Event Registration Web Application
## Date:24-12-2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

```
home page.html


<html>
    <head>
        <style>
            .android-compact-1,
.android-compact-1 * {
  box-sizing: border-box;
}
.android-compact-1 {
  background: #f7ff67;
  height: 917px;
  position: relative;
  overflow: hidden;
}
.rectangle-1 {
  background: #ff2a2a;
  width: 251px;
  height: 68px;
  position: absolute;
  left: 81px;
  top: 669px;
}
.rectangle-2 {
  background: #ff2a2a;
  width: 251px;
  height: 68px;
  position: absolute;
  left: 81px;
  top: 559px;
}
.register {
  color: #ffffff;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 36px;
  font-weight: 400;
  position: absolute;
  left: 121px;
  top: 681px;
}
.login {
  color: #ffffff;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 36px;
  font-weight: 400;
  position: absolute;
  left: 155px;
  top: 571px;
}
.sec-1 {
  border-radius: 440px;
  width: 257px;
  height: 256px;
  position: absolute;
  left: 72px;
  top: 203px;
  object-fit: cover;
}
.web-logo-01-1 {
  width: 412px;
  height: 58px;
  position: absolute;
  left: 0px;
  top: 80px;
  object-fit: cover;
}

        </style>
    </head>
    <body>
        <div class="android-compact-1">
            <div class="rectangle-1"></div>
            <div class="rectangle-2"></div>
            <div class="register">REGISTER</div>
            <div class="login">LOGIN</div>
            <img class="sec-1" src="sec-10.png" />
            <img class="web-logo-01-1" src="web-logo-01-10.png" />
        </div>          
    </body>
</html>
```
```
page 2.html


<html>
    <head>
        <style>
            .android-compact-2,
.android-compact-2 * {
  box-sizing: border-box;
}
.android-compact-2 {
  background: #d0ff84;
  height: 57.3125rem;
  position: relative;
  overflow: hidden;
}
.android-compact-2__sports-1 {
  width: 22.6875rem;
  height: 12.25rem;
  position: absolute;
  left: 1.5rem;
  top: 41.875rem;
  object-fit: cover;
}
.android-compact-2__sports-day-events {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 4.5625rem;
  top: 6.1875rem;
  width: 21.1875rem;
  height: 3.4375rem;
}
.android-compact-2__cricket {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 3.1875rem;
  top: 11.9375rem;
}
.android-compact-2__football {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 3.3125rem;
  top: 16.1875rem;
}
.android-compact-2__vollyball {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 3.1875rem;
  top: 20.4375rem;
}
.android-compact-2___4-x-100-relay {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 3.1875rem;
  top: 24.75rem;
}
.android-compact-2___100-mts {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 3.1875rem;
  top: 29rem;
}
.android-compact-2___200-mts {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 3.1875rem;
  top: 33.3125rem;
}
.android-compact-2___500-mts {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 3.1875rem;
  top: 37.625rem;
}

        </style>
    </head>
    <body>
        <div class="android-compact-2">
            <img class="android-compact-2__sports-1" src="sports-10.png" />
            <div class="android-compact-2__sports-day-events">Sports Day Events</div>
            <div class="android-compact-2__cricket">. Cricket</div>
            <div class="android-compact-2__football">. Football</div>
            <div class="android-compact-2__vollyball">. Vollyball</div>
            <div class="android-compact-2___4-x-100-relay">. 4 X 100 Relay</div>
            <div class="android-compact-2___100-mts">. 100 mts</div>
            <div class="android-compact-2___200-mts">. 200 mts</div>
            <div class="android-compact-2___500-mts">. 500 mts</div>
        </div>
    </body>
</html>
```
```
page 3.html


<html>
    <head>
        <style>
            .android-compact-3,
.android-compact-3 * {
  box-sizing: border-box;
}
.android-compact-3 {
  background: #d7edec;
  height: 57.3125rem;
  position: relative;
  overflow: hidden;
}
.android-compact-3__events-registration-form {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 3.5rem;
  top: 5.8125rem;
}
.android-compact-3__rectangle-3 {
  background: #ffffff;
  width: 18.75rem;
  height: 2.5rem;
  position: absolute;
  left: 2.0625rem;
  top: 13.875rem;
}
.android-compact-3__full-name {
  color: #000000;
  text-align: left;
  font-family: "Gupter-Regular", sans-serif;
  font-size: 2rem;
  font-weight: 400;
  position: absolute;
  left: 2.375rem;
  top: 13.8125rem;
}
.android-compact-3__rectangle-7 {
  width: 18.75rem;
  height: 2.5rem;
  position: absolute;
  left: 2.0625rem;
  top: 28.8125rem;
  overflow: visible;
}
.android-compact-3__rectangle-8 {
  width: 18.75rem;
  height: 2.5rem;
  position: absolute;
  left: 2.0625rem;
  top: 32.5625rem;
  overflow: visible;
}
.android-compact-3__email {
  color: #000000;
  text-align: left;
  font-family: "Gupter-Regular", sans-serif;
  font-size: 2rem;
  font-weight: 400;
  position: absolute;
  left: 2.375rem;
  top: 32.5625rem;
}
.android-compact-3__rectangle-10 {
  width: 18.75rem;
  height: 2.5rem;
  position: absolute;
  left: 2.0625rem;
  top: 40.0625rem;
  overflow: visible;
}
.android-compact-3__rectangle-9 {
  width: 18.75rem;
  height: 2.5rem;
  position: absolute;
  left: 2.0625rem;
  top: 36.3125rem;
  overflow: visible;
}
.android-compact-3__rectangle-4 {
  background: #ffffff;
  width: 18.75rem;
  height: 2.5rem;
  position: absolute;
  left: 2.0625rem;
  top: 17.625rem;
}
.android-compact-3__rectangle-5 {
  background: #ffffff;
  width: 18.75rem;
  height: 2.5rem;
  position: absolute;
  left: 2.0625rem;
  top: 21.375rem;
}
.android-compact-3__rectangle-6 {
  background: #ffffff;
  width: 18.75rem;
  height: 2.5rem;
  position: absolute;
  left: 2.0625rem;
  top: 25.125rem;
}
.android-compact-3__gender {
  color: #000000;
  text-align: left;
  font-family: "Gupter-Regular", sans-serif;
  font-size: 2rem;
  font-weight: 400;
  position: absolute;
  left: 2.375rem;
  top: 25.3125rem;
}
.android-compact-3__register-number {
  color: #000000;
  text-align: left;
  font-family: "Gupter-Regular", sans-serif;
  font-size: 2rem;
  font-weight: 400;
  position: absolute;
  left: 2.375rem;
  top: 17.5625rem;
}
.android-compact-3__age {
  color: #000000;
  text-align: left;
  font-family: "Gupter-Regular", sans-serif;
  font-size: 2rem;
  font-weight: 400;
  position: absolute;
  left: 2.375rem;
  top: 21.3125rem;
}
.android-compact-3__department {
  color: #000000;
  text-align: left;
  font-family: "Gupter-Regular", sans-serif;
  font-size: 2rem;
  font-weight: 400;
  position: absolute;
  left: 2.375rem;
  top: 28.8125rem;
}
.android-compact-3__events-to-register {
  color: #000000;
  text-align: left;
  font-family: "Gupter-Regular", sans-serif;
  font-size: 2rem;
  font-weight: 400;
  position: absolute;
  left: 2.375rem;
  top: 40.125rem;
}
.android-compact-3__mobile-number {
  color: #000000;
  text-align: left;
  font-family: "Gupter-Regular", sans-serif;
  font-size: 2rem;
  font-weight: 400;
  position: absolute;
  left: 2.375rem;
  top: 36.5rem;
}
.android-compact-3__rectangle-32 {
  background: #ff2a2a;
  width: 15.6875rem;
  height: 4.25rem;
  position: absolute;
  left: 5rem;
  top: 46.1875rem;
}
.android-compact-3__register {
  color: #ffffff;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 2.25rem;
  font-weight: 400;
  position: absolute;
  left: 7.5rem;
  top: 46.9375rem;
}

        </style>
    </head>
    <body>
        <div class="android-compact-3">
            <div class="android-compact-3__events-registration-form">
              Events Registration
              <br />
              Form
            </div>
            <div class="android-compact-3__rectangle-3"></div>
            <div class="android-compact-3__full-name">Full Name</div>
            <img class="android-compact-3__rectangle-7" src="rectangle-70.svg" />
            <img class="android-compact-3__rectangle-8" src="rectangle-80.svg" />
            <div class="android-compact-3__email">Email</div>
            <img class="android-compact-3__rectangle-10" src="rectangle-100.svg" />
            <img class="android-compact-3__rectangle-9" src="rectangle-90.svg" />
            <div class="android-compact-3__rectangle-4"></div>
            <div class="android-compact-3__rectangle-5"></div>
            <div class="android-compact-3__rectangle-6"></div>
            <div class="android-compact-3__gender">Gender</div>
            <div class="android-compact-3__register-number">Register Number</div>
            <div class="android-compact-3__age">Age</div>
            <div class="android-compact-3__department">Department</div>
            <div class="android-compact-3__events-to-register">Events to Register</div>
            <div class="android-compact-3__mobile-number">Mobile Number</div>
            <div class="android-compact-3__rectangle-32"></div>
            <div class="android-compact-3__register">REGISTER</div>
          </div>          
    </body>
</html>
```
```
page4.html

<html>
    <head>
        <style>
            .android-compact-4,
.android-compact-4 * {
  box-sizing: border-box;
}
.android-compact-4 {
  background: #afa1fe;
  height: 57.3125rem;
  position: relative;
  overflow: hidden;
}
.android-compact-4__we-are-all-eagerly-waiting-for-your-participation-in-the-sports-events {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 1.5rem;
  font-weight: 400;
  position: absolute;
  left: 4.0625rem;
  top: 27.25rem;
  width: 25.6875rem;
  height: 6.125rem;
}
.android-compact-4__web-logo-01-2 {
  width: 25.75rem;
  height: 3.625rem;
  position: absolute;
  left: 0rem;
  top: 5.8125rem;
  object-fit: cover;
}
.android-compact-4__thank-you {
  color: #000000;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 3rem;
  font-weight: 400;
  position: absolute;
  left: 5.4375rem;
  top: 17.8125rem;
}
.android-compact-4__rectangle-11 {
  background: #ff2b2b;
  opacity: 0.5;
  width: 25.75rem;
  height: 9.0625rem;
  position: absolute;
  left: 0rem;
  top: 43.6875rem;
}
.android-compact-4__contact-us-saveethaengineeringcollege-gmail-com-phone-no-78945-78945 {
  color: #ffffff;
  text-align: left;
  font-family: "Itim-Regular", sans-serif;
  font-size: 1.25rem;
  font-weight: 400;
  position: absolute;
  left: 0rem;
  top: 44.375rem;
}

        </style>
    </head>
    <body>
        <div class="android-compact-4">
            <div
              class="android-compact-4__we-are-all-eagerly-waiting-for-your-participation-in-the-sports-events"
            >
              we are all eagerly waiting
              <br />
              for your participation in the
              <br />
              sports events
            </div>
            <img class="android-compact-4__web-logo-01-2" src="web-logo-01-20.png" />
            <div class="android-compact-4__thank-you">Thank You</div>
            <div class="android-compact-4__rectangle-11"></div>
            <div
              class="android-compact-4__contact-us-saveethaengineeringcollege-gmail-com-phone-no-78945-78945"
            >
              contact us :
              <br />
              saveethaengineeringcollege@gmail.com
              <br />
              <br />
              phone no :
              <br />
              78945 78945
            </div>
        </div>          
    </body>
</html>
```

## OUTPUT:


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
