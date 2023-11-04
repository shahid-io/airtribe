# Core Session
## Topics covered in the session
`client-server architecture`, `web services` and `API's`


```There are architectures which we can differentiate with the different types of applications```
`Tier - 1` `Tier - 2` `Tier - 3`
### Tier - 1
```
~This could be an example like `Calender` `Calculator`.
~We can see in the above two applications which they don't intract with internet, It doesn't require internet to work.
~There is no Letancy there is no network calls.
~It simply giving the result based on the input and it computes the result.
```

##### client
`What are the things can be client?`
```
client can be User, frontend, service, Postman and a client can be another server.
A backend can also interact with another backend.
We can simply say that It can be anything which interact with servers.
These all interaction happens over the internet means we're somehow we're making network calls.
Our API plays a very crucial role to make network calls.
```
### API
```
client ------> request ------> server
client <------ response <------ server
```
There are different architectural paradigms to create API's
```
REST
SOAP
GRPC
RPC
GRAPHQL
```
`socket are different thing which not relate to the API's`

#### Request
`A request what do the consist of?`
```
URL (Uniform Resource Loacator)
1. A request Line.
2. A series of HTTP headers, header fields
3. A message body, if needed.

### 1. Request line
```
The request line is the first line in the request message. It consists of at least three items:
`
1. A method. The method is a one-word command that tells the server what it should do with the resource. For example, the server could be asked to send the resource to the client.
2. The path component of the URL for the request. The path identifies the resource on the server.
3. The HTTP version number, showing the HTTP specification to which the client has tried to make the message comply.
`
``` 





