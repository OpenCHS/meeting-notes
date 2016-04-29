Attendees
* Vivek
* Vinkesh
* Mihir


#### Things to Discuss
Discuss the spike on decision support approach
Brief update from JSS trip
Next item to develop after Decision Support
database spike

#### Meeting Notes
##### Spike on decision support
JavaScript seems simple and sufficient enough for the requirements. One issue could be that modifying this via a user interface may be difficult in future.

##### Database Spike
The spike is going on. We discussed broadly that there is no perfect solution and it is really a tradeoff.
We discussed how document modelling should be done in mongodb and what things will not be possible if we go that way.
We discussed about lack of transaction across multiple documents. But also that many people face the same issues and design around it.
With postgres we will face challenges at large size. Sharding provides an option but lack of active active replication is an issue, essentially requiring down time. It could be that we live with this tradeoff.
More to be discussed next time.

##### JSS trip
Details have been captured in the document in drive
JSS health information architecture was discussed (diagram in the document)
the need for a system by which one can keep track of individuals not falling off the radar is important. with paper based system this is really hard to achieve.

##### Next item after decision support
Anything we develop will require some basic building blocks in place like reference data and a way to register individuals
so this perhaps is the right next feature/epic to work on
