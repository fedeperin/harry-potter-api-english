# Harry Potter API
A Harry Potter rest API that brings information about spells, characters, books and information itself. I used Node js with json-server for creating it and I host it on Heroku <br>

- GitHub repository of json-server: https://github.com/typicode/json-server <br>
- Download Node.js: https://nodejs.org/ <br>
- Heroku webpage: https://heroku.com/ <br>

If you want to download the code, execute by terminal with Node js installed  ``npm i json-server``

## How to use
If your'e using JavaScript you can copy and paste the following code <br>
```javascript
fetch("https://fedeperin-harry-potter-api-en.herokuapp.com/db")
	.then((res) => res.json())
	.then((data) => {
		// It brings all data and it shows it by console
		console.log(data)
	})
	.catch((e) => console.log(e));
```
Or visit the principal page of the API (that comes by default with json-server): https://fedeperin-harry-potter-api-en.herokuapp.com/

## Endpoints
- https://fedeperin-harry-potter-api-en.herokuapp.com/db Brings all the API
- https://fedeperin-harry-potter-api-en.herokuapp.com/spells It bring the spells at the API
- https://fedeperin-harry-potter-api-en.herokuapp.com/info It brings the information of the API
- https://fedeperin-harry-potter-api-en.herokuapp.com/characters It brings the information about the characters at the API
- https://fedeperin-harry-potter-api-en.herokuapp.com/books It only bring the book part of the API <br>

<br>
Or try some routes at https://harry-potter-api-page.netlify.app/ <br>
<br>
If you want to access an specific part of the API, just secify the ID number at the end of the route<br><br>
Examples: <br>
- With the route https://fedeperin-harry-potter-api-en.herokuapp.com/books/3 you only access the book with ID 3<br>
- With the route https://fedeperin-harry-potter-api-en.herokuapp.com/spells/10 you only access the book with ID 10 <br><br>

Spanish Version: https://github.com/fedeperin/harry-potter-api/
