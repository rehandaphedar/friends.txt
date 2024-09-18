# Introduction

![friends.txt logo](https://git.sr.ht/~rehandaphedar/friends.txt/blob/main/favicon.png)

friends.txt is a standard to allow websites to link to each other.

# Specification

- The website must have a `/friends.txt` route.
- The `/friends.txt` route must return a plaintext file, which must be a newline separated list of domains.
- The `/friends.txt` route should have CORS enabled.

# Clients

- [frensviewer](https://sr.ht/~rehandaphedar/frensviewer): Web client.
- [frendds](https://sr.ht/~rehandaphedar/frendds): Program to generate `D2` files for a domain.
- [frendds-api](https://sr.ht/~rehandaphedar/frendds-api): A web server for frendds.
- [txtfriendscli](https://github.com/Asost/txtfriendscli): BASH client.

# Websites

For a list of websites with friends.txt files, see [websites.txt](https://git.sr.ht/~rehandaphedar/friends.txt/tree/main/item/websites.txt). Create a patch to add your own website.
