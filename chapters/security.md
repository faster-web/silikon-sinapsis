# Security

## PHP
Anytime you put passwords in a database, you should scramble or hash the password so if the data-base is compromised, the passwords can’t be easily read. Hashing is a one-way process. You take a string of characters and pass it through a function that turns it into what looks like gibberish. This gibberish is not translated back. When someone logs in, you run the password through the same function and compare that result to the password stored in the database.

## SQL