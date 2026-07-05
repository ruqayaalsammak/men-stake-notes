# men-stake-notes
| CRUD Action | RESTful Action | HTTP Method | Definition |
| ----------- | -------------- | ----------- | ------------------------ |
|  | `new` | `GET` | Show a form to create a new item |
| Create | `create` | `POST` | Add a new item to the database |
| Read | `index` | `GET` | Show all items |
| Read | `show` | `GET` | Show one specific item |
| | `edit` | `GET` | Show a form to edit an existing item |
| Update | `update` | `PUT` | Save changes to an existing item |
| Delete | `delete` | `DELETE` | Remove an item from the database |

## SETUP
- create a directory
- create server file'touch server.js'
- initialize a nide priject with 'npm init -y'
- install express 'nom i express'

## Write Server Bolireplate
server.js
```js
// Import Express
const express = require('express')

//Cactually use express
const app = express()

app.listen(3000, function(){
    console.log('Listening on port 3000❤')
})
```

