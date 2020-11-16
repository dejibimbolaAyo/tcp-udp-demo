## Introduction

There are two protocols for the Transport Layer of the OSI model (Layer 4)
- TCP (Transfer Control Protocol)
- UDP (User Datagram Protocol)

These have their particular use cases with their own pros and cons.
For example packets transmitted over TCP are generally larger than those over UDP, and this is due to the extra information a TCP connection would require to deliver a packet. Hence TCP requires higher bandwidth than a UPD connection would require.
UDP does not guarantee delivery of packets sent over its connection, but TCP guarantees delivery of packets via an acknowledgement process.

## Server

There are two servers in this project, demonstrating how TCP or UDP works.

## Client

There is a client app to showcase how a UDP server communicates over a UDP connection

## Commands

### Run TCP server

``` bash
npm run tcp
```

### Run UDP server

``` bash
npm run udp
```

### Run UDP client

``` bash
npm run client
```

