# P2P over QUIC
Let's make P2P applications using the IETF QUIC protocol!

## TODO
- Find latest IETF QUIC implementations in C/C++
  - [mvfst](https://github.com/facebookincubator/mvfst), [QUANT](https://github.com/NTAP/quant), [picoquic](https://github.com/private-octopus/picoquic)
- Start toy projects using QUIC libraries 
  - Simple chatting app
  - File sharing
    - Perfomance comparison to FTP/TCP : response time, average throughput, and etc.
  - Unreliable transmission
  - Use boost.asio or (experimental) networking TS
- Develop a P2P version of it
  - Peer discovery
