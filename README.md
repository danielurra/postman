# Postman
API testing and collaboration tool<br>
![postman-logo-580x464px](https://github.com/danielurra/postman/assets/51704179/cfc6b231-622d-4906-8a7d-53bf5eb32bc7)<br>
* Step 1 - Create a new **Workspace**
* Step 2 - Create a new **Collection** (just a group of requests)
* Step 3 - Create your requests
## Important when testing GitHub APIs
GitHub uses curly braces `{}` and Postman uses colon `:`<br>

https://docs.github.com/en/rest/users/users?apiVersion=2022-11-28#get-a-user

See example below:<br>
![github-get-a-user-api](https://github.com/danielurra/postman/assets/51704179/a948eb1f-cf5d-4e4f-ac2f-afcbbc659973)<br>
![github-get-a-user-api-postman](https://github.com/danielurra/postman/assets/51704179/5f2f9f89-df6f-4c06-a5f0-d964d72afebe)<br>
## Node.js first API
I was able to deploy my **Node.js** App to a live server, I do have a Digital Ocean Droplet (VPS) running Linux Ubuntu 22.04<br>
I did install Nginx web server on my VPS and create a few subdomains (server blocks)<br>
Once my subdomains were reachable I proceed with the SSL certificate installation, Let's Encrypt was my choice (available for free)<br>
My backend is managed by **Node.js** and **npm** I had to install both to able to deploy my App<br>
For testing the API using the subdomain I had to configure Nginx as a reverse proxy too.<br>
![http-method-GET-node js-nginx-reverse-proxy](https://github.com/danielurra/postman/assets/51704179/9d0d9db4-228f-4f62-8641-6c33edd01b36)<br>

![postman-get-03](https://github.com/danielurra/postman/assets/51704179/7a825b93-7ebe-49b4-a3ec-ea4aa92a29b8)<br>

