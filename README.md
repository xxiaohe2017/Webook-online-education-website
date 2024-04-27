

<img src="app/images/banner.svg" style="width:100%">


# Webook - Single Page Education Website

(This project is an adapted version of the original [one](https://github.com/SM8UTI/Webook-online-education-website).) 


<br/>

## Overview
In this project, we aim to build and deploy a single-page web application (named “Webook”) that enables users to explore the marketing information of online courses provided by Webook. This application presents users with an HTML-based interface with a RESTful web service on the backend to submit their enquiries.

<br/>
The main components of the website are: 

- Course introduction, Lecturer introduction, FAQs, Contact messages and other functions, where:
    - Contact messages contains the most important feature of this application

<br/>
Specially, this application integrates several AWS cloud services including:

- **AWS Amplify**: providing continuous deployment and hosting of static web resources (HTML, CSS, JavaScript, images, etc.)
- **API Gateway** and **Lambda**: building a public backend API that receives data and triggers a Lambda function to store the data into the database
- **DynamoDB**: providing a persistent layer where data can be stored by the Lambda function
- **IAM**: providing secure access for the Lambda function to store data into DynamoDB
- **CloudWatch**: monitoring application performance and resource use
  
<br/>

## 🖥️ Challenge Description : 



<br/>
This challenge is absolutely made for those who love to code websites and make the website look modern, sleek, user-friendly, responsive n many more. You have to create a single page of the Online Education Website using any preferred language you want. You have to only code the front-end part, no back-end code is needed.

Ex. Navbar, Header section, Services/Features, Courses, FAQ, Contact, Footer, etc.

- Single Page Online Education Website
- Only Front-End Code (Any Language)
- Make it responsive on all devices

<br/>

## 🌍  


<br/>


## 📁 File Strutcture : 

```
|   index.html // Index Html File 
|   README.md  // Readme File 
|   Webook.fig // Figma File 
|
\---app // All Files or Images 
    +---images
    |   |   ba1.png
    |   |   causal.png
    |   |   menu-alt.png
    |   |   menu-x.png
    |   |   preloader.gif
    |   |
    |   \---logo
    |           Favicon.svg
    |           logo.svg
    |
    +---js
    |       script.js // Main Javascript file 
    |
    \---scss
        |   style.css // Main Style CSS File
        |   style.css.map
        |   style.scss // Main Style SCSS File 
        |
        +---components // Here present all of components 
        |       _about.scss
        |       _banner.scss
        |       _classes.scss
        |       _contact.scss
        |       _courses.scss
        |       _expert.scss
        |       _faq.scss
        |       _features.scss
        |       _footer.scss
        |       _header.scss
        |       _index.scss
        |       _preloadder.scss
        |       _subscribe.scss
        |
        +---global // Here present all Default Html code and Color Codes 
        |       _boilerplate.scss
        |       _colors.scss    // All Colours file 
        |       _fonts.scss     // Font File 
        |       _images.scss    // Images url File 
        |       _index.scss
        |       _typography.scss
        |
        \---util
                _breakpoints.scss // Media Query Function 
                _functions.scss   // Some function 
                _index.scss
```

<br/>


## 💻 Screenshot : 

![Screenshot](screenshot-pc.png)


<br/>

### ©️ Copyright : 

```
Boost Software License - Version 1.0 - August 17th, 2003

Permission is hereby granted, free of charge, to any person or organization
obtaining a copy of the software and accompanying documentation covered by
this license (the "Software") to use, reproduce, display, distribute,
execute, and transmit the Software, and to prepare derivative works of the
Software, and to permit third-parties to whom the Software is furnished to
do so, all subject to the following:

The copyright notices in the Software and this entire statement, including
the above license grant, this restriction and the following disclaimer,
must be included in all copies of the Software, in whole or in part, and
all derivative works of the Software, unless such copies or derivative
works are solely in the form of machine-executable object code generated by
a source language processor.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT
SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE
FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```

