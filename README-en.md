[简体中文](README.md) | [English](README-en.md)

> [rathole](https://github.com/rapiz1/rathole) is a secure, stable, and high-performance NAT traversal tool written in Rust, similar to [frp](https://github.com/fatedier/frp) and [ngrok](https://github.com/inconshreveable/ngrok). It allows services on devices behind NAT to be exposed to the public internet through a server with a public IP.

Compiled based on the latest commits (full SHA: be14d124a22e298d12d92e56ef4fec0e51517998) of the [rathole](https://github.com/rapiz1/rathole) project (Commits on Jun 6, 2024), and can run on CentOS7 (x86_64).

![image-20250307004427433](assets/image-20250307004427433.png)

Solved the error `./rathole: error while loading shared libraries: libssl.so.3: cannot open shared object file: No such file or directory`.

![image-20250307004654150](assets/image-20250307004654150.png)

## File Differences

- rathole: Uncompressed
- rathole-upx: Compressed with upx

