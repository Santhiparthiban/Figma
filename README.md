# Ex09 Event Registration Web Application
## Date:17.10.2025

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
Home page 
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="logo" src="img/logo-1.png" />
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-19-at-17-59-10-dc196b38-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">MUSIC FEST</div>
      <div class="text"></div>
      <div class="div"></div>
      <img class="text-on-a-path" src="img/image.svg" />
      <div class="text-wrapper-2">LOGIN</div>
      <img class="img" src="img/text-on-a-path.svg" />
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">REGISTER</div>
      <img class="whatsapp-image-2" src="img/whatsapp-image-2025-10-19-at-18-29-29-7ca9ec34-1.png" />
    </div>
  </body>
</html>

style-home.css
.android-medium {
  background-color: #f9c2ed;
  width: 100%;
  min-width: 700px;
  min-height: 946px;
  position: relative;
}

.android-medium .logo {
  position: absolute;
  top: 38px;
  left: 0;
  width: 700px;
  height: 101px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.android-medium .whatsapp-image {
  position: absolute;
  top: 197px;
  left: 232px;
  width: 236px;
  height: 231px;
  aspect-ratio: 1.02;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 456px;
  left: 158px;
  width: 371px;
  height: 87px;
  background-color: #ff7ce2;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 486px;
  left: 246px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text {
  position: absolute;
  top: 486px;
  left: 178px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 556px;
  left: 246px;
  width: 188px;
  height: 57px;
  background-color: #d9d9d9;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 426px;
  left: 296px;
  width: 181px;
  height: 56px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 567px;
  left: 290px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  position: absolute;
  top: 426px;
  left: 289px;
  width: 188px;
  height: 41px;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 626px;
  left: 253px;
  width: 181px;
  height: 57px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 635px;
  left: 266px;
  width: 168px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .whatsapp-image-2 {
  position: absolute;
  top: 696px;
  left: 115px;
  width: 470px;
  height: 250px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

Event page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="text"></div>
      <p class="MAIN-STAGE-EVENT">
        <span class="text-wrapper">MAIN STAGE EVENT:<br /></span>
        <span class="span"
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.&nbsp;&nbsp;LIVE BAND
          PERFORMANCE<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. DJ NIGHT<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.
          BATTLE OF BANDS<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. ACOUSTIC
          EVENING<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5. OPEN MIC NIGHT<br
        /></span>
        <span class="text-wrapper-2"><br /></span>
        <span class="text-wrapper">SPECIAL SEGMENTS:<br /></span>
        <span class="span"
          >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1. CELEBRITY PERFORMANCE<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          2. TRIBUTE NIGHT<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3. GENRE
          HOUR<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4. SILENT DISCO</span
        >
      </p>
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-19-at-18-52-45-2b4691e3-1.png" />
    </div>
  </body>
</html>

style-event.css
.android-medium {
  background-color: #ff82d5;
  width: 100%;
  min-width: 700px;
  min-height: 958px;
  position: relative;
}

.android-medium .text {
  position: absolute;
  top: 107px;
  left: 182px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .MAIN-STAGE-EVENT {
  position: absolute;
  top: 24px;
  left: 77px;
  width: 528px;
  -webkit-text-stroke: 1px #9b299f;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper {
  font-weight: 800;
  color: #0f1d20;
}

.android-medium .span {
  font-family: "Inter-Italic", Helvetica;
  font-style: italic;
  color: #0f1d20;
  font-size: 36px;
}

.android-medium .text-wrapper-2 {
  font-family: "Inter-Italic", Helvetica;
  font-style: italic;
  color: #1b3237;
  font-size: 36px;
}

.android-medium .whatsapp-image {
  position: absolute;
  top: 663px;
  left: 244px;
  width: 444px;
  height: 295px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

Register page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <p class="REGISTRATION-FORM">
        <span class="text-wrapper"> REGISTRATION FORM<br /> </span> <span class="span">Fill The Details</span>
      </p>
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-19-at-19-05-17-2730191b-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="div">AGE</div>
      <img class="img" src="img/rectangle-9.svg" />
      <div class="text-wrapper-2">MOBILE NO</div>
      <img class="rectangle-2" src="img/rectangle-11.svg" />
      <div class="text-wrapper-3">REGISTER</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">GENDER</div>
      <img class="rectangle-4" src="img/rectangle-8.svg" />
      <div class="text-wrapper-5">DEPARTMENT</div>
      <img class="rectangle-5" src="img/rectangle-7.svg" />
      <div class="text-wrapper-6">REGISTER NUMBER</div>
      <img class="text-on-a-path-2" src="img/text-on-a-path-4.svg" />
      <img class="text-on-a-path-3" src="img/image.svg" />
      <div class="rectangle-6"></div>
      <div class="text-wrapper-7">NAME</div>
      <img class="text-on-a-path-4" src="img/text-on-a-path-2.svg" />
      <img class="text-on-a-path-5" src="img/text-on-a-path-3.svg" />
      <img class="text-on-a-path-6" src="img/text-on-a-path-5.svg" />
      <div class="rectangle-7"></div>
      <img class="rectangle-8" src="img/rectangle-14.svg" />
      <div class="text-wrapper-8">EVENTS TO REGISTER</div>
      <div class="text-wrapper-9">EMAIL ID</div>
    </div>
  </body>
</html>

style-register.css
.android-medium {
  background-color: #f655d3;
  overflow: hidden;
  width: 100%;
  min-width: 700px;
  min-height: 977px;
  position: relative;
}

.android-medium .REGISTRATION-FORM {
  position: absolute;
  top: 31px;
  left: 22px;
  width: 655px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 400;
  color: transparent;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .text-wrapper {
  font-weight: 800;
  color: #740f0f;
}

.android-medium .span {
  font-family: "Inter-Regular", Helvetica;
  color: #111010;
  font-size: 32px;
}

.android-medium .whatsapp-image {
  position: absolute;
  top: 329px;
  left: 380px;
  width: 320px;
  height: 648px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: -28px;
  left: -1415px;
  width: 304px;
  height: 87px;
}

.android-medium .rectangle {
  position: absolute;
  top: 291px;
  left: 22px;
  width: 304px;
  height: 74px;
  background-color: #d9d9d9;
}

.android-medium .div {
  position: absolute;
  top: 311px;
  left: 85px;
  width: 134px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .img {
  position: absolute;
  top: 639px;
  left: 22px;
  width: 304px;
  height: 68px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 653px;
  left: 25px;
  width: 178px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 867px;
  left: 35px;
  width: 233px;
  height: 77px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 882px;
  left: 53px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 389px;
  left: 22px;
  width: 304px;
  height: 59px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 401px;
  left: 85px;
  transform: rotate(0.07deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 561px;
  left: 22px;
  width: 304px;
  height: 63px;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 569px;
  left: 25px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 473px;
  left: 22px;
  width: 304px;
  height: 64px;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 489px;
  left: 25px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-on-a-path-2 {
  position: absolute;
  top: 522px;
  left: -1415px;
  width: 316px;
  height: 63px;
}

.android-medium .text-on-a-path-3 {
  position: absolute;
  top: 6px;
  left: -1415px;
  width: 304px;
  height: 67px;
}

.android-medium .rectangle-6 {
  position: absolute;
  top: 202px;
  left: 22px;
  width: 304px;
  height: 64px;
  background-color: #d9d9d9;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 214px;
  left: 85px;
  width: 98px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-on-a-path-4 {
  position: absolute;
  top: 517px;
  left: -1415px;
  width: 304px;
  height: 68px;
}

.android-medium .text-on-a-path-5 {
  position: absolute;
  top: 524px;
  left: -1419px;
  width: 308px;
  height: 61px;
}

.android-medium .text-on-a-path-6 {
  position: absolute;
  top: 524px;
  left: -1415px;
  width: 304px;
  height: 61px;
}

.android-medium .rectangle-7 {
  position: absolute;
  top: 717px;
  left: 22px;
  width: 315px;
  height: 55px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-8 {
  position: absolute;
  top: 785px;
  left: 18px;
  width: 350px;
  height: 61px;
}

.android-medium .text-wrapper-8 {
  position: absolute;
  top: 796px;
  left: 24px;
  transform: rotate(-0.33deg);
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-9 {
  position: absolute;
  top: 722px;
  left: 30px;
  font-family: "Inter-SemiBold", Helvetica;
  font-weight: 600;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

contact page
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="logo" src="img/logo-2.png" />
      <div class="text-wrapper">THANK YOU</div>
      <p class="div">we are eagerly waiting for your participation in the music event</p>
      <img class="text-on-a-path" src="img/text-on-a-path.png" />
      <div class="text-wrapper-2">CONTACT US</div>
      <div class="email-saveetha-gmail"><br />Email: saveetha@gmail.com</div>
      <div class="text-wrapper-3">9845674787</div>
      <div class="text-wrapper-4">9756474875</div>
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-19-at-19-46-14-ee72b03b-1.png" />
    </div>
  </body>
</html>

style-contact.css
.android-medium {
background-color: #fe0cc2;
overflow: hidden;
width: 100%;
min-width: 700px;
min-height: 977px;
position: relative;
}

.android-medium.logo {
position: absolute;
top: 29px;
left: 0;
width: 700px;
height: 106px;
aspect-ratio: 6.65;
object-fit: cover;
}

.android-medium.text-wrapper {
position: absolute;
top: 198px;
left: 191px;
font-family: "Inter-ExtraBold", Helvetica;
font-weight: 800;
color: #000000;
font-size: 48px;
letter-spacing: 0;
line-height: normal;
}

.android-medium div {
position: absolute;
top: 280px;
left: 76px;
width: 671px;
font-family: "Inter-Italic", Helvetica;
font-weight: 400;
font-style: italic;
color: #000000;
font-size: 36px;
letter-spacing: 0;
line-height: normal;
}

.android-medium.text-on-a-path {
position: absolute;
top: 420px;
left: -1933px;
width: 482px;
height: 483px;
object-fit: cover;
}

.android-medium.text-wrapper-2 {
position: absolute;
top: 403px;
left: 31px;
width: 319px;
font-family: "Inter-ExtraBold", Helvetica;
font-weight: 800;
color: #000000;
font-size: 48px;
letter-spacing: 0;
line-height: normal;
white-space: nowrap;
}

android-medium email-saveetha-gmail {
position: absolute;
top: 431px;
left: 31px;
font-family: "Inter-SemiBold", Helvetica;
font-weight: 600;
color: #000000;
font-size: 40px;
letter-spacing: 0;
line-height: normal;
}

.android-medium text-wrapper-3 {
position: absolute;
top: 550px;
left: 33px;
font-family: "Inter-SemiBold", Helvetica;
font-weight: 600;
color: #eeeeee;
font-size: 40px;
letter-spacing: 0;
line-height: normal;
white-space: nоwгар;
}

.android-medium.text-wrapper-4 {
position: absolute;
top: 598px;
left: 33px;
font-family: "Inter-SemiBold", Helvetica;
font-weight: 600;
color: #000000;
font-size: 40px;
letter-spacing: 0;
line-height: normal;
white-space: nowrap;
}

.android-medium.whatsapp-image {
position: absolute;
top: 646px;
left: 303px;
width: 395px;
height: 331px;
aspect-ratio: 1;
object-fit: cover;
}
```

## OUTPUT:
![alt text](<Screenshot (44).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
