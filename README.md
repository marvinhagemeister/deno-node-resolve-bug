# Deno resolve index file bug

The node compat mode doesn't seem to support resolving to index files.

## Steps to reproduce

1. Clone this repository
2. Run `deno run -A foo.js`

## Error

```sh
error: Is a directory (os error 21)
    at file:///projects/node-resolve/foo.js:1:21
```
