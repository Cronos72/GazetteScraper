# GazetteScraper
### Programm to connect to the University of Calgary's LIBRARIES
### AND CULTURAL RESOURCES api and retrieve "Alberta Gazette 1908" .
### The website https://cdm22007.contentdm.oclc.org/digital/collection/p22007coll9/id/492409/rec/2
### Does this via a fetch request which can be viewed in the developer tools network tab.
### This program emulates this behavior. It makes a request to the api which returns a json object
### Which needs is then unicode encoded and writen toa file called book txt.
### The following improvements are needed:
#   Error handling in case the server fails to respond. (atm just rerun program)
