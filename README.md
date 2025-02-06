# Caddy Stub Redirect

This project demonstrates a simple use-case scenario for caddy. The use-case is to provide a simple 200 ok response.

For example, sometimes a DevOps team creates an instance for use, but does not know what to populate it with. That makes monitoring it difficult at first. This project provides a small service that can be monitored until a real service is put in place.


## Use Cases

Return one of the following:

- ok
- blank page
- html page with automatic redirect (with and without javascript)
- permanent redirect
- temporary redirect

## Example Cases

A server is being deprecated. A service is replaced with this one to either provide nothing or be friendly and provide a message and redirect.

## Requirements

The only requirement is Docker. You can achieve the same results by installing caddy directly.

## Benefits

DevOps (and other teams) can get something running on the box quickly and establish node monitors earlier.
