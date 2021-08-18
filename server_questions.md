## 1. Difference between sites-available and sites-enabled NGINX directories.

> The `sites-available` folder is for storing _all_ of your vhost configurations, whether or not they're currently enabled
> 
> The `sites-available` folder is for storing _all_ of your vhost configurations, whether or not they're currently enabled


## 2. Why NGINX instead of other Web servers?

> Nginx can perform a much better job at handling the static files from a specific directory. Also, the upstream server processes don't get blocked because of the heavy, multiple static content requests as Nginx can process them concurrently. This significantly improves the overall performance of backend servers.


## 3. What is the protocol behind the main internet ports?

> TCP/IP


## 4. Could we use any port to connect anything?

> Yes, regardless of whether some are standardized, they are still used to connect in one way or another to the server.


## 5. Talking about Docker, Is a container port the same as a server port? argue your answer.

> No. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings. And a server port is simply the communication path between the local server and the remote server.
