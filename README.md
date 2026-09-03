# Fun Weekend Projects

This is where I document small technical projects I build outside of work to keep learning, experiment with new tools, and turn ideas into something I can actually test.

My professional background is in mission-critical power and data center infrastructure, and I also have a degree in Information Technology. These projects are a way for me to bring those two sides of my experience together while building deeper hands-on skills in networking, automation, Linux, local AI, cybersecurity, and software development.

I try to document more than just the finished result. When it adds value, I include the decisions I made, problems I ran into, how I tested the solution, and what I would improve next.

> Public documentation is intentionally sanitized. Credentials, addresses, device identifiers, private configuration data, and other unnecessary operational details are not published.

## Projects

| Project | Status | What it demonstrates |
|---|---|---|
| **[FWP-001 — OPNsense Home Firewall](https://github.com/tiwaolagbaju/FWP-001-opnsense-home-firewall)** | ✅ Complete | Networking, IPv4/IPv6, DNS, firewall policy, security hardening, testing, troubleshooting |
| **[FWP-002 — UPS Maintenance Bypass Training Simulator](https://github.com/tiwaolagbaju/FWP-002-ups-training-simulator-portfolio)** | 🧪 Public test build | Domain-driven software development, training design, interactive simulation, web development, security-conscious application design |
| **[FWP-003 — Cost-Optimized Local AI Server](https://github.com/tiwaolagbaju/FWP-003-local-ai-server)** | 🔧 In progress | Linux, local AI infrastructure, multi-GPU compute, hardware integration, benchmarking, cost/performance engineering |

## FWP-001 — OPNsense Home Firewall

I replaced an ISP-provided router with a dedicated OPNsense firewall and treated the migration like a small production change rather than a simple hardware swap.

That meant building and testing the new environment in stages, validating IPv4 and IPv6, hardening DNS and firewall behavior, benchmarking performance, planning a rollback path, and troubleshooting several unexpected issues during the cutover.

The final system maintained near-gigabit performance while giving me much more control over routing, DNS, security policy, and future network segmentation.

**Skills:** `OPNsense` · `TCP/IP` · `IPv4/IPv6` · `DHCP` · `DNS` · `DNSSEC` · `Firewall Policy` · `Network Security` · `Troubleshooting` · `Change Planning`

[View FWP-001 →](https://github.com/tiwaolagbaju/FWP-001-opnsense-home-firewall)

## FWP-002 — UPS Maintenance Bypass Training Simulator

This project started with a problem I have seen during more than a decade working around critical-power systems: junior technicians can learn procedures from documents, but there is limited opportunity to safely practice the decision-making behind those procedures.

I used my UPS field experience, software-development background, and AI-assisted development tools to build an interactive browser-based simulator where a trainee can work through a simplified maintenance-bypass scenario and immediately see how system state changes in response to their actions.

The public version is a testing build. The underlying implementation and detailed training logic are being treated separately from the portfolio material because this project may be developed into a licensable training product.

**Skills:** `JavaScript` · `Web Development` · `Interactive Simulation` · `Technical Training` · `Application Security` · `Domain Modeling` · `AI-Assisted Development`

[View the FWP-002 portfolio showcase →](https://github.com/tiwaolagbaju/FWP-002-ups-training-simulator-portfolio)  
[Try the public test build →](https://criticalpowertraining.com/)

## FWP-003 — Cost-Optimized Local AI Server

The goal of this build is to see how much useful local-AI capability I can get from carefully selected used enterprise hardware instead of buying a new high-end AI workstation.

The system is being built around two 32 GB AMD Radeon Pro V620 GPUs for 64 GB of aggregate VRAM. I am documenting the hardware integration, Linux configuration, cooling, multi-GPU inference testing, model performance, and total cost so I can evaluate the build on capability per dollar rather than specifications alone.

**Skills:** `Linux` · `Local AI` · `GPU Compute` · `Multi-GPU` · `Docker` · `Vulkan/ROCm` · `Hardware Integration` · `Benchmarking` · `Cost Engineering`

[View FWP-003 →](https://github.com/tiwaolagbaju/FWP-003-local-ai-server)

## What I’m Building Toward

The projects will continue to expand into areas such as:

- network segmentation and monitoring
- Linux and containerized services
- local AI and agentic workflows
- industrial automation, SCADA, and Modbus
- data center infrastructure software and DCIM
- cloud infrastructure
- cybersecurity labs
- practical automation tools

## About Me

I’m **Tiwa Olagbaju**, a critical-power and data center infrastructure professional with more than 10 years of field experience and a background in Information Technology. I enjoy troubleshooting complex systems, learning how the pieces fit together, and building practical tools that solve real problems.

This portfolio is a record of that process.