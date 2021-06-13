# Harry Potter API
A Harry Potter Rest API that returns information about spells, characters, books and information itself. I used Node js with the only package json-server for creating it. The API is hosted at heroku <br>

- GitHub repository of json-server: https://github.com/typicode/json-server <br>
- Install Node.js: https://nodejs.org/ <br>
- Hosting webpage: https://heroku.com/ <br>

If you want to download the code, execute by terminal with Node js installed  ``npm i json-server``

## How to use
If you are using JavaScript you can copy and paste the following code to use this API <br>
```javascript
fetch("https://fedeperin-harry-potter-api-en.herokuapp.com/db")
	.then((res) => res.json())
	.then((data) => {
		// It brings all data at the API and it shows it at the console
		console.log(data)
	})
	.catch((e) => console.log(e));
```
Or visit the main page of this API (that comes by default with json-server): https://fedeperin-harry-potter-api-en.herokuapp.com/

## Endpoints
- https://fedeperin-harry-potter-api-en.herokuapp.com/db Brings all the data at the API
- https://fedeperin-harry-potter-api-en.herokuapp.com/spells It bring the spells at the API
- https://fedeperin-harry-potter-api-en.herokuapp.com/info It brings the information of the API
- https://fedeperin-harry-potter-api-en.herokuapp.com/characters It brings the information about the characters at the API
- https://fedeperin-harry-potter-api-en.herokuapp.com/books It only bring the book part of the API <br>

<br>
Try some routes at the page https://harry-potter-api-page.netlify.app/ <br>
<br>
If you want to access an specific element at the API, just secify the ID number at the end of the endpoint route <br><br>


#### Examples: 
* With the route https://fedeperin-harry-potter-api-en.herokuapp.com/books/3 you only access the book at the API with ID 3<br>
* With the route https://fedeperin-harry-potter-api-en.herokuapp.com/spells/10 you only access the spell at the API with ID 10 <br><br>

Spanish version of this API: https://github.com/fedeperin/harry-potter-api/
