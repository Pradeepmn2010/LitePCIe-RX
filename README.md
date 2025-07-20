# 🧩 LitePCIe-RX: Modular PCIe Receive Pipeline

This repository contains a modular, simulation-driven PCIe Receiver IP built for ASIC-level design verification and RTL development. It includes:

- ✅ SyncFIFO-IP: Parametric FIFO with assertions + coverage
- ✅ PCIe-8b10bDecoder: PHY-compliant 8b/10b decoder
- ✅ PCIe-TLPParser: MMIO-style TLP Decoder
- ✅ LitePCIe-RX Integration: End-to-end symbol-to-MMIO system

## 🎯 Goals
- Build protocol-aligned, reusable RTL blocks
- Verify with assertions, functional coverage, scoreboarding
- Learn real-world project execution for DV/RTL roles

## 🗂️ Project Modules
| Module             | Description                        |
|--------------------|------------------------------------|
| SyncFIFO-IP        | Synchronous FIFO buffer            |
| PCIe-8b10bDecoder  | PHY Decoder (8b/10b + disparity)   |
| PCIe-TLPParser     | Parser for PCIe TLPs               |
| LitePCIe-RX-Integration | Final RX subsystem (symbol to MMIO) |


