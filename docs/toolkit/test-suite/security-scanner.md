---
title: Security Vulnerability Scanner
sidebarSortOrder: 5
sidebarLabel: Security Scanner
seoTitle: "How to check for security vulnerabilities in Solana programs"
description: "How to check for security vulnerabilities in Solana programs"
keywords:
  - solana security
  - solana programs
  - program development
  - program security
  - security vulnerabilities
  - solana vulnerabilities
  - solana security best practices
---

> This is a beta version of the [Solana Toolkit](/docs/toolkit/index.md), and is
> still a WIP. Please post all feedback as a GitHub issue
> [here](https://github.com/solana-foundation/developer-content/issues/new?title=%5Btoolkit%5D%20).

## Static Analysis Tools

[Radar](https://github.com/Auditware/radar?tab=readme-ov-file) is static
analysis tool for Anchor rust programs. It allows you to write, share, and
utilize templates to identify security issues in rust-based programs using a
powerful python based rule engine that enables automating detection of
vulnerable code patterns through logical expressions.

[Xray](https://github.com/sec3-product/x-ray) is an open-source, cross-platform
command-line interface (CLI) tool designed for static analysis of Solana
programs and programs written in Rust.

## Common Security Exploits and Protections

Read [Sealevel Attacks](https://github.com/coral-xyz/sealevel-attacks) for
examples of common exploits unique to the Solana programming model and
recommended idioms for avoiding these attacks using the Anchor framework.
