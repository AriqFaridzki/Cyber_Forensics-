# Cyber Week #1 - Cloud Computing Assessment and Mitigation

        

## Daftar Isi

- [Cyber Week #1 - Cloud Computing Assessment and Mitigation](#cyber-week-1---cloud-computing-assessment-and-mitigation)
  - [Daftar Isi](#daftar-isi)
  - [X. Virtualization Tools](#x-virtualization-tools)
    - [X.1. Pendahuluan](#x1-pendahuluan)
  - [2. Perbandingan Singkat](#2-perbandingan-singkat)
  - [3. Detail Virtualisasi Tools](#3-detail-virtualisasi-tools)
    - [3.1 VMware Workstation Pro](#31-vmware-workstation-pro)
    - [3.2 VirtualBox](#32-virtualbox)
    - [3.3 XenServer](#33-xenserver)
    - [3.4 Proxmox VE](#34-proxmox-ve)
    - [3.5 OpenStack](#35-openstack)
  - [4. Kesimpulan](#4-kesimpulan)


## X. Virtualization Tools

### X.1. Pendahuluan

Virtualisasi adalah teknologi yang memungkinkan satu komputer fisik menjalankan beberapa sistem operasi secara bersamaan. Teknologi ini banyak digunakan dalam pengujian, pengembangan, dan infrastruktur IT berbasis cloud. Berikut adalah daftar alat virtualisasi populer, lengkap dengan deskripsi, dokumentasi, serta kelebihan dan kekurangannya.


keyword : “Virtualisasi, host, guest, cloud, cluster, node, backup, restore, snapshot, suspend”.

---

## 2. Perbandingan Singkat

| Nama| Jenis | Keunggulan | Kekurangan  |
| -------------------------- | ------------------- | --------------------------------------------------------- | --------------------------------------------------- |
| **VMware Workstation Pro** | Type-2 Hypervisor   | Stabil, banyak fitur enterprise, performa tinggi          | Berbayar, cukup berat untuk hardware lawas          |
| **VirtualBox**             | Type-2 Hypervisor   | Gratis, open-source, mendukung berbagai OS                | Performa lebih rendah dibanding VMware              |
| **XenServer**              | Type-1 Hypervisor   | Cocok untuk server, skala besar, mendukung live migration | Tidak se-user-friendly Type-2 Hypervisor            |
| **Proxmox VE**             | Type-1 Hypervisor   | Gratis, berbasis Debian, mendukung LXC & KVM              | UI tidak semudah VMware, butuh sedikit pembelajaran |
| **OpenStack**              | Cloud Orchestration | Fleksibel untuk cloud computing, open-source              | Konfigurasi rumit, butuh resource besar             |

---

## 3. Detail Virtualisasi Tools

### 3.1 VMware Workstation Pro

VMware Workstation Pro adalah **Type-2 Hypervisor** yang memungkinkan pengguna menjalankan beberapa sistem operasi dalam satu komputer. Cocok untuk pengembang, pengujian, dan infrastruktur IT tingkat lanjut.

- **Dokumentasi**: [VMware Workstation Pro Docs](https://techdocs.broadcom.com/content/dam/broadcom/techdocs/us/en/pdf/vmware/desktop-hypervisors/workstation/vmware-workstation-pro-17-0.pdf)
- **EULA**: [VMware License](https://static.carahsoft.com/concrete/files/6214/1995/7902/VMware3.pdf)
- **Unduh**: [Download VMware](https://support.broadcom.com/group/ecx/downloads)

### 3.2 VirtualBox

VirtualBox adalah virtualisasi open-source dari Oracle yang ringan dan mudah digunakan. Cocok untuk pengguna pemula atau yang ingin menjalankan sistem operasi tambahan di komputer mereka.

- **Dokumentasi**: [VirtualBox Docs](https://www.virtualbox.org/manual/)
- **Ketentuan Penggunaan**: [Oracle Terms](https://www.oracle.com/legal/terms/?er=221886)
- **Unduh**:
  - [Windows](https://download.virtualbox.org/virtualbox/7.1.6/VirtualBox-7.1.6-167084-Win.exe)
  - [Ubuntu 24](https://download.virtualbox.org/virtualbox/7.1.6/virtualbox-7.1_7.1.6-167084~Ubuntu~oracular_amd64.deb)

### 3.3 XenServer

XenServer adalah **Type-1 Hypervisor** yang didesain untuk server dan pusat data. Cocok untuk manajemen virtualisasi tingkat lanjut dan skala besar.

- **Dokumentasi**:
  - [EULA XenServer](https://www.cloud.com/content/dam/cloud/documents/legal/end-user-agreement.pdf)
  - [Panduan Instalasi XenServer](https://docs.xenserver.com/en-us/xenserver/8/install)
  - [Panduan XenCenter](https://docs.xenserver.com/en-us/xencenter/current-release/install-xencenter)
- **Unduh**:
  - [XenServer](https://downloads.xenserver.com/xenserver/2024-12-09.1756/XenServer8_2024-12-09.iso)
  - [XenCenter](https://downloads.xenserver.com/xencenter/2024.4.0/XenCenter-2024.4.0.msi)

### 3.4 Proxmox VE

Proxmox adalah solusi **Type-1 Hypervisor** berbasis Debian yang mendukung virtualisasi berbasis KVM dan container dengan LXC. Banyak digunakan untuk server pribadi dan enterprise.

- **Dokumentasi**:
  - [Panduan Administrasi Proxmox VE](https://www.proxmox.com/images/download/pve/docs/pve-admin-guide-8.3.pdf)
  - [Pusat Dokumentasi](https://www.proxmox.com/en/downloads/proxmox-virtual-environment/documentation)
- **Unduh**:
  - [Download Proxmox VE](https://enterprise.proxmox.com/iso/proxmox-ve_8.3-1.iso)

### 3.5 OpenStack

OpenStack bukan sekadar hypervisor, tetapi **platform orkestrasi cloud** yang memungkinkan pembuatan infrastruktur cloud publik dan privat.

- **Dokumentasi**:
  - [Panduan Instalasi OpenStack](https://docs.openstack.org/id/install-guide/)
- **Lisensi**: OpenStack menggunakan **Apache License 2.0** (Gratis & Open-Source)
- **Unduh**: [DevStack (OpenStack Lokal)](https://opendev.org/openstack/devstack)

---

## 4. Kesimpulan

Pemilihan alat virtualisasi tergantung pada kebutuhan:

- **Untuk Pengguna Pemula**: VirtualBox (Gratis & Mudah Digunakan)
- **Untuk Pengembang & IT Profesional**: VMware Workstation Pro (Stabil & Banyak Fitur)
- **Untuk Infrastruktur Skala Besar**: XenServer atau Proxmox (Server-Level, Open-Source)
- **Untuk Cloud Computing**: OpenStack (Orkestrasi Cloud Fleksibel)


