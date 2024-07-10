## Quake II
```rs
struct Frame {
  width: i32,
  height: i32,
  origin_x: i32,
  origin_y: i32,
  name: [u8; 64],
};

struct Sp2 {
  ident: i32,
  version: i32,
  num_frames: i32,
  frames: [Frame; 1],
};
```
