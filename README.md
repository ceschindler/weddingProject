# Weddings Made Easy

## Problem Statement
I wanted an easy way for people to do things for our wedding day, from RSVPing
to choosing wedding gifts, seeing accommodations, etc. A one stop shop for all
guests and it makes it easy for us to accumulate statistics for us to give for
the rehearsal dinner, reception hall, and numbers of things that we get to make
for that day. 

## Project Technologies/Techniques
* Security/Authentication
    * Admin role: CRUD operations of data
    * User role: RSVP
    * All: Anyone can view most tabs except RSVP
* Database (MySQL and Hibernate)
    * Store users
    * Store user responses and food choice
    * Store accommodations and details
    * Store places/events to see
* Web Services or APIs
    * Registry locations
    * Engagement Photos (Maybe hosted site, or upload to Flickr/Instagram album)
    * Weather leading up to the big day
* Logging
    * Errors logged using Log4J, but debug information displayed up till functional deploy
* Unit Testing
    * JUnit tests to achieve 80% coverage
* Site and database hosted on AWS or Digital Ocean.

* Optional add-ons (Choosing at least one)
    * SendGrid (Auto-Response emails)
    * Travis CI (Possible independent research topic)
    * Java 9 goodies (Possible independent research topic)
    
## Design
* [Screen Design](designDocuments/WeddingDesign.epgz)
* [Application Flow](designDocuments/applicationFlow.md)
* [Database Design](designDocuments/databaseDiagram.png)

## [Project Plan](projectPlan.md)
## [Time Log](timeLog.md)
## [Journal](journal.md)