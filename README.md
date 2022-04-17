# Node.js TDD Server

* [GitHub Repo Server](https://github.com/WebDevelopUa/react-tdd-server)
* [GitHub Repo Client](https://github.com/WebDevelopUa/react-tdd-client)
* [http://localhost:3000](http://localhost:3000)
* [ENDPOINT 1](http://localhost:3000/api/1.0/users) - `{"content":[],"page":0,"size":10,"totalPages":0}`
* [ENDPOINT 1+](http://localhost:3030/api/1.0/users)
* [proxy] - `  "proxy": "http://127.0.0.1:3030" `
-------------------

### Node: 16.13.0

Run project:

```shell
npm i 
npm run start
npm run test
npm run lint
````

# Server App

## npm run start

```shell
run start:dev --scripts-prepend-node-path=auto

2022-04-16T13:17:38.088Z [INFO   ] : app is running. version: 1.3.0
[nodemon] 2.0.15
[nodemon] to restart at any time, enter `rs`

rs
[nodemon] starting `node index index.js`
2022-04-16T13:18:39.910Z [INFO   ] : app is running. version: 1.3.0

```

[http://localhost:3000](http://localhost:3000)


------------

# Client APP

## SignUp Submit

### Moesif CORS extension or https://mybrowseraddon.com/access-control-allow-origin.html

##### password: "Password must have at least 1 uppercase, 1 lowercase letter and 1 number"

```shell

http://localhost:3030/api/1.0/users
POST
200 OK
127.0.0.1:3030
strict-origin-when-cross-origin

```

```shell

POST /api/1.0/users HTTP/1.1
Accept: application/json, text/plain, */*
Accept-Encoding: gzip, deflate, br
Accept-Language: ru-RU,ru;q=0.9,en-US;q=0.8,en;q=0.7,uk;q=0.6
Connection: keep-alive
Content-Length: 101
Content-Type: application/json
Cookie: 
Host: localhost:3030
Origin: http://localhost:3030
Referer: http://localhost:3030/
Sec-Fetch-Dest: empty
Sec-Fetch-Mode: cors
Sec-Fetch-Site: same-origin
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/100.0.4896.127 Safari/537.36
sec-ch-ua: " Not A;Brand";v="99", "Chromium";v="100", "Google Chrome";v="100"
sec-ch-ua-mobile: ?0
sec-ch-ua-platform: "Windows"

```

```shell

{ username: "email@email.com", email: "email@email.com", password: "nuE@6jjKxsHj7wP" }
email: "remail@email.com"
password: "nuE@6jjKxsHj7wP"
username: "rogok18706@drlatvia.com"

```

```shell

{ message: "User created" }

```

## Updates DB:

[database.sqlite](database.sqlite)
