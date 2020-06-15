# notes-careertrack-10.md
## User Modeling
<p>It's the developer's responsibility to store private information and not leak or misuse the user's data. The database must be password protected or behind a firewall. User's passwords should be encrypted using hashing algorithms. User Models sensitive data should never be sent to the client applications. Creating a second user profile model can used to handle data with limited access.</p>

## Cryptography 
<p>This the sciences that studies methods of encoding messages. The encoded messages can only be read by someone who know how to decode the message.</p>

## Hash Algorithm
This takes a bit of data and a key then produces a encrypted piece of data. To decrypt the piece of data you would need the same key. Token can be created in this fashion.The token can be sent back and forth as a string. 

## Basic Authorization 
I common method of sending a user/password in HTTP request. (Kinda like the header thing we used to do).
The Server is able to decode the basic auth and check it against what the user sent in the HTTPs. 
