# Image Binary

# Dependencies
- [`rust`](https://www.rust-lang.org/)

# Installation
```sh
$ git clone https://github.com/carrotshniper21/image-binary
$ cd image-binary
$ cargo build --release
```

# Routes 
### /upload
Example Request
```sh
curl -X POST \
  https://example.com/upload \
  -H 'Content-Type: application/json' \
  -d '{
    "filetype": "image/png",
    "contents": "data:image/png;base64,(image data here)"
  }'
```
