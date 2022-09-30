# Mern stack implementation

## Step 1

`sudo apt update`

`sudo apt upgrade`

`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`

`sudo apt-get install -y nodejs`

`node -v`

`npm -v`

![version](./Images/node%20version.PNG)


`mkdir Todo`

`ls`

`npm init`

![json](./Images/ls%20Json.PNG)


## Step 2

`npm install express`

`touch index.js`

![index](./Images/index-js.PNG)

`npm install dotenv`

`vim index.js`

`node index.js`

![5000](./Images/port-5000.PNG)

`http://<PublicIP-or-PublicDNS>:5000`

![welcome-express](./Images/welcome-to-express.PNG)

`mkdir routes`

`touch api.js`

`vim api.js`

## Models

`npm install mongoose`

`mkdir models`

`cd models`

`touch todo.js`

`vim todo.js`

`vim api.js`

## Mongodb database

`touch .env`

`vi .env`

`DB = 'mongodb+srv://<username>:<password>@<network-address>/<dbname>?retryWrites=true&w=majority'`

`vim index.js`

`node index.js`

![database](./Images/database-connect.PNG)

`http://<PublicIP-or-PublicDNS>:5000/api/todos`

![post](./Images/Post1.PNG)


![get](./Images/Get1.PNG)

#### Optional Delete request

![delete](./Images/Delete-request.PNG)


## Frontend creation

` npx create-react-app client`

`npm install concurrently --save-dev`

`npm install nodemon --save-dev`

`cd client`

`vi package.json`

`npm run dev`

![run-dev](./Images/localhost3000.PNG)

`cd client`

`cd src`

`mkdir components`

`cd components`

`touch Input.js ListTodo.js Todo.js`

`vi Input.js`

`cd ..`

`cd ..`

`npm install axios`

![axios](./Images/install%20Axios.PNG)


## Frontend creation (contd)

`cd src/components`

`vi ListTodo.js`

`cd ..`

`vi App.js`

`vi App.css`

`vim index.css`

`cd ../..`

`npm run dev`

![run-dev](./Images/Run-build.PNG)

![mytodos](./Images/mytodos.PNG)

