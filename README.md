# service-web-store

**service-web-store** contains the backend service that will store and serve the database, and provide endpoints to access the data.

I made a branch

### 1. Navigate to our newly forked directory

Open a terminal in vscode, by clicking Terminal > New Terminal.

In the terminal type:

> cd service-web-store

:information_source: _| change directory to a directory named | service-web-store |_

### 2. Install all NPM

> npm install<br>

:information_source: _| node package manager | install |_

The references for both of these packages are added to package.json, and their source bits are stored in the corresponding folders inside of the node_modules subdirectory.

### 3. Use the stack script to start the Docker environment with the DB

> sudo sh stack.sh up<br>

:information_source: _| super user do | run a script | named stack.sh | pass in the variable "up" |_
