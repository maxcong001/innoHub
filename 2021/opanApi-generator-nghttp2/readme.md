Currently, openAPI generator tool do not support nghttp2.

This is base frame work for openApi, we can generate client and server code via it for nghttp2 via this project.

This is the base framework for Idea:

UDM

UDR


## work list

need to study how to use nghttp2 and write a simple example with nghttp2/static json/rapid json support and then convert the example to openAPI example.

1. openapi generator support for nghttp2 C++ server -- to do
1.1 openapi core language change(language support for java)
1.2 mustache support file writting
2. openapi generator support for nghttp2 C++ client -- to do
3. openapi to json schema, this is used by static json/rapid json for schema validation and mapping json schema to C++ class -- done   https://github.com/maxcong001/openAPI2JsonSchema
4. static json/rapid json support for schema validation support 
5. nghttp2 asio clinet/server example with json support
6. mustache support with the example 
7. openapi core language change base on the example


## open issue
1. open API generator supprot anyof/oneof/allof not so well


## to do
1. query parameter? base_64?
2. path decode : /pet/:petId/uploadImage, how to route to the handler
3. route design(http2 asio do not have this )



## working 

https://github.com/maxcong001/openAPI2JsonSchema

nghttp2 asio server example with json support

