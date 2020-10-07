# rw-38

## Introduction
This is a planning document for a website that serves as an aggregator for polling information and as a petitioning platform. 

## Deployment
```
Bundle install
[probably] Rackup
```

The website will either use Sinatra or Rails. This decision is yet to be made, and therefore effects how you would deploy the site.

## Tests
Testing is done through a combination of Rspec, Jasmine, and Capybara. Rspec, Capybara and other assosciated gems (simplecov) are included in the bundle install required for deployment.

---
## Example user stories
The user stories listed here are *very* macro and exist to illustrate what the site could do, rather than features that have been written out and tested.
```
As a visitor to the site
I want to have a clear view of recent polling updates
So that I can make informed decisions about what I think

As a visitor to the site
I want to sign a page with petitions on it
To see those that I would like to sign

As an administrator
I want a way to approve user petitions
To retain editorial control of the website
```