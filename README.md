# Ricky Raihan Azhari

**Infrastructure Engineer** transitioning from telecom automation to payment systems.

## About

Infrastructure engineer with production experience in high-availability telecom 
systems (60K+ devices, 99.9% uptime). Now applying distributed systems expertise 
to payment infrastructure—settlement engines, multi-currency ledgers, and 
cross-border payment rails.

## Payment Infrastructure Projects

### 🌏 [kovra](https://github.com/rickyraz/corridor)
**Cross-border remittance platform** | *Active development*

End-to-end remittance application: FX conversion, compliance screening, 
ISO 20022 messaging, real-time tracking. Built on TigerBeetle for 
atomic multi-currency settlement.

**Tech:** Go · PostgreSQL · Redis · TigerBeetle  
**Features:** 9-state transaction flow, OFAC screening, FX rate locking, 
WebSocket updates, admin dashboard

<!--   ### 🔧 [spectrum](https://github.com/rickyraz/spectrum) -->
### 🧵 sutera
**Settlement engine** | *Planned*

HTLC-based atomic settlement inspired by BIS Project Icebreaker and 
mBridge. Designed to replace TigerBeetle dependency in corridor with 
custom-built ledger engine.

**Tech:** Zig · Go  
**Scope:** Storage engine, WAL, HTLC state machine, multi-ledger coordination

<!-- ### 🔨 [zcobol](https://github.com/rickyraz/zcobol)  -->
### 🔨 zcobol
**Safe COBOL-Zig interop** | *Research*

Financial primitives enabling safe interop between COBOL and Zig. Preserves exact 
COBOL semantics (COMP-3 decimals, packed formats, EBCDIC) at native performance 
for gradual mainframe modernization.

**Approach:** Direct type mapping + compile-time verification (inspired by CXX's C++-Rust interop)  
**Status:** COMP-3 arithmetic implementation, layout verification research  
**Vision:** Production-ready interop toolkit by 2027

**Why it matters:** 800B+ lines of COBOL in production (up from 220B in 2017), 
43% of banking systems. Traditional migration approaches carry extreme risk and cost:
- Commonwealth Bank: 5 years, $750M
- TSB Bank: £427M+ in direct losses and fines, 5.2M customers affected
- Big IT project failure rate: 50-80%

zcobol enables keeping battle-tested COBOL business logic while adding modern 
components incrementally—avoiding big-bang rewrites.

**Tech:** Zig + C ABI bridge  
**Use cases:** Settlement file processing, batch reconciliation, mainframe integration

<!-- [Volt](https://github.com/rickyraz/volt) 
<!-- ### ⚡ volt - message broker [Planned]
Persistent queue in Zig for payment event streaming. Designed for 
mainframe-to-cloud integration patterns.

Status: Architecture research | Start: 2028
Tech: Zig, RocksDB
  -->
## Professional Experience

**Software Engineer** | Network Automation  
*2022 - Present*

Production automation for fiber networks: 60K+ ONUs, 310+ OLT devices.
Built provisioning systems, monitoring dashboards, incident platform.

**Tech:** TypeScript · Go · Redis · PostgreSQL  
**Scale:** 99.9% uptime, real-time telemetry, legacy API integration

## Open To

Backend/infrastructure roles in payment systems. 
Singapore · Remote · Open to relocation.

## Contact

**Email:** rickyraihan83@gmail.com  
**LinkedIn:** [linkedin.com/in/rickyraz](https://linkedin.com/in/rickyraz)  
**Location:** Jakarta, Indonesia


## Stats

[![GitHub Streak](https://streak-stats.demolab.com/?user=rickyraz&theme=dark&hide_border=true)](https://git.io/streak-stats)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rickyraz&layout=compact&theme=dark&hide_border=true&hide=html,css,scss,cmake,mdx,php)](https://github.com/rickyraz)

<sub>All projects are learning exercises. I write about challenges and decisions as I go. Quality over features.</sub>
