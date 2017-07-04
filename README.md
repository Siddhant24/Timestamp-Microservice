# Timestamp API

Timestamp Microservice

Pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016).
If it does, both the Unix timestamp and the natural language form of that date are returned.
If it does not contain a date or Unix timestamp,null is returned for those properties.
Example usage:

https://clover-propane.glitch.me/December%2015,%202015 
https://clover-propane.glitch.me/1450137600


Example Output:

{ "unix": 1450137600, "natural": "December 15, 2015" }
