# State less Chat app written in node.js and socket.io

## Libraries used
<ul>
  <li>node.js / npm</li>
  <li>socket.io</li>
  <li>express</li>
  <li>node-uuid</li>
  <li>underscore</li>
  <li>ejs</li>
</ul>

# Functionality
<ul>
  <li>People will able to join the chat server after entering their names</li>
  <li>Usernames are unique - if a username is taken, a new suggestion is generated</li>
  <li>User agent and geo location are both detected</li>
  <li>People can setup a private room. Room names are unique. One person can create on room and join one room</li>
  <li>Users have to join a room to chat, except for the whisper (one-to-one chat - preivate meassage) feature.</li>
  <li>Users can leave a room and/or disconnect from the server anytime</li>
  <li><strong>New:</strong> People joining the room will see the past 10 messages (chat history).</li>
  <li><strong>New:</strong> People will see an 'is typing' message when someone is typing a message.</li>
</ul>

## Setup and configuration

Make sure that you update <strong>server.js</strong>:

To install <code>npm install && bower install</code> and to launch run <code>npm start</code>.
