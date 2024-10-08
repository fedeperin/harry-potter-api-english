# Harry Potter API
> [!IMPORTANT]  
> [PotterAPI](https://github.com/fedeperin/potterapi) is a new version of this API, available en multiple languages and updated with new information. I recommend using that one instead of this one.

A Harry Potter Rest API that returns information about spells, characters, books and information itself. I used node.js with the only package json-server for creating it. This Harry Potter API is hosted at Render<br>

* GitHub repository of json-server: https://github.com/typicode/json-server <br>
* Node js webpage: https://nodejs.org/ <br>
* Render's webpage: https://render.com/ <br>

For installing the dependencies, execute by terminal with node js installed  ``npm install json-server``

## How to use
Here is a JavaScript example of fetching the entire API. Just change tha value of the const ``urlToFetch`` for changing the URL being fetched. ``urlToFetch`` value can be changed by an enpoint of this (or another) API for feching different APIs <br>
```javascript
const urlToFetch = "https://harry-potter-api-en.onrender.com/db"

fetch(urlToFetch)
	.then((res) => res.json())
	.then((data) => {
		// It brings all data at the API and it shows it at the console
		console.log(data)
	})
	.catch((e) => console.log(e));
```
Or visit the main page of this API (that comes by default with json-server): https://harry-potter-api-en.onrender.com/

## Endpoints
* https://harry-potter-api-en.onrender.com/db Brings all the data at the API
* https://harry-potter-api-en.onrender.com/spells It bring the spells at the API
* https://harry-potter-api-en.onrender.com/info It brings the information of the API
* https://harry-potter-api-en.onrender.com/characters It brings the information about the characters at the API
* https://harry-potter-api-en.onrender.com/books It only bring the book part of the API <br>

<br>
To access an specific element at the API, just secify the ID number of that element at the end of the route <br><br>


#### Examples: 
* With the route https://harry-potter-api-en.onrender.com/books/3 you only access the book at the API with ID 3<br>
* With the route https://harry-potter-api-en.onrender.com/spells/10 you only access the spell at the API with ID 10 <br><br>
---
GitHub Repository of the Spanish version of this same API: https://github.com/fedeperin/harry-potter-api/
