# Wallery - Ripple-NFT

## Technologies

We have chosen the technologies Node.js and React. These are two javascript libraries and are often used in web development.

![image](https://user-images.githubusercontent.com/52482896/121243883-86fc4600-c89e-11eb-9817-088d23d27688.png)

---

We will use Node.js for developing the backend. We chose Node.js because Ripple provides the Node.js api for the XRP ledger.
Also, the scalability of the project is important to us, and Node.js is very well suited for that.

![image](https://user-images.githubusercontent.com/52482896/121243923-924f7180-c89e-11eb-8a97-d27c1a927b90.png)

---

We will use React in our project for the development of the frontend. We have chosen React because it is constantly being developed further and because it offers good performance.

![image](https://user-images.githubusercontent.com/52482896/121244011-ad21e600-c89e-11eb-94bc-fbbc1826852c.png)

---

As database we will use mongoDB. This is a NoSQL database and is therefore more performant than a SQL database. Also Node.js offers an easy development with mongoDB.



## AWS Node.js Stack

Amazon AWS offers the solution &quot;Node.js Stack&quot;. With this solution, we can run our Node.js application on it. It also offers &quot;Amazon DynamoDB&quot;. On this instance you can run a NoSQL database. In our case this is MongoDB.

This stack also includes the &quot;Elastic Load Balancer&quot;. This service distributes the requests to the different instances. This way you can achieve a higher performance.

In order to always get the best one for the web application, Auto-Scaling offers a solution. This service automatically increases or decreases the performance of the Node.js instance per need.

The estimated cost is 0.04$ - 0.06$ per hour. This results in a monthly price between $29.76 and $44.64.

![image](https://user-images.githubusercontent.com/52482896/121244155-d773a380-c89e-11eb-8f24-8a5c3190de16.png)

[AWS Node.js Stack](https://aws.amazon.com/de/getting-started/hands-on/deploy-nodejs-web-app/)


## XRP Ledger intergration

For the XRP Ledger integration we will use the Ripple Node.js Library. This is a offical Ripple library that allows to communicate with the XRP Ledger.

![image](https://user-images.githubusercontent.com/52482896/121244219-e4909280-c89e-11eb-9970-6287d784e509.png)


To store and get the NFT&#39;s of an user, the users need to provide their public XRP address. With the public address we can get the NFT&#39;s from the user and send NFT&#39;s to the user.

For testing, we will use the XRP Test Net. With this Test network we can test our project without any costs.
