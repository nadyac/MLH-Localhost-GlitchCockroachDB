Startrek Quotes with CockroachDB
================================
### Homepage
#### Quotes are queried from CockroachDB and displayed every few seconds.  
<img src="https://i.imgur.com/TiGjKH8.png"></img>

### Project on Glitch
#### Project can be found on Glitch at <a href = "https://checker-aries.glitch.me">https://checker-aries.glitch.me/</a>
<img src="https://i.imgur.com/IEd1qdV.png"></img>

### Troubleshooting 'BRB! Connecting to CockroachDB' 
#### This happens occassionally when the project has been running for a while. It may go to sleep. Simply reload the page and wait a few minutes while the project wakes up and restarts the DB process. 
If the app is really unresponsive, you may also go into the Glitch Console and type 'sh cockroach.sh' to run the cockroachDB process manually. Hit <enter> to execute the DB process. You should see a bunch of output on the Glitch console.

#### If the app is still not responding and the following error appears 'EADDRINUSE :::3000' in the Glitch Log, then you have no choice but to kill the server.js process in the Glitch Console.
<img src="https://i.imgur.com/nzQsauv.png" /></a>

#### To solve the 'EADDRINUSE :::3000' error...
* Go to the Glitch Console
* Type *'ps -ax'* to see a list of all running processes.
* Find the process *'node server.js'* and note the PID.
* Finally, kill that process by running *'kill [PID]'* 
<img src="https://i.imgur.com/0u8U6qS.png" title="Kill process on Glitch" /></a>
  
#### Don't worry about restarting the nodoe server.js as Glitch will do this automatically. You may return to your project on Glitch IDE and check the log to ensure you have no issues. 

---
Welcome to Glitch
=================

Click `Show` in the header to see your app live. Updates to your code will instantly deploy and update live.

**Glitch** is the friendly community where you'll build the app of your dreams. Glitch lets you instantly create, remix, edit, and host an app, bot or site, and you can invite collaborators or helpers to simultaneously edit code with you.

Find out more [about Glitch](https://glitch.com/about).


Your Project
------------

On the front-end,
- edit `public/client.js`, `public/style.css` and `views/index.html`
- drag in `assets`, like images or music, to add them to your project

On the back-end,
- your app starts at `server.js`
- add frameworks and packages in `package.json`
- safely store app secrets in `.env` (nobody can see this but you and people you invite)


Made by [Fog Creek](https://fogcreek.com/)
-------------------

\ ゜o゜)ノ
