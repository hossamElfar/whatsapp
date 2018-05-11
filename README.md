# whatsapp 

A massively scalable implementation of whatsapp.

## Getting Started

1. clone the repo 
   ```
   $ git clone https://github.com/hossamElfar/whatsapp.git
   ```

### Prerequisites

1. Java 8 
2. golang
3. postgres
4. mongodb
5. rabbitmq
6. haproxy
7. docker and docker-compose

### Installing
1. Run the 5 maven apps, main-server, chatting-app, auth-app, user-app, stories-app. Make sure to modify the resources files in each app to support your own configurations.

2. Navigate to the media-server and build the go project and run the genetrted binaries.

## Using Docker

1. Just run `docker-compose up -d` to get all the apps up and running.


