# SSLKEYLOGFILE Extension for Encrypted Client Hello (ECH)

This repository contains sample PCAPs and `SSLKEYLOGFILE` file with TLS
handshakes using Encrypted Client Hello (ECH).

In addition to the usual `SSLKEYLOGFILE` handshake traffic secrets the
key log data is augmented with ECH configuration and derived secret based on
[draft-rosomakho-tls-ech-keylogfile].

[draft-rosomakho-tls-ech-keylogfile]: https://datatracker.ietf.org/doc/draft-rosomakho-tls-ech-keylogfile/
