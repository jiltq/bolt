## Source 2013
```rs
struct MeshHeader {
  m_nLod: u32,
  m_nVertexes: u32,
  m_nOffset: u32,
  m_nUnused: [u32; 4],
};

struct FileHeader {
  m_nVersion: i32,
  m_nChecksum: u32,
  m_nVertexFlags: u32,
  m_nVertexSize: u32,
  m_nVertexes: u32,
  m_nMeshes: i32,
  m_nUnused: [u32; 4],
};
// WIP
```
