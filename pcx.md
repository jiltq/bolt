## Quake II
```rs
struct PCX {
  manufacturer: char,
  version: char,
  encoding: char,
  bits_per_pixel: char,
  x_min: u16,
  y_min: u16,
  x_max: u16,
  y_max: u16,
  h_res: u16,
  v_res: u16,
  //
  //
  filler: [char; 58],
  data: u8
};
```
