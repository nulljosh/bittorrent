<img src="icon.svg" width="80">

# bittorrent

![version](https://img.shields.io/badge/version-v0.1.0-blue)

BitTorrent client built from scratch in Rust. Bencode parser, tracker protocol, peer wire protocol, piece management, and disk I/O.

## Build

```bash
cargo build --release
./target/release/bittorrent download file.torrent
```

## Test

```bash
cargo test
```

## License

MIT 2026 Joshua Trommel
