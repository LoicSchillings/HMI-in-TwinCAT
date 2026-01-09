# TwinCAT HMI – Installation & Setup Guide

This README explains how to:

1. Install **TwinCAT HMI Engineering** packages on a PC for TwinCAT  
2. Install the **TwinCAT HMI Server** on a PLC / IPC running Windows
3. Create a basic HMI project  
4. Connect the HMI to TwinCAT / PLC using ADS 


(assuming TwinCAT XAE is already installed)

---

## 0. Prerequisites

- Beckhoff PLC / IPC running **Windows**
- Engineering PC running **Windows**
- TwinCAT 3 installed
- Administrator rights on both systems
- PLC and PC preferably on the same subnet

---

## 1. Installing HMI packages for TwinCAT

### 1.1 Install the "TE2000 - TwinCAT HMI Engineering" package

This package provides the tools needed to develop a HMI project in TwinCAT on your engineering PC.

![TE2000 in Package Manager](docs/images/TE2000.png)


## 2. Installing TwinCAT HMI Server on the PLC (Windows)

### 2.1 Install the HMI Server package

On the **PLC / IPC**:

1. Open **Beckhoff Package Manager**
2. Install:
   - `TE2000 – TwinCAT HMI Server`
3. Reboot if prompted

---

### 2.2 Create an HMI Server instance

1. On the PLC, open a browser:
