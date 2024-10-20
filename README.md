# Flask-Mongo
Learning about the Flask and Mongo db
A list of common HTTP status codes for REST APIs:

 These are the popular code 

200 OK: The request was successful.

201 Created: The request was successful and a resource was created.

202 Accepted: The request has been accepted for processing, but the processing is not complete.

204 No Content: The request was successful, but no content is returned.

301 Moved Permanently: The requested resource has been moved to a new URL.

304 Not Modified: The resource has not been modified since the last request.

400 Bad Request: The request could not be understood or was missing required parameters.

401 Unauthorized: Authentication failed or user does not have permissions for the requested operation.

403 Forbidden: Authentication succeeded but the user does not have permission to access the resource.

404 Not Found: The requested resource could not be found.

405 Method Not Allowed: The HTTP method is not allowed for the requested resource.

409 Conflict: The request could not be processed because of a conflict.

410 Gone: The resource requested is no longer available and will not be available again.

415 Unsupported Media Type: The request format is not supported by the server.

422 Unprocessable Entity: The request was well-formed but could not be processed due to semantic errors.

429 Too Many Requests: The user has sent too many requests in a given amount of time.

500 Internal Server Error: The server encountered an error and could not complete the request.

502 Bad Gateway: The server received an invalid response from the upstream server.

503 Service Unavailable: The server is currently unavailable (overloaded or down for maintenance).

504 Gateway Timeout: The server did not receive a timely response from the upstream server.


The codes below are less popular as compaired to the above codeSS

100 Continue: The client should continue with its request.

101 Switching Protocols: The server is switching protocols as requested by the client.

103 Early Hints: Used to return some response headers before the final HTTP message.

206 Partial Content: The server is delivering only part of the resource due to a range header sent by the client.

300 Multiple Choices: There are multiple options for the resource from which the client may choose.

402 Payment Required: Reserved for future use; often used in digital payment systems.

407 Proxy Authentication Required: The client must first authenticate itself with the proxy.

408 Request Timeout: The client took too long to send the request.

411 Length Required: The server requires the Content-Length header to be sent in the request.

412 Precondition Failed: The server does not meet one of the preconditions specified in the request.

413 Payload Too Large: The request is larger than the server is willing or able to process.

414 URI Too Long: The URI provided was too long for the server to process.

416 Range Not Satisfiable: The client has asked for a portion of the file that the server cannot supply.

417 Expectation Failed: The server cannot meet the expectations indicated in the Expect request header.

426 Upgrade Required: The server requires the client to switch to a different protocol.

428 Precondition Required: The server requires the request to be conditional (usually for PUT or PATCH requests).

431 Request Header Fields Too Large: The server refuses to process the request because one or more header fields are too large.

451 Unavailable For Legal Reasons: The server is denying access to the resource as a result of a legal demand.


