# informative-stuffs-you-may-know-
Here you gonna find informative stuffs in a collection of inspiring lists, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools and more.

<h2>
  📔  What is it?</h2>
<h4>
This list is a collection of various materials that I use every day in my work. It contains a lot of useful information gathered in one piece.</h4>
<h2> 
  For whom?</h2>
<h4>
  This collection is suitable for everyone. It is aimed towards System and Network administrators, DevOps, Pentesters and Security Researchers.</h4>
<h2>💢  Table of Contents</h2>
<h3>Only main chapters:</h3><br>
<ul>
<li>CLI Tools
<li>GUI Tools
<li>Web Tools
<li>Systems/Services
<li>Networks
<li>Manuals/Howtos/Tutorials
<li>Inspiring Lists
<li>Blogs
<li>Hacking/Penetration Testing
<li>Your daily knowledge and news
<li>Other Cheat Sheets
<li>One-liners
</ul>

<h2>CLI Tools  <sub>[TOC]</sub></h2>
<pre> <h3>▪️ Shells</h3><h4>
  🔸 Oh My ZSH! - the best framework for managing your Zsh configuration.
  🔸 bash-it - framework for using, developing and maintaining shell scripts and custom commands for your daily work.
  🔸 Oh My Fish - the Fishshell framework.
▪️ Managers
  🔸 Midnight Commander - visual file manager, licensed under GNU General Public License.
  🔸 screen - full-screen window manager that multiplexes a physical terminal.
  🔸 tmux - terminal multiplexer, lets you switch easily between several programs in one terminal.
  🔸 tmux-cssh - sets a comfortable and easy to use functionality, clustering and synchronizing virtual tmux-sessions.
▪️ Text editors
  🔸 vi - is one of the most common text editors on Unix.
  🔸 vim - is a highly configurable text editor.
  🔸 emacs - an extensible, customizable, free/libre text editor - and more.
▪️ Network
  🔸 nmap - free and open source (license) utility for network discovery and security auditing.
  🔸 masscan - the fastest Internet port scanner, spews SYN packets asynchronously.
  🔸 pbscan - faster and more efficient stateless SYN scanner and banner grabber.
  🔸 hping - command-line oriented TCP/IP packet assembler/analyzer.
  🔸 mtr - functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
  🔸 netcat - networking utility which reads and writes data across network connections, using the TCP/IP protocol.
  🔸 tcpdump - powerful command-line packet analyzer.
  🔸 tshark - dump and analyze network traffic (wireshark cli).
  🔸 ngrep - is like GNU grep applied to the network layer.
  🔸 stenographer - is a packet capture solution which aims to quickly spool all packets to disk.
  🔸 bmon - monitoring and debugging tool to capture networking related statistics and prepare them visually.
  🔸 iptraf-ng - is a console-based network monitoring program for Linux that displays information about IP traffic.
  🔸 iPerf3 - is a tool for active measurements of the maximum achievable bandwidth on IP networks.
  🔸 ethr - is a Network Performance Measurement Tool for TCP, UDP & HTTP.
  🔸 Etherate - is a Linux CLI based Ethernet and MPLS traffic testing tool.
  🔸 Nemesis - packet manipulation CLI tool; craft and inject packets of several protocols.
  🔸 packetfu - a mid-level packet manipulation library for Ruby.
  🔸 Scapy - packet manipulation library; forge, send, decode, capture packets of a wide number of protocols.
  🔸 aria2 - is a lightweight multi-protocol & multi-source command-line download utility.
▪️ Network (DNS)
  🔸 fierce - a DNS reconnaissance tool for locating non-contiguous IP space.
  🔸 sublist3r - fast subdomains enumeration tool for penetration testers.
  🔸 amass - tool obtains subdomain names by scraping data sources, crawling web archives and more.
  🔸 namebench - provides personalized DNS server recommendations based on your browsing history.
  🔸 dnscrypt-proxy 2 - a flexible DNS proxy, with support for encrypted DNS protocols.
