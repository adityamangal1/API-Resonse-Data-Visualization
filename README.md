# API Resons Data Visualization

Visualization code added to the Tests for a request will render in the Visualize tab for the response body, alongside the Pretty, Raw, and Preview options. Postman provides a programmable way to visually represent your request responses. API consumers can get more from API data by taking advantage of prebuilt charts and graphs. Data itself can seem very bland. It can be difficult to really capture the impact a set of data has just by looking at straight numbers. But when you introduce a visual concept to present your data, thoughts click, your mind gets creative, and you see insights that you would’ve never seen just by looking at plain numbers. Postman Visualizer is your API visualization companion


![b6e4691585cedceb3d2c956d87e5bb01](https://user-images.githubusercontent.com/68494604/127006001-4ea66a7d-ea93-40c9-a3b5-ed4aa079105e.gif)

## What it does
I have used two different APIs one was covid cases data retrieval API and another one was a star Wars character data API. I'm new to the postman and really enjoying with experiment with the postman and its amazing features.

- Easy
No coding is required to consume rich visualization from easy-to-share collections.

- Save Time
Choose from prebuilt visualizations from the Postman API Network templates.

- Customizable
Tweak charts and visualizations to your liking with a little CSS and JavaScript knowledge.

## How we built it

To visualize your response data, add code to the Pre-request or Tests script for the request. The pm. **pm.visualizer.set()** method will apply your visualizer code to the data and present it in the Visualize tab when the request runs. The template is made with HTML, CSS, and JavaScript.

- Adding visualizer code
The **pm.visualizer.set()** method accepts a Handlebars template string as its first parameter. The second parameter should be the data you want to use the template to display. Handlebars can do this with the **{{#each}}** tag. The **template** variable is the template string created earlier. The second argument passed is an object defined as the **response** property—this is the variable that the template expects in the **{{#each response}}** loop. The value assigned to the response property is the response JSON data from the request parsed as an object.

## What we learned
Postman Visualizer is a great way to see data and make more meaningful sense of it—but it supports so much more than just seeing charts and graphs for data. Postman Visualizer can also be used for testing and creating micro web apps, serving as yet another way Postman empowers you from the beginning to the end of your software development lifecycle.

## What's next for Postman Visualization from APIs
Yet to learn and experiment with more APIs with this amazing postman visualizers feature. 

<p align="center">
  <img alt="Sloan, the sloth mascot" width="250px" src="https://user-images.githubusercontent.com/68494604/120436157-39627380-c39c-11eb-89cf-58089fb1032d.gif">
   <br>
</p>


