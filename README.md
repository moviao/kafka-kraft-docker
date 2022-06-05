# A kafka kraft docker image Container (Experimental)

This repository provides a container image running a Kafka broker without Zookeeper (using Kraft).

**IMPORTANT:** The broker is configured for development purpose only.

## Usage

$ Shell

docker run -it -p 9092:9092  moviao/kafka-kraft:latest

# Or

docker run -it -p 9092:9092  moviao/kafka-kraft:3.2.0
