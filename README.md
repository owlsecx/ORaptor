# 🦉 ORaptor

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **ORaptor** — Disk Image Forensics ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ORaptor is a disk-image forensics tool for RAW, E01-header, VMDK, VDI and QCOW2 images. It identifies image types, parses MBR/GPT partitions, hashes evidence, carves files by signature, extracts strings and builds a timeline while preserving chain of custody. It is intended for authorised forensic use only.

---

## ✨ Features

- Identifies RAW, E01-header, VMDK, VDI and QCOW2 disk images
- MBR/GPT partition parsing
- Evidence hashing for chain-of-custody preservation
- Signature-based file carving with configurable scan size
- String extraction and entropy/slack scanning
- Full analysis pipeline with report generation

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ORaptor -i disk.raw --identify --partitions
./ORaptor -i disk.e01 --carve --scan-mb 512 -o ./out
./ORaptor -i disk.vmdk --full
./ORaptor --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
