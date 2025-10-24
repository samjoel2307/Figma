# Ex09 Event Registration Web Application
## Date:20-10-2025

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
page 1

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="label"><div class="text"></div></div>
  </body>
</html>


globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


style.css

.label {
  width: 1px;
  height: 58px;
}

.label .text {
  position: fixed;
  top: 270px;
  left: 479px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}


page 2

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="images" src="img/images-1-1.png" />
      <div class="TOP-ACTORS-AND">•TOP ACTORS&nbsp;&nbsp;AND CELEBRITIES&nbsp;&nbsp;ARE COMING</div>
      <div class="frame"><div class="text-wrapper">CELENZA(2026)</div></div>
      <div class="div">EVENT DETAILS</div>
      <p class="p">•EVENT WILL CONDUCT FOR ABOUT 4 DAYS</p>
      <p class="text-wrapper-2">•ONLY THOSE WHO FILL THE FORM WILL BE ALOWDED</p>
      <div class="text-wrapper-3">•BUS FACILITIES ARE AVAILABLE</div>
      <p class="text-wrapper-4">•OTHER COLLEGE STUDENTS SHOULD PAY RS2000 ON ENTRY</p>
      <p class="ALL-THE-STUDENTS-ARE">•ALL THE STUDENTS&nbsp;&nbsp;ARE WELCOMES TO ENJOW THE EVENT</p>
      <p class="DANCE-SONGS-DJ-WILL">•DANCE,SONGS,DJ&nbsp;&nbsp;WILL HAPPEN ,EVERYONE IS WELCOMED FOR THIS EVENT</p>
    </div>
  </body>
</html>


globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .images {
  position: absolute;
  top: 110px;
  left: 0;
  width: 440px;
  height: 839px;
  object-fit: cover;
}

.iphone-pro-max .TOP-ACTORS-AND {
  position: absolute;
  top: 328px;
  left: 18px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .frame {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 117px;
  display: flex;
  background-color: #c81010;
}

.iphone-pro-max .text-wrapper {
  margin-top: 30px;
  width: 390px;
  height: 58px;
  margin-left: 25px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 177px;
  left: 25px;
  font-family: "Inter-BoldItalic", Helvetica;
  font-weight: 700;
  font-style: italic;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .p {
  position: absolute;
  top: 299px;
  left: 18px;
  width: 385px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 348px;
  left: 18px;
  width: 426px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 387px;
  left: 18px;
  width: 252px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 411px;
  left: 18px;
  width: 426px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .ALL-THE-STUDENTS-ARE {
  position: absolute;
  top: 459px;
  left: 18px;
  width: 413px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .DANCE-SONGS-DJ-WILL {
  position: absolute;
  top: 503px;
  left: 18px;
  width: 426px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}


page 3

index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper">FILL THE FORM</div>
      <div class="div"></div>
      <img class="img" src="img/image.svg" />
      <div class="text-wrapper-2">NAME:</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">REGISTER NUMBER:</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">PHONE NUMBER:</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-5">EMAIL ID:</div>
      <div class="rectangle-5"></div>
    </div>
  </body>
</html>


globals.css


@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


style.css

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 280px;
  left: 105px;
  width: 264px;
  height: 35px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 99px;
  background-color: #000000;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 33px;
  left: 71px;
  width: 331px;
  opacity: 0.4;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 99px;
  left: -57px;
  width: 618px;
  height: 876px;
  background-color: #c80909;
}

.iphone-pro-max .img {
  position: absolute;
  top: 80px;
  left: -55px;
  width: 576px;
  height: 1013px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 135px;
  left: 22px;
  width: 158px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 177px;
  left: 29px;
  width: 291px;
  height: 43px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 234px;
  left: 23px;
  width: 256px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #010101;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 291px;
  left: 29px;
  width: 291px;
  height: 41px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 380px;
  left: 39px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 443px;
  left: 29px;
  width: 291px;
  height: 45px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 537px;
  left: 40px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 597px;
  left: 37px;
  width: 283px;
  height: 45px;
  background-color: #d9d9d9;
}



```


## OUTPUT:

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
