# bittorrent

BitTorrent client in Rust.

## Architecture

- `src/main.rs` -- CLI entry point
- `src/bencode.rs` -- Bencode encoder/decoder
- `src/torrent.rs` -- .torrent file parser
- `src/tracker.rs` -- HTTP/UDP tracker protocol
- `src/peer.rs` -- Peer wire protocol (TCP)
- `src/piece.rs` -- Piece selection and verification (SHA-1)
- `src/disk.rs` -- File I/O and piece assembly

## Dev

```bash
cargo build
cargo test
cargo clippy
```

## Conventions

- Rust 2021 edition
- tokio for async networking
- No unsafe blocks unless absolutely necessary
