# What I Learned Week 10

## Objects

In essence objects are arrays that use keys instead of indices to identify values. 
- Example: rather than having a value of say, 50 at index 0 in an array, an **object** can store this value 50 under the name 'fifty'.

### Other neat things:

- Objects can store objects
- Objects can store arrays
- They are the essence of the next part, JSON files.

## JSON Files

JSON files are one of the primary ways to store large quantities of data in an organized manner for Javascript

It is mostly used for transmitting data from the client to the server.

It's syntax is very similar to that of a Javascript Object, with some extra rules:

### Syntax Rules:
- No trailing commas
- Must **start** and **end** with __curly brackets__
- The keys must have quotation marks

*These rules are stricter because the server code may be written in another programming language, so this format allows universal understanding for both the client and the server.