You need:
- NodeJs
- MongoDB Free Web Cluster

Setup Database
Sign up for MongoDB free database cluster: https://www.mongodb.com/

Create .env file
Create a .env file to store your credentials. Example below:

MONGODB_URI=mongodb+srv://<username>:<password>@clusterName.xxxxxxx.mongodb.net/blog
JWT_SECRET=MySecretBlog

Installation
To install and run this project - install dependencies using npm and then start your server:

cd domains/Blog
npm install
npm run dev