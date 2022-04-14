### Build a Blockchain and Cryptocurrency | Full-Stack Edition

This takes that course's best content, and adds a ton of additional material:
Some of the main course highlights:

- Code a full-on backend with test-driven development.
- Write a full test suite for the backend.
- Build a Blockchain in the object-oriented programming style.
- Create a full frontend React.js web application.
- Deploy the application to production (with multiple servers).
- Create an API around the Blockchain.
- Create a real-time connected peer-to-peer server with a pub/sub implementation.
- Implement a proof-of-work algorithm.
- Sign Transactions with cryptography and digital signature.
- Create a Transaction Pool for a real-time list of incoming data.
- Include transactions in core blocks of the chain.

### Software Installations:

1. A Code Editor and Command Line Application

For a code editor, I recommend Visual Studio Code: https://code.visualstudio.com/. I also recommend configuring it to open via the command line:

CMD-SHIFT-P

Enter “Shell Command”, and choose “Install ‘code’ command in path.

Then you can run $ code /folder to open folders in VSCode from your shell.

For the command line application, on MacOS or Linux, I recommend the native Terminal application (or Iterm2).



WINDOWS USERS: I absolutely recommend downloading Git Bash. This course was recorded using a bash environment. Using Git Bash will make doing this course a smooth process.



2. Node.js.

If you don’t already have Node.js installed, here is the download page: https://nodejs.org/en/download/. Once you have Node.js installed, run the following commands on the command line

$ node -v

See a value like `v8.8.1` or higher

$ npm -v

See a value like `v5.4.2` or higher



3. Postman. This app allows developers to send custom HTTP Requests. Here is the link to install Postman: https://www.getpostman.com/docs/postman/launching_postman/installation_and_updates



4. (Optional) Redis. There will come a point where you may opt to use Redis for the networking part of the course. There will be instructions again later in the course. But, while you're setting up, you may want to try installing Redis now!

That being said, installing Redis is OPTIONAL. There's a Redis alternative if you don't want to spend a lot of time setting up locally (especially since it's particularly tricky on Windows).

Once, you have Redis, the key command to run is:

$ redis-server

If you can run the above, you’re all good! Feel free to get a head start on downloading Redis

MacOS: https://medium.com/@petehouston/install-and-config-redis-on-mac-os-x-via-homebrew-eb8df9a4f298

Linux: https://redis.io/topics/quickstart

Windows: https://github.com/ServiceStack/redis-windows