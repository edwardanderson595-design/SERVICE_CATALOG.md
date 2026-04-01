# Cloud Pricing Research and Proxmox API Usage

## 1. Cloud Pricing Models Overview

This section compares typical entry‑level VPS plans from DigitalOcean, Linode, and Vultr. Prices are monthly and based on current public listings for basic/general‑purpose instances.

### 1.1 DigitalOcean

- **Provider:** DigitalOcean (Droplets – Basic)
- **Pricing model:** Flat monthly rate, per‑second billing behind the scenes
- **Typical entry plans:**

| Plan            | vCPU | RAM  | Disk    | Bandwidth | Price  |
|-----------------|------|------|---------|-----------|--------|
| Basic 1GB       | 1    | 1GB  | 25GB SSD | 1TB      | $6/mo  |
| Basic 2GB       | 1    | 2GB  | 50GB SSD | 2TB      | $12/mo |

DigitalOcean focuses on simple, predictable pricing and a developer‑friendly platform with strong documentation. 

---

### 1.2 Linode (Akamai Cloud)

- **Provider:** Linode (Shared CPU)
- **Pricing model:** Flat monthly rate
- **Typical entry plans:**

| Plan            | vCPU | RAM  | Disk     | Bandwidth | Price  |
|-----------------|------|------|----------|-----------|--------|
| Nanode 1GB      | 1    | 1GB  | 25GB SSD | 1TB       | $5/mo  |
| Shared 2GB      | 1    | 2GB  | 50GB SSD | 2TB       | $12/mo |

Linode is known for transparent pricing and strong customer support, with competitive plans in the low‑cost VPS space. 

---

### 1.3 Vultr

- **Provider:** Vultr (Cloud Compute / High Frequency)
- **Pricing model:** Flat monthly rate, hourly billing
- **Typical entry plans:**

| Plan                     | vCPU | RAM  | Disk       | Bandwidth | Price   |
|--------------------------|------|------|------------|-----------|---------|
| IPv6‑only 1GB (test)     | 1    | 1GB  | 25GB NVMe  | 1TB       | $2.50/mo |
| Cloud Compute 1GB        | 1    | 1GB  | 25GB NVMe  | 1TB       | $6/mo   |
| High Frequency 1GB       | 1    | 1GB  | 32GB NVMe  | 1TB       | $6/mo   |

Vultr often provides the lowest entry price and NVMe storage at the same price point as competitors’ SSD‑based plans, making it attractive for performance‑focused workloads. 

---

### 1.4 Summary Comparison

| Provider      | Lowest Common 1GB Plan | vCPU | RAM  | Disk      | Bandwidth | Notes                          |
|--------------|------------------------|------|------|-----------|-----------|--------------------------------|
| DigitalOcean | $6/mo                  | 1    | 1GB  | 25GB SSD  | 1TB       | Very simple UX, great docs     |
| Linode       | $5/mo                  | 1    | 1GB  | 25GB SSD  | 1TB       | Strong support, stable         |
| Vultr        | $6/mo (NVMe)           | 1    | 1GB  | 25GB NVMe | 1TB
