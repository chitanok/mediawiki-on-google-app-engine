# mediawiki-on-google-app-engine
This repository is for, host your MediaWiki on Google App Engine.

# About MediaWiki
MediaWiki is a free and open source software wiki package written in PHP, originally for use on Wikipedia. It is now also used by several other projects of the non-profit Wikimedia Foundation and by many other wikis, including this website, the home of MediaWiki.
Use the links below to explore the site contents. You'll find some content translated into other languages, but the primary documentation language is English.


# How to install on Google App Engine.
 - Download MediaWiki stable version from there website.
 - Create Sql instances on Google Cloud SQL
 - Set root password and create user account and database for use on MediaWiki local
 - Clone this repository and keep files inside the mediawiki folder
 - Then install MediaWiki on you local PC. It can be inside Xampp or wamp.
 - Run cloud-sql-proxy and use database accordingly.
 - Run setup MediaWiki
 - After setup done test everything working fine.
 - Then deploy your MediaWiki to Google App engine 
   			- gcloud app deply
