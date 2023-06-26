# Why this topic matters

>to enhance the user experince ,It's important to use tokens to allow the user to navigate through the website without signing in each time .

## What is a JSON Web Token (JWT)?

### It's a web standard that provides a secure way to transmit information between two parties as a JSON object and it can be verified and trusted cause its digitaly signed

## When should we use JSON Web Tokens?

### When we want to secure our tokens and our send data,and verify it's the same as the sent one

## Claims are expected in which structural component of a JWT?

>JSON

## If I get a JWT and I can decode the payload, how can we call that secure?

### we generally dont send sensitve data in as JWT ,but its useful when we want to send data and know when any change has been done on it

## If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

## they should know the SECRET KEY 

## Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter

>we can extract the concatenated data easily cause it follows a certain structure ,also cause its signed we can easly know if it has changed.

## JWT is Compact and self-contained. Describe how this is useful to a non-technical friend

>cause its sent as a JSON seperated by dots and and the output is three base64 url strings based by dots so it can be easly sent in HTTP AND HTML .

## What are the three components (the structure) of a JWT signature?

>its self contained,compact ,and singed digitally.

## Things I want to know more about

> knowing more about how the token is produced and put together
