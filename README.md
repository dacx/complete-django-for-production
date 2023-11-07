# Demo project for the Complete Django for Production guide

### Who is this guide for?
This guide is for any developer who intends to learn how to efficiently set up a robust tech stack and host in for as cheap as $5/mo for production. Personally, I have used this setup for three successful startups I founded; a SaaS business that partnered with Airbnb, a vacation resort management system and a property billing solution.

Here, we will use Docker to create our own database and our own web server (among other services) on our own server, instead of buying countless services from a service provider such as Heroku or AWS.

The tech stack will serve as a base version for you to extend by your app's features later on. In its initial version, it will consist of the following (don't let this overwhelm you, it will all make sense as we go on):
- web server and reverse proxy to serve your django application
- database for all model entries
- asynchronous task queue

Together, we will be able to cover pretty much all use cases that you will come across in your development process. Some features that are present from the get-go:
- multi-tenancy (full support for multiple users on your site)
- social logins (talking Facebook, Google, etc.)
- automated database backups and external storage
- send emails to users (both for information and confirmations)
- create background tasks
- create cronjobs and timed tasks

### Structure
The guide is split into the following chapters. They are very thorough, and you can skip the parts that are already familiar.

1. [Setting up the development environment](https://fullcycledev.substack.com/p/complete-django-for-production-setting)
2. [Creating and launching the tech stack](https://fullcycledev.substack.com/p/complete-django-for-production-creating)
3. Understanding the tech stack
4. Renting a VPS, setting up git
5. Configuring domain and server
6. Deploying for production!

### Like the content? Support!
- [Follow on Twitter](https://links.fullcycledev.io/?twitter)
- [Join the Discord Community](https://links.fullcycledev.io/?discord)
- [Read the Substack](https://links.fullcycledev.io/?substack)
