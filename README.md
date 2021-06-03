# chatBox
Aim : To perform,a two-way communication between the servers and the clients, which mean both the parties, communicate and exchange data at the same time.

Making connection to the local port 4000 to make a bidirectional connection between client and server. 

var app = express();
var server = app.listen(4000, function(){
    console.log('listening for requests on port 4000,');
});

![nodemon](https://user-images.githubusercontent.com/67537391/120589118-fd8be480-c455-11eb-9a81-22bf4f666b06.PNG)

The above picture shows that we connected locally and the connection was made with unique id on the servers,i.e "socket.id" ex : "made socket connection EQcKkc4pNroe-5EmAAAA "

Here,two clients of different socket.id's connected to single server by sockets and this will run only when we call a function i.e socket.on().This socket.io emits the texts messages from the server by io.sockets.emit() .
![Chat](https://user-images.githubusercontent.com/67537391/120588616-1d6ed880-c455-11eb-9885-d19604d897b7.PNG)

