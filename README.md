This is an eureka discovery service

Steps to check microservices:

1) Clone repository discovery-service https://github.com/yurysukhorukov/discovery-service and run DiscoveryServiceApplication 

2) Clone repository note-keeper https://github.com/yurysukhorukov/note-keeper and run NoteKeeperApplication - this microservice is responsible for returning list of notes retrieved from DB

3) Clone repository notes-web-client-service https://github.com/yurysukhorukov/notes-web-client-service and run NotesWebClientServiceApplication - this is our client who will request notes

4) To check if both microservices registered on Eureka server go to http://localhost:8761/, you will see them under "Instances currently registered with Eureka"

5) To check if we can get our list of notes, go to http://localhost:9098/get-notes , you will get simple representation of Leo's notebook)