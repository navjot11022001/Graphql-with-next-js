# Graphql-with-next-js

🚀 Introduction
In this we will cover the all fundamentals regarding the graphql and we will also use this graphql in out next js application to have some more clear understanding of the things.

💡 Why GraphQL?
GraphQL is an open-source data query and manipulation language developed by Facebook in 2012 and publicly released in 2015. It is designed to provide a more efficient, powerful and flexible alternative to traditional RESTful API architectures

What actually happens when we we use the REST apis :-
So as a client i will shoe the ui to the use on the basis of the data which i recieved from the server , but see on the other hand who is the owner of deciding what to show on ui- it is the client , so why server is being deciding that which data is to be send to client on which client will do some operation and will show that into the ui. 
And sometime there also the case when data comes in a huge quantity which might be for not any use but still it comes in the request , so why to fetch the over data when we don't need it ...? 
And also sometime there might be the case that the data which you are expecting to be come from the paticular request didn't came so in this case you might fetch some different api to fetch that required data.so this is the problem of under fetching.

🌟 Benefits of GraphQL

Well to addres these kind of problem graphql came into the picture which gives th owner ship of deciding which data to be fetched from the server to the CLIENT, so now i as a client can decide the data what to fetch .so  allowing clients to request only the data they need and reducing the number of requests needed to fetch that data.

With REST, a client has to request an entire resource even if it only needs a few fields This results in the client receiving more data than it actually needs, which can slow down the request and waste resources. In contrast, GraphQL allows clients to specify exactly what data they need, down to the field level, in a single query. 

And server will listen to the reqiuest and will send the corresponding data to the client.


Another benefit of GraphQL is its flexibility. With REST APIs, developers have to create specific endpoints for each data query. 
This can lead to API sprawl and make it difficult to maintain and evolve the API over time.

#### In contrast, GraphQL provides a single, flexible endpoint that allows clients to specify the data they need, including nested and related data. ####
So this reduces the complexity of the client code and makes it easier to add new features or change the schema over time to time .
because we only have one endpoint which is again the POST call.

GraphQL is also schema-based, which means that developers can define a schema that describes the data ,and operations available in the API. This schema can be used to validate queries, generate documentation, and even generate client-side code.

#####
In summary, GraphQL is a powerful tool for building efficient, flexible, and easy-to-maintain APIs. It eliminates many of the problems associated with traditional REST APIs, including overfetching and underfetching of data, and provides a flexible and schema-based approach to API development.