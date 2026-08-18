# Fun Weekend Projects

A growing portfolio of hands-on IT, networking, infrastructure, automation, and cybersecurity projects designed to be completed over a weekend and documented from planning through lessons learned.

## About This Project Series

The goal of **Fun Weekend Projects (FWP)** is to continuously build practical technical skills through small, focused projects that solve real problems and demonstrate real-world engineering and IT concepts.

Each project is documented so that someone reviewing my GitHub can see not only the final result, but also how I planned, implemented, tested, troubleshot, and improved the solution.

## Project Workflow

Each project generally includes:

1. **Project Goal** — What I am trying to build or solve
2. **Requirements** — Hardware, software, tools, and prerequisites
3. **Design** — Architecture, network diagrams, and implementation plan
4. **Build** — Step-by-step configuration and deployment
5. **Testing** — Validation of functionality and expected behavior
6. **Troubleshooting** — Problems encountered and how they were resolved
7. **Security Review** — Security considerations and improvements where applicable
8. **Lessons Learned** — Key technical takeaways
9. **Documentation** — Screenshots, diagrams, configurations, and supporting notes

## Project Index

| ID | Project | Status | Skills / Technologies |
|---|---|---|---|
| **FWP-001** | **[OPNsense Home Firewall](https://github.com/tiwaolagbaju/FWP-001-opnsense-home-firewall)** | ✅ Complete | OPNsense, TCP/IP, IPv4/IPv6, DHCP, DNS, Firewall Policy, Network Security, Troubleshooting |
| FWP-002 | Coming Soon | ⏳ Planned | TBD |
| FWP-003 | Coming Soon | ⏳ Planned | TBD |

## FWP-001 — OPNsense Home Firewall

**Status:** ✅ Complete

Replaced my ISP-provided router with a dedicated OPNsense firewall/router running on an x86-64 mini PC. The project covered isolated lab validation, direct ISP cutover, DNS and firewall hardening, native IPv4/IPv6, MFA-protected administration, encrypted upstream DNS, DNS-bypass controls, performance benchmarking, external WAN exposure testing, rollback planning, and real-world troubleshooting.

**Result:** OPNsense is now the production edge router/firewall while maintaining near-gigabit performance with no meaningful latency increase. Wired and wireless clients passed final production validation, and an external IPv4 service-port scan found no open TCP ports in the tested range.

**Skills:** `OPNsense` · `TCP/IP` · `IPv4/IPv6` · `DHCP` · `DNS` · `DNSSEC` · `DNS-over-TLS` · `Firewall Policy` · `Network Security` · `Performance Testing` · `Troubleshooting` · `Change/Rollback Planning`

**[View the full FWP-001 project →](https://github.com/tiwaolagbaju/FWP-001-opnsense-home-firewall)**

## Areas I Plan to Explore

Future weekend projects may include:

- Network monitoring and logging
- VLAN segmentation
- VPN deployment
- Intrusion detection and prevention
- Linux administration
- Docker and containerization
- Home lab virtualization
- Python automation
- SCADA and industrial automation
- Modbus communications
- DCIM and data center infrastructure
- Cloud infrastructure
- Cybersecurity labs

## Documentation Philosophy

These projects are intentionally documented as engineering projects rather than just finished demos. I want each repository to show the thought process behind the implementation, including design decisions, tradeoffs, troubleshooting, testing, and improvements.

## About Me

I'm **Tiwa Olagbaju**, a Critical Power Systems Engineer and IT professional with more than 10 years of experience supporting mission-critical data center infrastructure. I'm using these projects to expand my hands-on experience across networking, automation, SCADA, cybersecurity, cloud, and modern IT infrastructure.

---

**Follow the repository to see new projects added to the Fun Weekend Projects series.**
