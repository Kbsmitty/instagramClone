## Phoenix Framework Final Project
## Project Video:
* https://cdn.discordapp.com/attachments/1170601029952352267/1183530674997690408/webDemo.mp4?ex=6588abd5&is=657636d5&hm=17d0321ab02ec34ed11a51d588d5b3dc4b718008606f31f5d2625758eead7297&

## Project SlideShow:
* https://docs.google.com/presentation/d/1BHY1KS9BfiNifZYEc7xZvHrAFc13diw-i57SZkNOaRs/edit?usp=sharing

Project Overview
## Contributors: 
Kyler Smith - https://github.com/Kbsmitty/instagramClone

Lucas Rowsey - https://github.com/lrowsey/PhoenixFramework

## Project Description

The goal of our project was to create a social media demo, inspired mostly by twitter and instagram, utilizing the Phoenix Framework with the Elixir programming language. We aimed to showcase the ease and efficiency of implementing Phoenix Framework for real-time applications, specifically leveraging LiveView to enhance the development process. 


Our project is hosted on GitHub. You can find the repositories at 
https://github.com/Kbsmitty/instagramClone 
https://github.com/lrowsey/PhoenixFramework

## Project Objectives 

Our primary objective was to develop a demonstrative social media application similar to Twitter. The focus was on leveraging the capabilities of the Phoenix Framework to streamline the development process, making it more efficient and less labor-intensive. 

## Contribution
Kyler - I made the instagram clone with Lucas's help. I implemented most of the features on the Instagram clone website including the login functoin, post function, and the function to add a photo to a post. Most of the work was in claburation and we helped as needed. 

## Technology Summary

## Phoenix Framework

Phoenix Framework is a powerful web framework for Elixir that enables the development of real-time applications. The framework is known for its efficiency and scalability, making it an ideal choice for projects requiring real-time features. 

## LiveView

LiveView, a key feature of Phoenix Framework, allows developers to create interactive, real-time user experiences without the need for JavaScript. It simplifies the development of dynamic, responsive web applications. 

When a browser makes an http request so a server that is hosting the single page app, html is returned then the browser requests the javascript and css that are in the html fire. If the single page app doesn’t support server side rendering then the browser may have to request more data before the app is rendered in the browser. 

When you make an http request to a Phoenix live view URL, what is sent back from the serve is the pages fully rendered html which provides a fast page load similar to a multi page app. Unlike a multi page app or a single page app, things like data state (what is happening to the data), client logic (functions for events), and view functions (the html) are held on the server instead of the browse through a websocket connection and are all called the LiveView Proccess. This allows for Phoenix LiveView to be less complex than something like a single page app. 

## Demo Application

The demo application simulates a social media platform where users can post updates, follow other users, and engage in real-time conversations. Leveraging LiveView, we aimed to provide a smooth and dynamic user experience. 

## How to Run the Project

To run the project locally, follow these steps: 
* Clone the GitHub repository: ‘git clone https://github.com//Kbsmitty/instagramClone.git’
* Navigate to the project directory: ‘cd instagramClone’
* Install dependencies: ‘mix deps.get’
* Set up the database: ‘mix ecto.setup’
* Start the Phoenix server: ‘mix phx.server’

*	Visit ‘http://localhost:4000’

## Resources
Phoenix Framework Official Website
Phoenix Framework Documentation
Phoenix Framework GitHub Repository

## Kylers Takeaways

I think the Phoenix Framework is very useful and has a lot of great tools such as Liveview and project creation. I thought it was super cool to learn about Elixir and all the different technologies that go into Phoenix. A downside to that, was trouble shooting syntax, as well as implementing Elixir and the Phoenix Framework into the project. Trying to host a website that uses the framework is also a bit of a nightmare and it would help if they had a bit more documentation for it, especially with the newest release of Phoenix. Otherwise, I could see myself implementing Phoenix or something similar in the future to make my website more user friendly and versatile. 
