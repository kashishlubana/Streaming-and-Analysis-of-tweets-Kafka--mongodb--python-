# Streaming and Analysis of tweets using Apache Kafka
This project consists of creating a pipeline for live Twitter streams for current trending topics

The main areas of focus are:
1) Generating the current trending topics that a user chooses from a location by making a Twitter API call
2) Extracting live Twitter streams for select two trending topics for a location
3) Making use of a distributed streaming platform to produce, store and consume collected tweets in the form of messages
4) Ingest the consumed messages into a database(MongoDB)
5) Answer 5 business questions on the data that has been ingested into the database.


# Info on installing and running Apache kafka on windows
https://towardsdatascience.com/running-zookeeper-kafka-on-windows-10-14fc70dcc771

# Info on installing and running Apache kafka on MacOS
https://medium.com/@Ankitthakur/apache-kafka-installation-on-mac-using-homebrew-a367cdefd273

# Getting twitter access tokens
1) Visit the Twitter Developers page using this link
2) Click on Apps from your user-name dropdown
3) Click on ‘Create an app’
4) Fill up all the mandatory details and click on the ‘Create’ button


