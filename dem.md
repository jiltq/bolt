## Source 2013
```rs
struct Header {
  demo_file_stamp: [u8; 8],
  demo_protocol: i32,
  network_protocol: i32,
  server_name: [char; 260],
  client_name: [char; 260],
  map_name: [char; 260],
  game_directory: [char; 260],
  playback_time: f32,
  playback_ticks: i32,
  playback_frames: i32,
  sign_on_length: i32,
}
```
