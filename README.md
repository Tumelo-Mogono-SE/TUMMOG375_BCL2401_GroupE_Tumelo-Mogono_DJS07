# DJS07 - Build a Meme Generator
# Overview

In this project we build a meme generator application using React. We followed along the Scrimba lessons. This projects aim is to improve our understanding of React, including setting up a REact app, structuring our application and managing the state within our app.

After cloning  we had to run `npm install` to install dependencies.

# Project Process

* After getting the starter code which contains the initial files and the css for styling from the codespace repository. I had to run npm install to get all the dependencies.
* After that I created a component folder which I created the Header component file, which inside the file I imported the React library and then created functional component which will be exported which returns a header element which contains the image, h2 element and an h4 element.
* Then inside the App.jsx file I imported the Header component and rendered it inside the App function.
* I then created another component file called Meme.jsx, which inside it I imported the React library and then created function called Meme which inside it I returned the main element which inside it there is div for the form which inside it there is a inputs and a button and then there is another div which inside it there is an img element and two h2 element which will render the value from the inputs.
* I then initialized the state for the meme with default values and also the top text and bottom text using React.useState.
* I then also initialized the state for all the memes as an empty array.
* I then fetched the memes from an API when the component mounts using React.useEffect, which inside it from the parsed JSON response I set the allMemes state with the fetched data.
* I then created a function which will get a random meme image which inside it I created a randomNumber between 0 and the length of memes in the array. Then got the url based on the index number which I get from the randomNumber variable. Then I update the state using setMeme and assign the url to the randomImage property.
* I then created a function that handles changes in the input fields, which inside the function I destructure the event target to get the name and value variable which I use to update the setMeme state by copying the previous state abd update the state with the new values.
* I then had the meme component imported in the App.jsx file and rendered the meme component .
* I then made changes to the css file to center the meme image so that the top text and bottom text appear properly.


# Challenges

For this project I didn't have alot challenges since it was more of a follow along, but I still need to learn more about hooks and usage of states for lifecycles. I also need to read more of the React documentation.

# Feedback

This was a great introduction project to dynamic web applications. I look forward to learning more about the in's and out's of React.
