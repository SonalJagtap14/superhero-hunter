<h1 align="center" id="title">SuperHero Hunter app using MARVEL API</h1>

<p align="center"><img src="https://socialify.git.ci/SonalJagtap14/superhero-hunter/image?font=Source%20Code%20Pro&amp;language=1&amp;name=1&amp;owner=1&amp;pattern=Circuit%20Board&amp;stargazers=1&amp;theme=Dark" alt="project-image"></p>

<p id="description">This code powers a Superhero Hunter web application that leverages the Marvel API to retrieve and showcase Marvel character data. It comprises several functions that allow users to browse all the characters on the homepage search for specific characters via the Marvel API based on their input in the search bar and add characters to their favorites list. The list of search results is displayed with an option to add the characters to the favorites list which is stored locally on the user's browser. Additionally the code includes a function to toggle the visibility of the character list on the homepage. This code empowers the web application with the ability to explore and view information on Marvel characters.</p>

<h2>🚀 Demo</h2>

[https://sonaljagtap14.github.io/superhero-hunter.github.io/](https://sonaljagtap14.github.io/superhero-hunter.github.io/)

<h2>Project Screenshots:</h2>

<img src="https://github.com/SonalJagtap14/superhero-hunter/blob/main/Screenshot%202023-03-25%20160825.png?raw=true" alt="project-screenshot" width="500" height="400/">

<img src="https://github.com/SonalJagtap14/superhero-hunter/blob/main/Screenshot%202023-03-25%20160910.png?raw=true" alt="project-screenshot" width="500" height="400/">

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Responsive
*   Searchbar
*   Functional
*   Favourites

<h2>🛠️ Installation Steps:</h2>

<p>1. Generate API key from Marve;</p>

<p>2. Use the api fetch function</p>

```
function getCharacters(){     const char_url = `http://gateway.marvel.com/v1/public/characters?&ts=1&apikey=26cd8e7d36c0122137914a00f6b87862&hash=f7fb73edbdb6b9355a7c4c7a6a7d68b9&limit=100`     getCharApi(char_url) } getCharacters()
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   HTML5
*   CSS3
*   Vanilla JavaScript
*   Marvel API
