This is a weather app built using OpenWeatherMap's free API.

The App file turned into a mess of components. Looking back at it now, it's a real mess. 

This project really sunk in how splitting components into different files can really make it easier to navigate and develop in.

Another thing to note, it is not at all responsive to mobile design. I was focused on consuming and exposing API data more than anything while building this project.

I also ended up switching out the weather API that I was using three times.

Since I'm updating this Readme 3 months later I can't remember the reasons why I swapped the API out everytime. However, I do remember being frustrated because I ran out of API requests accidentally while working on the frontend.

On the server side I ended up with a solution where after I had gotten the request, I would cache the data on my server side and 
give a cached copy of the data to my frontend to avoid excessive API requests.

I also used Postman quite a bit for learning how to request the different APIs correctly, seeing what data was returned etc.

Overview:<br> 
    - Weather App<br> 
    - Features<br>
    &ensp;- A 5-Day forecast.<br>
    &ensp;- A 12-hour forecast.<br>
    &ensp;- Current weather conditions.<br>
    &ensp;- Settings tab.<br>
        &ensp;&ensp;- Change your default location and measurement system (Imperial vs Metric)<br>
    &ensp;- A Cities tab.<br>
        &ensp; &ensp;- Search for a city to save.<br>
        &ensp; &ensp;- Displays the current conditions of the saved cities<br>

Built using:<br> 
    &ensp;- MongoDB, Express, React, Node, Axios and Typescript.<br> 
      &ensp;&ensp;- React, Axios, Typescript, localStorage and sessionStorage for state persistance<br> 
      &ensp;&ensp;- Node, OpenWeatherMap's API, Express and Typescript for the backend. <br> 

Operation:<br> 
    &ensp;1. Terminal pointed towards server root folder.<br> 
       &ensp;&ensp;-  `npm run start`.<br> 
    &ensp;2. New terminal pointed towards client root folder.<br> 
       &ensp;&ensp;-  `npm run start`<br> 
    &ensp;3. localhost:3000 should open automatically.<br> 

Project_notes:<br> 
    &ensp;- I keep a running log while building the project.<br> 
    &ensp;- Typically I start out with an idea.<br> 
    &ensp;- Tasks that need to be completed are outlined.<br> 
      &ensp;&ensp;- When a task is completed, I move it into a separate completed tasks section.<br>