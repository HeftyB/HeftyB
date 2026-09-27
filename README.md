# Andrew Shields

Software and systems generalist in Jacksonville, FL. I build applications and run the infrastructure under them: Java and Spring Boot at one end, Linux, Proxmox, ZFS and VLANs at the other.

Looking for a junior or entry-level role in software development or systems administration.

## Start here

**[DMS](https://github.com/HeftyB/DMS)** — Java 21, Spring Boot, SQL Server. Software for running an independent auto repair shop: customers and vehicles, repair orders, parts, appointment scheduling, timekeeping and invoicing. About 11,500 lines of Java that I wrote by hand, solo, between June 2024 and February 2025; that build is tagged [`v1.0-handwritten`](https://github.com/HeftyB/DMS/tree/v1.0-handwritten). The 2026 commits are a maintenance pass with Claude Code that added tests and CI and fixed bugs. They're attributed in the commit log, and the README separates the two.

**[Musical-Trainer](https://github.com/HeftyB/Musical-Trainer)** — Swift, SwiftUI, CoreMIDI. A macOS app that measures and trains musical timing from MIDI. Claude Code wrote the code under my direction: I set the design and the rules, reviewed its 80+ pull requests, and gated its changes with 926 tests and CI on my self-hosted Gitea and Woodpecker.

**[mdtools](https://github.com/HeftyB/mdtools)** — C. A native Markdown toolkit: CommonMark parser, print CLI and terminal reader. Built by directing Claude and Codex; the README covers how the output was verified.

**[SetGame](https://github.com/HeftyB/SetGame)** — Swift, SwiftUI. The card game Set, written for Stanford's CS193P in 2022.

## Infrastructure

A three-node Proxmox VE cluster built from bare metal: tiered ZFS storage, VLAN-segmented networking behind OPNsense, split-horizon DNS with wildcard TLS, Prometheus and Grafana on every node, and self-hosted Gitea with Woodpecker CI. I've been self-hosting since 2021.

**[Network diagnostic runbook](https://github.com/HeftyB/network-diagnostic-runbook)**: symptom-based troubleshooting for Linux hosts, DHCP, DNS and VLANs. It grew out of a wireless outage I traced to a switch-port VLAN tagging mismatch, and includes that incident's retrospective.

## Background

Full-stack web development at Bloom Institute of Technology (Lambda School), then C# and .NET on a production contract. Before software, automotive dealership service: service advising and manufacturer warranty administration. Studying for the RHCSA.

[heftyb.com](https://heftyb.com) · **heftyb@heftyb.com** · [LinkedIn](https://www.linkedin.com/in/heftyb)
