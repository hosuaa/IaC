# Infrastructure as code

Orchastrating and Configuration

Imagine your sending an email to multiple people: you either send an email to each eprson, or send the same email to everyone -> save alot of time with the second approach

We can use IaC to spin up multiple instances at once, sending a single script to a controller which loads up a chosen number of instances and installs the given dependancies on them
- Rather than having to SSH in and do this manually (which takes a long time) we can use IaC to save development time and reduce time to deployment. 

## Tools

anisble: open source, simple (uses YAML which is human readable), powerful, agentless
- yaml is needed for cloud formation (an aws tool), docker compose, kubernates...


