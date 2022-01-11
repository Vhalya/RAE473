---
date: 2021-11-15T10:58:08-04:00
description: "Create a MERN website"
featured_image: "/images/MERN-logo.png"
tags: ["mern"]
title: "Learning the MERN stack "
---

I have been developping a website based on the MERN stack for a study course at Riga Technical University. This project was a way for me to get into web development and Javascript.
 This website has been deployed to production and its available to visit at https://fishing-spot.netlify.app/posts. The main concept behind the website was to allow users to create posts about anything and interact with other posts. It then became an app to post about fishing spots (I'm a fisherman). 
 
 It features Google authentication as well as normal authentication ( made possible thanks to json web tokens). There is also a fully functionnal pagination system and search algorythm, many features such as google maps integration are gonna be comming, I am currently still working on it but it hasn't been deployed yet. 
  
_Front end / Client side_

The front end was built using React and material-ui, the client uses redux to allow dynamic updates of the pages. Learning the redux architecture was really hard at first since it had no previous background in web development. Front end has been deployed on Netlify 

_Back end / Server side_ 

The back end works with a MongoDB database, mongoose, express and nodejs, it was deployed on heroku. 

![MERN stack workflow](/images/MERN-stack.png "MERN stack workflow")
