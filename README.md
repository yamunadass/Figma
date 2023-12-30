# Ex09 Event Registration Web Application
## Date:

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
home page

// Login
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word
---
// Register
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word

 <div style="width: 100%; height: 100%; background: #3B8279; flex-direction: column; justify-content: flex-start; align-items: flex-end; display: inline-flex">
    <img style="width: 360px; height: 69px" src="https://via.placeholder.com/360x69" />
    <img style="width: 360px; height: 647px" src="https://via.placeholder.com/360x647" />
    <img style="width: 204px; height: 204px" src="https://via.placeholder.com/204x204" />
    <div style="width: 250px; height: 66px; background: #FCFFFF"></div>
    <div style="width: 220px; height: 29px; text-align: center; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Login</div>
    <div style="width: 250px; height: 64px; background: #FFFCFC"></div>
    <div style="width: 205px; height: 34px; text-align: center; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Register</div>
</div>

Events page 

// List of Events
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word
---
//  1 .  Bharatanatyam  <br/> <br/> 2 . Freestyle <br/><br/>3 . Folk <br/><br/>4 . Semi - Classical <br/><br/>5 . Hip pop <br/><br/>6 . Salsa <br/><br/>7 . Ballet dance <br/><br/>8 . Kathakali
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word

 <div style="width: 100%; height: 100%; position: relative; background: white">
    <img style="width: 356px; height: 716px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/356x716" />
    <img style="width: 360px; height: 69px; left: -4px; top: 0px; position: absolute" src="https://via.placeholder.com/360x69" />
    <div style="width: 247px; height: 71px; left: 55px; top: 110px; position: absolute; text-align: center; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">List of Events</div>
    <div style="width: 286px; height: 495px; left: 48px; top: 189px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word"> 1 .  Bharatanatyam  <br/> <br/> 2 . Freestyle <br/><br/>3 . Folk <br/><br/>4 . Semi - Classical <br/><br/>5 . Hip pop <br/><br/>6 . Salsa <br/><br/>7 . Ballet dance <br/><br/>8 . Kathakali</div>
</div>


Registration page 

// Event  registration form  
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word
---
// Name :<br/>
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word
---
// Department :
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word
---
// E -mail :
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word
---
// Mobile no :
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word

 <div style="width: 100%; height: 100%; position: relative; background: white">
    <img style="width: 360px; height: 716px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/360x716" />
    <div style="width: 306px; height: 22px; left: 27px; top: 100px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Event  registration form  </div>
    <img style="width: 360px; height: 86px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/360x86" />
    <div style="width: 234px; height: 38px; left: 32px; top: 171px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Name :<br/></div>
    <div style="width: 246px; height: 55px; left: 57px; top: 209px; position: absolute; background: rgba(67.38, 224.61, 215.18, 0.54)"></div>
    <div style="width: 238px; height: 37px; left: 32px; top: 286px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Department :</div>
    <div style="width: 246px; height: 51px; left: 57px; top: 337px; position: absolute; background: rgba(67.38, 224.61, 215.18, 0.54)"></div>
    <div style="width: 149px; height: 48px; left: 32px; top: 419px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">E -mail :</div>
    <div style="width: 246px; height: 46px; left: 57px; top: 465px; position: absolute; background: rgba(67.38, 224.61, 215.18, 0.54)"></div>
    <div style="width: 246px; height: 49px; left: 57px; top: 598px; position: absolute; background: rgba(67.38, 224.61, 215.18, 0.54)"></div>
    <div style="width: 213px; height: 43px; left: 32px; top: 533px; position: absolute; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Mobile no :</div>
</div>

Contact Us page 

// THANK YOU <br/><br/>
color: #F43737;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word
---
// we are eagerly waiting for your participation in dance events.
color: #3B37F4;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word
---
// CONTACT US <br/>www.saveetha.ac.in<br/>8939902737
color: black;
 font-size: 24px;
 font-family: Inter;
 font-weight: 800;
 word-wrap: break-word

 <div style="width: 100%; height: 100%; position: relative; background: white">
    <img style="width: 391px; height: 716px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/391x716" />
    <img style="width: 391px; height: 83px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/391x83" />
    <img style="width: 204px; height: 204px; left: 94px; top: 124px; position: absolute" src="https://via.placeholder.com/204x204" />
    <div style="width: 309px; height: 178px; left: 39px; top: 369px; position: absolute; text-align: center"><span style="color: #F43737; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">THANK YOU <br/><br/></span><span style="color: #3B37F4; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">we are eagerly waiting for your participation in dance events.</span></div>
    <div style="width: 315px; height: 127px; left: 41px; top: 549px; position: absolute; text-align: center; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">CONTACT US <br/>www.saveetha.ac.in<br/>8939902737</div>
</div>
```
## OUTPUT:
![image](https://github.com/yamunadass/Figma/assets/138971172/327d766a-ac8c-4db0-8bf5-e56e0a9ac062)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
