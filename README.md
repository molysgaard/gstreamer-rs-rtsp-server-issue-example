## Example showing segfault with rtsp-server example.

To reproduce in one terminal:

```
cargo run
```

And in another:

```
xdg-open rtsp://127.0.0.1:8554/test
```

