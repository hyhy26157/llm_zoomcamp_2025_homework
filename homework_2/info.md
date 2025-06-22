
1. download qdrant binary as an alternative to qdrant docker.
 - https://github.com/qdrant/qdrant/releases/download/v1.14.1/qdrant-x86_64-pc-windows-msvc.zip
2. run qdrant.exe locally as backend engine.
3. start running the homework_code




## INFO
u1. sing pip install qdrant-client because limitation of space for C drive using windows docker locally.
- https://hub.docker.com/r/qdrant/qdrant for more info

- vector search is king when it come to provide back information that is "similar enough". it is meant for casual user who are working with large corpus of information. Heres the thing. Especially when working with document. 

- keyword or vector search
is not a either or thing. its usually both. especially with rag. 
lesson 1 show elasticsearch. its a structured search + vector search.

## important
- k filtering search combine keyword search, following by vector search. a combination of best of both world.