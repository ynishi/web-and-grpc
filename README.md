# web-and-grpc

* web app using grpc backend
* under network that it is can be able to use grpc protocol directory.
* ie. internal system.

## why grpc

grpc might be heavy to make internal system, but there are benefits to accept complexity.

* internal systems are live long time, similer to company rather than each services.
* internal systems use many commonly layer like auth, reporting, and so on.
* there are case to change data structure is difficult, grpc is useful because it is suppose to maintain data longtime.

## frameworks
### frontend
* vue.js https://jp.vuejs.org/index.html
* grpc-web https://github.com/grpc/grpc-web (or rest access via grpc-gateway is more stable)
### backend
* grpc-gateway(rest api wrapper for grpc)
* grpc https://grpc.io/
* grpc-go https://github.com/grpc/grpc-go
* leveldb/boltdb/RDBMS(decentralized data store)
* data service(grobal data store)
* docker-compose(pacakge each service)
