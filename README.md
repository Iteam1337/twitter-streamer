Twitter Face Indexer Demo
=========================

## What is this?

We wanted to show how to use Docker and Tutum.co to construct a pretty advanced setup by combining a set of small parts with specific purpose.

The end result will be listening to Twitter for tweets and extracts images and parses face characteristics which is indexed to Elasticsearch and sent with socket.io to a display. A Kibana is directed to the Elasticsearch instance for easy analysis.

## Demo!

Tweet an image to #kodapor and see the results [http://react.devsum.cont.tutum.co](here)

## Prerequisites
- FaceAPI key from Microsoft Azure. This is free but very hard to find. Follow [https://www.projectoxford.ai/doc/general/subscription-key-mgmt](these instructions)
- Twitter key - create a new Twitter App and generate app keys.
- Docker (and Boot2Docker if you use Mac OSX or Windows)
- Docker Compose
- A [](tutum account)

## How to set it up

Clone this repo. 




## Components

This demo shows how you can use Docker and Tutum.co to deploy a 