<h1><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="35"/> Hi! Nice to see ya ~.</h1>
# Hi there, I'm RikkaCCLC 👋

[![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=RikkaCCLC.RikkaCCLC)](https://github.com/RikkaCCLC)
[![GitHub Follow](https://img.shields.io/github/followers/RikkaCCLC?label=Follow&style=social)](https://github.com/RikkaCCLC)

> **Systems Engineer | Open Source Enthusiast | Rustacean & C++ Developer**

I am a passionate software engineer specializing in **High-Performance Computing (HPC)**, **Distributed Storage Systems**, and **Cloud-Native Infrastructure**. My research focuses on optimizing I/O throughput for modern hardware (NVMe SSDs) and designing low-latency systems using lock-free data structures and asynchronous runtime models.

Currently, I am working on **next-generation hybrid storage engines** and **serverless runtime optimization**.

---

## 🛠 Tech Stack & Arsenal

| Domain           | Technologies                                                 |
| :--------------- | :----------------------------------------------------------- |
| **Languages**    | ![C++](https://img.shields.io/badge/C++-17%2F20-00599C?style=flat-square&logo=c%2B%2B) ![Rust](https://img.shields.io/badge/Rust-Nightly-000000?style=flat-square&logo=rust) ![Go](https://img.shields.io/badge/Go-1.21-00ADD8?style=flat-square&logo=go) ![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=flat-square&logo=python) |
| **Systems**      | ![Linux](https://img.shields.io/badge/Linux-Kernel_5.15+-FCC624?style=flat-square&logo=linux) ![eBPF](https://img.shields.io/badge/eBPF-Observability-FF7139?style=flat-square) ![io_uring](https://img.shields.io/badge/io__uring-Async_I%2FO-white?style=flat-square) |
| **Storage**      | ![RocksDB](https://img.shields.io/badge/RocksDB-LSM_Tree-blue?style=flat-square) ![Redis](https://img.shields.io/badge/Redis-Internals-DC382D?style=flat-square&logo=redis) ![NVMe](https://img.shields.io/badge/NVMe-Direct_I%2FO-green?style=flat-square) |
| **Cloud Native** | ![Kubernetes](https://img.shields.io/badge/K8s-Operator-326CE5?style=flat-square&logo=kubernetes) ![Docker](https://img.shields.io/badge/Docker-Container-2496ED?style=flat-square&logo=docker) ![gRPC](https://img.shields.io/badge/gRPC-Protobuf-244F60?style=flat-square&logo=google) |
| **Tools**        | ![CMake](https://img.shields.io/badge/CMake-Build-064F8C?style=flat-square&logo=cmake) ![GDB](https://img.shields.io/badge/GDB-Debugging-green?style=flat-square) ![Perf](https://img.shields.io/badge/Perf-Profiling-red?style=flat-square) ![Git](https://img.shields.io/badge/Git-VCS-F05032?style=flat-square&logo=git) |

---

## 🚀 Featured Open Source Projects

### 1. [Titan-KV](https://github.com/RikkaCCLC/Titan-KV)

> **High-Throughput Key-Value Separation Storage Engine**
>
> A C++ based embedded storage engine optimized for large value workloads on NVMe SSDs.
>
> - **Core Tech**: `LSM-Tree`, `Key-Value Separation`, `SIMD (AVX2/512)`, `Lock-Free SkipList`.
> - **Innovation**: Reduces write amplification from **50x to 3x** by decoupling keys from values (WiscKey architecture).
> - **Performance**: **210k OPS** (Write) with sub-millisecond P99 latency.

### 2. [FlashKV-Uring](https://github.com/RikkaCCLC/FlashKV-Uring)

> **Async I/O Hybrid Cache Middleware**
>
> A next-gen cache engine written in Rust, leveraging Linux `io_uring` for zero-syscall I/O.
>
> - **Core Tech**: `Rust (Tokio)`, `io_uring (SQPOLL)`, `Direct I/O (O_DIRECT)`, `Slab Allocator`.
> - **Innovation**: Bypasses kernel page cache to achieve **320k+ IOPS** on a single NVMe drive.
> - **Architecture**: Hybrid DRAM (L1) + SSD (L2) hierarchy with **W-TinyLFU** eviction policy.

### 3. [StreamDrift-Monitor](https://github.com/RikkaCCLC/StreamDrift-Monitor)

> **Real-time Concept Drift Detection Engine**
>
> A lightweight Flink plugin for detecting feature drift in high-throughput financial data streams.
>
> - **Core Tech**: `Apache Flink`, `Sketch Algorithms (Count-Min, T-Digest)`, `Probabilistic Data Structures`.
> - **Impact**: Detects model degradation in **<5 minutes** with **<50MB** memory footprint.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=RikkaCCLC&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true" alt="RikkaCCLC's Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RikkaCCLC&layout=compact&theme=tokyonight" alt="Top Languages" />
</p>


## 🔭 Current Focus

- **Kernel Bypass Networking**: Exploring DPDK and XDP for ultra-low latency packet processing.
- **Serverless Cold Start**: Researching snapshot-based (CRIU) restore mechanisms for FaaS platforms.
- **Database Internals**: Diving deep into modern Bw-Tree and concurrent latch-free indexing.

---



Mathematics student Graduated from CSU (Central South University), 2023,  <b>China</b>.
<br>Entrepreneur & Currently working on software development-related entrepreneurial ventures in HongKong.
<br>Focused on developing efficient and scalable systems.
<br>Active contributor to open-source projects.
<br>Currently engaged in projects involving big data technologies and cloud-native solutions.
<br>Feel free to reach out via the social links above. All my contact details for different platforms can be found on my blog.
<br>


<h3>Open source projects</h3>
<table>
  <thead align="center">
    <tr border: none;>
      <td><b>🎁 Projects</b></td>
      <td><b>⭐ Stars</b></td>
      <td><b>📚 Forks</b></td>
      <td><b>🛎 Issues</b></td>
      <td><b>📬 Pull requests</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/RikkaCCLC/Fast-modular-inverse-calculation-function"><b>Fast modular inverse calculation function</b></a></td>
      <td><img alt="Stars" src="https://img.shields.io/github/stars/RikkaCCLC/Fast-modular-inverse-calculation-function?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Forks" src="https://img.shields.io/github/forks/RikkaCCLC/Fast-modular-inverse-calculation-function?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Issues" src="https://img.shields.io/github/issues/RikkaCCLC/Constant-Time-GCD?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Pull Requests" src="https://img.shields.io/github/issues-pr/RikkaCCLC/Constant-Time-GCD?style=flat-square&labelColor=343b41"/></td>
    </tr>
      <tr>
      <td><a href="https://github.com/RikkaCCLC/Titan-KV"><b>Titan-KV</b></a></td>
      <td><img alt="Stars" src="https://img.shields.io/github/stars/RikkaCCLC/Titan-KV?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Forks" src="https://img.shields.io/github/forks/RikkaCCLC/Titan-KV?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Issues" src="https://img.shields.io/github/issues/RikkaCCLC/Titan-KV?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Pull Requests" src="https://img.shields.io/github/issues-pr/RikkaCCLC/Titan-KV?style=flat-square&labelColor=343b41"/></td>
    </tr>
    <tr>
      <td><a href="https://github.com/RikkaCCLC/FlashKV-Uring"><b>FlashKV-Uring</b></a></td>
      <td><img alt="Stars" src="https://img.shields.io/github/stars/RikkaCCLC/FlashKV-Uring?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Forks" src="https://img.shields.io/github/forks/RikkaCCLC/FlashKV-Uring?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Issues" src="https://img.shields.io/github/issues/RikkaCCLC/FlashKV-Uring?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Pull Requests" src="https://img.shields.io/github/issues-pr/RikkaCCLC/FlashKV-Uring?style=flat-square&labelColor=343b41"/></td>
    </tr>
  </tbody>
</table>
<h3>My latest posts</h3>
<ul>
  <li><a href="https://my-bucket-1304946661.cos-website.ap-guangzhou.myqcloud.com/2023/03/17/Ch.2%20LightGBM%E7%9A%84GOSS%E9%87%87%E6%A0%B7%E4%B8%8E%E7%9B%B4%E6%96%B9%E5%9B%BE%E4%BC%98%E5%8C%96%E8%BF%87%E7%A8%8B/"><b>LightGBM core technology: GOSS sampling and histogram optimization algorithm</b></a><br/><i>GOSS sampling and histogram optimization algorithm</i></li>
  <li><a href="https://my-bucket-1304946661.cos-website.ap-guangzhou.myqcloud.com/2023/12/30/LSTM%E4%B8%8EGRU%EF%BC%88%E4%B8%8A%EF%BC%89/"><b> LSTM & GRU </b></a><br/><i>Introduction to the basic principles and architecture of LSTM</i></li>
    <li><a href="https://my-bucket-1304946661.cos-website.ap-guangzhou.myqcloud.com/2023/01/10/%E5%8E%9F%E7%90%86%E8%BF%9B%E9%98%B6%EF%BC%9AXGBoost%E7%9A%84%E6%B1%82%E8%A7%A3%E6%B5%81%E7%A8%8B/"><b> Derivation of the mathematical principles of XGBoost</b></a><br/><i>Basic mathematical process of XGB and derivation of objective function</i></li>
</ul>

------------
<p align="center">This <i>README</i> file is generated <b>every 3 hours</b>!</br>Last refresh: Tuesday, 1 October, 05:11 CEST<br /><a href="https://medium.com/@th.guibert/how-to-create-a-self-updating-readme-md-for-your-github-profile-f8b05744ca91">Create your own here!</a></p>
<p align="center">
  <i>"Talk is cheap. Show me the code." — Linus Torvalds</i>
</p>

