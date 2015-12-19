# nodejs
## Testing code by

ApacheBench  http://httpd.apache.org/docs/2.2/programs/ab.html
Siege  https://www.joedog.org/siege-home/
Jmeter  http://jmeter.apache.org/
Tsung  http://tsung.erlang-projects.org/
mocha   http://code.tutsplus.com/tutorials/testing-in-nodejs--net-35018

## Deamon and Watching

**PM2** is a sweet little tool that is going to solve two problems for you. Production process manager for Node.JS applications with a built-in load balancer. PM2 is a production process manager for Node.js applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.
[How to use PM2](https://www.digitalocean.com/community/tutorials/how-to-use-pm2-to-setup-a-node-js-production-environment-on-an-ubuntu-vps)

[![screen](https://cloud.githubusercontent.com/assets/4102119/11913846/8b4c313a-a67a-11e5-9963-1b539a73334b.jpg)](https://github.com/Unitech/pm2)

**FOREVER** A simple CLI tool for ensuring that a given script runs continuously (i.e. forever).
There are two ways to use forever: through the command line or by using forever in your code. Note: If you are using forever programatically you should install forever-monitor.

![screen](https://cloud.githubusercontent.com/assets/4102119/11913875/34991c44-a67b-11e5-9a9f-e2ecaf8e3484.jpg)

**NODEMON**  will watch the files in the directory in which nodemon was started, and if any files change, nodemon will automatically restart your node application. nodemon does not require any changes to your code or method of development. nodemon simply wraps your node application and keeps an eye on any files that have changed. Remember that nodemon is a replacement wrapper for node, think of it as replacing the word "node" on the command line when you run your script.

![screen](https://cloud.githubusercontent.com/assets/4102119/11914058/7f9a5d5e-a67e-11e5-869c-32c2b329529a.jpg)
