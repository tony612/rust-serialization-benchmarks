Result:

```
running 19 tests
test capnp_deserialize                 ... bench:         257 ns/iter (+/- 36) = 1743 MB/s
test capnp_deserialize_packed          ... bench:         480 ns/iter (+/- 54) = 702 MB/s
test capnp_populate                    ... bench:         433 ns/iter (+/- 192)
test capnp_serialize                   ... bench:          25 ns/iter (+/- 3) = 17920 MB/s
test capnp_serialize_packed            ... bench:         337 ns/iter (+/- 73) = 1000 MB/s
test clone                             ... bench:       1,091 ns/iter (+/- 137) = 480 MB/s
test flatbuffers_deserialize           ... bench:           0 ns/iter (+/- 0) = 472000 MB/s
test flatbuffers_populate_with_args    ... bench:         598 ns/iter (+/- 353)
test flatbuffers_populate_with_builder ... bench:         481 ns/iter (+/- 88)
test flatbuffers_serialize             ... bench:           0 ns/iter (+/- 0) = 472000 MB/s
test rmp_serde_deserialize             ... bench:       1,891 ns/iter (+/- 346) = 151 MB/s
test rmp_serde_serialize               ... bench:         335 ns/iter (+/- 65) = 856 MB/s
test rust_bincode_deserialize          ... bench:       1,328 ns/iter (+/- 401) = 301 MB/s
test rust_bincode_serialize            ... bench:         183 ns/iter (+/- 38) = 2185 MB/s
test rust_protobuf_deserialize         ... bench:         476 ns/iter (+/- 48) = 600 MB/s
test rust_protobuf_populate            ... bench:       1,313 ns/iter (+/- 235)
test rust_protobuf_serialize           ... bench:         419 ns/iter (+/- 27) = 682 MB/s
test serde_json_deserialize            ... bench:       2,084 ns/iter (+/- 209) = 290 MB/s
test serde_json_serialize              ... bench:       1,154 ns/iter (+/- 383) = 524 MB/s
```
