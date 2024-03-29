# Amazona ECommerce Website

![amazona](https://github.com/bouba-jaz/shopping-website/blob/43ae05c37d76f7b35fa163bf44096208bf477acc/test/template/images/amazona.jpg)


## Run Locally

### 1. Clone repo

```
$ git clone https://github.com/bouba-jaz/shopping-website.git
$ cd amazona
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/amazona
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin
