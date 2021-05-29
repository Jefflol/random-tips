# Random Tips and Code Snippets
This is a collection of random tips and code snippets.

&nbsp;
### `console.table()`
Prints out the objects and their selected data in table form, in console.
```js
async function getUsers() {
    let response = await fetch('https://jsonplaceholder.typicode.com/users')
    let data = await response.json()
    
    console.table(data, ['name', 'email'])
}

getUsers()
```
![console-table](./images/console-table.jpg)
