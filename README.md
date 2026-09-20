iosentry: sysadmin / dev / builder / maker && breaker of both hard & soft-warez

My name is Roman I spend the majority of my free time researching a wide variety or topics related to computer and information security. I have a particular interest in IoT 
security, the weaponization of "smart devices", and system security models utilizing virtualization to effectively implement deep compartmentalization and system component isolation.

Secure Boot, Intel TXT, BootGuard / Managed Boot, Trusted Platfotm Module utilization, integration, optimization and attack surface audit and analysis are my forte. Exploration of root-of-trust as attack surface has been the focal point of my recent work.

Creating computing environments tolerant of Ring 0 exploitation of OS code using immutable images, virtualized IO and memory management of individual aggregate systems via type-1 hardware virtualization running in Ring -1 (Xen Project) is of great interest to me. 
In particular, hardening of the Dom0 Administrative Control Domain is ongoing work as can be seen in my XenUKI (experimental) which can boot a customized PE32+ EFI executable containing all components of the hypervisor and its host Domain 0 in a monolithic cryptographicly sign-able Secure Boot compliant Unified kernel Image.See repository XenUKI for an experimental but functional example that utilizes LVM on LUKS for disk encryption.

IAM obsessed with authentication mechanisms...
Not only their analysis and exploitation, but their design and implementation as well. I have built robust custom authentication mechanisms for heterogeneous 
research computing environments compliant to HIPAA regulatory control. One such system providing highly parallel and redundant authentication servers and storage arrays providing automated client and lab equipment data and configuration backup services still in use at Massachusetts General Hospital / Harvard Medical School's Cutaneous Biology Research Center (CBRC). This system utilizes highly customized LDAP schema customized with SAMBA, PAM, OpenLDAP, NFS, ZFS (COW), rsync, and drbd to provide "roaming profile" service to client workstations and laptops regardless of the installed client OS. Authentication services for OSX, Windows, and Linux clients is facilitated by the aforementioned LDAP back-ends. Distributed Replicated Block Devices (drbd) and rsync are utilized to broadcast writes to multiple storage NAS arrays and their associated front end servers running both Linux (CentOS/Debian) and Solaris HA clusters, safeguarding against OS compromise through architecture diversification. 

I also enjoy working with Open Weight LLM's quantized to run locally on mid-grade GPU's (8GB VRAM min.) which are customized to perform comprehensive system monitoring, maintenance, and reporting for use by organizations with highly confidential IP to protect and/or regulatory conpliance considerations. 

I have been known to dance with the Intel Management Engine (ME) but we don't talk about that just anywhere. 

<!---
IO-sentry/IO-sentry is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
