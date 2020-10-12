# *rw-38*

## Introduction
This is a planning document for a website that serves as an aggregator for polling information and as a petitioning platform. 

## Deployment
```
Bundle install
Rackup
In your browser, visit localhost:9292
```

The website will either use Sinatra or Rails. This decision is yet to be made, and therefore effects how you would deploy the site.

## Tests
Testing is done through a combination of Rspec, Jasmine, and Capybara. Rspec, Capybara and other assosciated gems (simplecov) are included in the bundle install required for deployment.

---
## MVP
* A website running on Sinatra, using Postgres , that a user can sign up to and start a new petition.
* A page that contains links to external polling websites.
* (Stretch) A way for users to sign eachother's petitions.

---
## Example user stories
The user stories listed here are *very* macro and exist to illustrate what the site could do, rather than features that have been written out and tested.
```
As a visitor to the site
I want to have a clear view of recent polling updates
So that I can make informed decisions

As a visitor to the site
I want to sign a page with petitions on it
To see those that I would like to sign

As an administrator
I want a way to approve user petitions
To retain editorial control of the website

As the business owner
I need to see how people are using the website
To monetize web traffic and raise more funds
```
