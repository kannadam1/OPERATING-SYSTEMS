Project Overview

This coursework focuses on configuring, securing, and evaluating the performance of a Linux server system using a dual-system architecture. The project is designed to develop practical Linux system administration skills, command-line proficiency, and an understanding of security and performance trade-offs in operating systems.

The server runs a headless Linux distribution (Ubuntu Server) and is administered remotely via SSH from a workstation system. This setup reflects industry-standard practices for cloud and server administration.

Objectives

Deploy a Linux server and manage it entirely from the command line.

Implement and verify security controls, including SSH hardening, firewall configuration, AppArmor, fail2ban, and automatic updates.

Select and install applications representing different workloads for performance evaluation.

Monitor CPU, memory, disk I/O, network performance, and service response times.

Analyse system behaviour under different workloads and apply optimisation strategies.

Conduct a security audit and system evaluation using Lynis, nmap, and service access checks.

Document all work, commands, scripts, and findings in a weekly GitHub journal with screenshots and explanations.

Learning Outcomes

Develop proficiency in Linux server administration and remote system management.

Apply security best practices to protect systems from potential threats.

Analyse and interpret system performance metrics to identify bottlenecks.

Create reproducible scripts for security verification and remote monitoring.

Communicate technical implementations effectively through documentation and demonstrations.

Tools and Technologies

Server OS: Ubuntu Server (headless)

Workstation: Linux Desktop VM, host machine, or hybrid setup

Virtualisation: Oracle VirtualBox

Security Tools: AppArmor, fail2ban, Lynis, ufw (firewall), SSH key-based authentication

Monitoring Tools: top, htop, iostat, ifstat, iperf3, Apache Benchmark (ab)

Scripting: Bash scripts for automation and monitoring

Documentation: GitHub Pages with weekly journals, screenshots, and explanations

Coursework Structure

The project is completed in 7 weekly phases:

System Planning and Distribution Selection – OS choice, architecture diagram, network setup, system specs.

Security Planning and Testing Methodology – Security baseline, threat modelling, performance testing plan.

Application Selection for Performance Testing – Choosing CPU, RAM, disk, network-intensive applications.

Initial System Configuration & Security Implementation – SSH key authentication, firewall rules, user management.

Advanced Security and Monitoring Infrastructure – AppArmor, fail2ban, automatic updates, verification and monitoring scripts.

Performance Evaluation and Analysis – Testing applications, collecting metrics, analysing performance, applying optimisations.

Security Audit and System Evaluation – Lynis audit, network scans, access control verification, service and configuration review.

Deliverables

Technical Journal: Weekly GitHub Pages documenting commands, screenshots, scripts, and reflections.

Recorded Demonstration: 8-minute video demonstrating system configuration, security verification, and performance monitoring.

Scripts: Automated Bash scripts for security checks (security-baseline.sh) and remote performance monitoring (monitor-server.sh).

Conclusion

This project integrates system administration, security, and performance evaluation in a realistic Linux environment. It provides hands-on experience with professional server management, security auditing, and performance analysis, preparing students for cloud, DevOps, and cybersecurity roles.
