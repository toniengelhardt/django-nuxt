# django-nuxt
Template for a Django/Nuxt PWA with axios, vuex, REST, JWT auth, markdown blog, etc.

### What is this?
I'm working on a Django Nuxt PWA and it is tedious to get all the basic workflows going. While there is a lot of material out there on how to build a simple app, it's hard to figure out more advanced concepts, especially when you build your first Django/Nuxt app. This is an attempt to create a template for a Django/Nuxt PWA that has all essentials included and you can basically just clone it and have all the boilerplate working:

- Django backend with REST API
- Vue/Nuxt Universal PWA frontend with axios request library
- JSON Web Token (JWT) authentication (local, Facebook, Google)
- Password reset with magic links
- Fontawesome integration
- Markdown blog with lazy image loading (based on https://github.com/marinaaisa/nuxt-markdown-blog-starter)

### Stack 
Python 3, PostgreSQL, Django 3, RESTframework, Vue 2, Axios, Vuex, Nuxt, HTML5, SCSS.

## Django

TBD...

## Vue/Nuxt

TBD...

#### Cookie Consent

Simple popup to handle GDPR and cookie consent.

## Authentication

#### Registration

Authentication with @nuxtjs/auth module and django_restframework_jwt module. Customized to use auth- and refresh tokens for enhanced security.

Strategies:

- Local
- Social
  - Facebook
  - Google

#### Login/Logout

Including wiping of the vuex store and destroying of cookies.

#### Password reset

Use Magic Links and in-app password change to reset the password (please report security issues if you find any).

## Blog 

#### AddThis

Social sharing for blog posts.

#### Mailchimp

Email subscription for new posts.

## Google Analytics

TBD...

## Sentry

Issue tracking for frontend and backend (free for basic use).

## Sendgrid

Emails that don't end up in the spam folder (free up to 100 emails/day). Used for email confirmation and password reset.

## Websockets

Coming later...

## HTTP/2

Serve via HTTP/2 to make the app fast.

## Hosting

Digital Ocean, Ubuntu, NGINX, Gunicorn, PM2.

## Automatic DB backups with cron

Generate daily/weekly/monthly backups automatically with cron and a bash script.

## SEO

All the easy things for Search Engine Optimization: meta tags, page speed, etc.