▪️ Network (HTTP)
  🔸 Curl - command line tool and library for transferring data with URLs.
  🔸 kurly - is an alternative to the widely popular curl program, written in Golang.
  🔸 HTTPie - a user-friendly HTTP client.
  🔸 wuzz - interactive cli tool for HTTP inspection.
  🔸 htrace.sh - shell script to debugging http/https; ssllabs, mozilla observatory, testssl.sh and nmap nse support.
  🔸 httpstat - visualizes curl statistics in a way of beauty and clarity.
  🔸 Lynx - is a text browser for the World Wide Web.
  🔸 siege - is an http load testing and benchmarking utility.
  🔸 wrk - is a modern HTTP benchmarking tool capable of generating significant load.
  🔸 bombardier - fast cross-platform HTTP benchmarking tool written in Go.
  🔸 gobench - http/https load testing and benchmarking tool.
  🔸 gobuster - free and open source directory/file & DNS busting tool written in Go.
▪️ SSL/Security
  🔸 openssl - is a robust, commercial-grade, and full-featured toolkit for the TLS and SSL protocols.
  🔸 gnutls-cli - client program to set up a TLS connection to some other computer.
  🔸 sslyze - fast and powerful SSL/TLS server scanning library.
  🔸 sslscan - tests SSL/TLS enabled services to discover supported cipher suites.
  🔸 testssl.sh - testing TLS/SSL encryption anywhere on any port.
  🔸 spiped - is a utility for creating symmetrically encrypted and authenticated pipes between socket addresses.
  🔸 Certbot - is EFF's tool to obtain certs from Let's Encrypt and (optionally) auto-enable HTTPS on your server.
  🔸 mkcert - simple zero-config tool to make locally trusted development certificates with any names you'd like.
▪️ Auditing Tools
  🔸 Lynis - battle-tested security tool for systems running Linux, macOS, or Unix-based operating system.
  🔸 LinEnum - scripted Local Linux Enumeration & Privilege Escalation Checks.
  🔸 Rkhunter - scanner tool for Linux systems that scans backdoors, rootkits and local exploits on your systems.
  🔸 PE-sieve - is a light-weight tool that helps to detect malware running on the system.
▪️ System Diagnostics/Debuggers
  🔸 strace - diagnostic, debugging and instructional userspace utility for Linux.
  🔸 DTrace - is a performance analysis and troubleshooting tool.
  🔸 ltrace - is a library call tracer, used to trace calls made by programs to library functions.
  🔸 sysdig - system exploration and troubleshooting tool with first class support for containers.
  🔸 Valgrind - is an instrumentation framework for building dynamic analysis tools.
  🔸 glances - cross-platform system monitoring tool written in Python.
  🔸 htop - interactive text-mode process viewer for Unix systems. It aims to be a better 'top'.
  🔸 atop - ASCII performance monitor. Includes statistics for CPU, memory, disk, swap, network, and processes.
  🔸 lsof - displays in its output information about files that are opened by processes.
  🔸 FlameGraph - stack trace visualizer.
  🔸 lsofgraph - small utility to convert Unix lsof output to a graph showing FIFO and UNIX interprocess communication.
  🔸 hexyl - a command-line hex viewer.
▪️ Log Analyzers
  🔸 angle-grinder - slice and dice log files on the command line.
  🔸 lnav - log file navigator with search and automatic refresh.
  🔸 GoAccess - real-time web log analyzer and interactive viewer that runs in a terminal.
  🔸 ngxtop - real-time metrics for nginx server.
▪️ Databases
  🔸 usql - universal command-line interface for SQL databases.
  🔸 pgcli - postgres CLI with autocompletion and syntax highlighting.
  🔸 mycli - terminal client for MySQL with autocompletion and syntax highlighting.
▪️ TOR
  🔸 Nipe - script to make Tor Network your default gateway.
  🔸 multitor - a tool that lets you create multiple TOR instances with a load-balancing.
▪️ Other
  🔸 incron - is an inode-based filesystem notification technology.
  🔸 GRV - is a terminal based interface for viewing Git repositories.
  🔸 tldr - simplified and community-driven man pages.
  🔸 commander.js - minimal CLI creator in JavaScript.</h4></pre> <br>
  <h2>GUI Tools</h2>
  
