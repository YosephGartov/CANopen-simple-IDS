# CANopen-simple-IDS
C++-based Intrusion Detection System (IDS) for detecting anomalous CANopen traffic, including PDO injection, flooding, replay attacks, and heartbeat failures in a virtual CAN environment.

## Project Overview

This project implements an IDS in a virtual CANopen environment using:

- Linux SocketCAN
- vcan0
- cannelloni
- can-utils
- CANopen
- C++

The system monitors CAN traffic and detects abnormal behavior such as:

- PDO injection
- CAN flooding
- Replay attacks
- Heartbeat timeouts

The attacker and defender operate on separate virtual machines and
communicate through a cannelloni CAN tunnel.
