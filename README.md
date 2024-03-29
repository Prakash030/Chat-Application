# Text-A-Lot

> A Realtime Chat Application

A simple realtime chat apoplication made using [React JS](https://reactjs.org/docs/getting-started.html), a JavaScript library to make awesome UI by Facebook, [Node JS](https://nodejs.org/en/docs), [Express JS](https://expressjs.com/en/api.html) and [MongoDB](https://docs.mongodb.com/).

This application uses [React JS](https://reactjs.org/docs/getting-started.html) component oriented UI creation paradigm. All components are written in [JSX](https://reactjs.org/docs/jsx-in-depth.html) and ES6 style and are
combined to get a single build for production purpose using [Webpack 5](https://webpack.js.org/concepts/).


Back end is implemented using [Node JS](https://nodejs.org/en/docs), [Express JS](https://expressjs.com/en/api.html) and [MongoDB](https://docs.mongodb.com/). [Atlas](https://www.mongodb.com/cloud/atlas), the _Cloud_ version of [MongoDB](https://docs.mongodb.com/) is used. Real time communication is done using [Socket.io](https://www.npmjs.com/package/socket.io).

This is a _responsive web application_ for viewing in both Mobile and Desktop.

```
This is still a work in progress
If you find any bugs you can report it to me.
Pull requests are always welcome. For major changes, 
please open an issue first to discuss what you would like to change.

```


## Features

- Latest features of JavaScript i.e. ES6, ES7, ES8 is used
- [React JS Hooks](https://reactjs.org/docs/hooks-intro.html) are used with Functional components
- ES8 `async/await` is used

<br/>

<ul>
 <li> This is Simple Chat Application </li>
 <li> It is a Full Stack Application </li>
</ul>

- All the user details, group chats and conversations are stored in the [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

<ul>
 <li>Login/Signup as well as Logout feature is added </li>
 <li>Guest User Login added</li>
 <li>Error will be shown if the credentials are not correct</li>
</ul>

- Real time communication & notification is supported using <a href="https://www.npmjs.com/package/socket.io">Socket.io</a>

<ul>
 <li> Realtime One on One chats and group chats </li>
 <li> Functionality and features like Search for chats, create a group, add or remove partricipants. </li>   
 <li> typing... animation. </li>
 <li> Online / Offline status are shown . </li>
 <li> Read / Unread status of conversation is supported
 <li> All the conversation are stored in the database i.e. <i>persistant</i>
</ul>


## Tech Stack

MongoDB, Express, React, Node, Socket.IO, Chakra-UI



```

### Env Variables

Create a .env file in the root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = <yourMongoDbUri>
JWT_SECRET = <yourSecret>
```



