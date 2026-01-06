# More Linux Distributions

> Retrieved on 2025-12-25 by Keming He from [Google Cybersecurity Certificate - Course 4 - Module 2 - More Linux Distributions](https://www.coursera.org/learn/linux-and-sql/supplement/wJh3U/more-linux-distributions)

## Introduction

Previously, you were introduced to the different distributions of Linux. This included KALI LINUX™. (KALI LINUX™ is a trademark of OffSec.) In addition to KALI LINUX™, there are multiple other Linux distributions that security analysts should be familiar with. In this reading, you’ll learn about additional Linux distributions.

## Debian vs. RHEL (Red Hat® Enterprise Linux®) Comparison

| Feature | Parrot / Kali (Debian) | AlmaLinux (Red Hat) |
| :--- | :--- | :--- |
| Package Manager | `apt` (Advanced Package Tool) | `dnf` (Dandified YUM) |
| Package Format | `.deb` | `.rpm` (Red Hat Package Manager) |
| Security Module | AppArmor (commonly) | SELinux (Security-Enhanced Linux) |
| Focus | Pentesting / Desktop | Server Stability / Enterprise Security |

## Debian-Based Linux Distributions

### [KALI LINUX™](https://www.kali.org/)

KALI LINUX™ is an open-source distribution of Linux that is widely used in the security industry. This is because KALI LINUX™, which is Debian-based, is pre-installed with many useful tools for penetration testing and digital forensics. A penetration test is a simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes. Digital forensics is the practice of collecting and analyzing data to determine what has happened after an attack. These are key activities in the security industry.

However, KALI LINUX™ is not the only Linux distribution that is used in cybersecurity.

### [Ubuntu](https://ubuntu.com/)

Ubuntu is an open-source, user-friendly distribution that is widely used in security and other industries. It has both a command-line interface (CLI) and a graphical user interface (GUI). Ubuntu is also Debian-derived and includes common applications by default. Users can also download many more applications from a package manager, including security-focused tools. Because of its wide use, Ubuntu has an especially large number of community resources to support users.

Ubuntu is also widely used for cloud computing. As organizations migrate to cloud servers, cybersecurity work may more regularly involve Ubuntu derivatives.

### [Parrot](https://www.parrotsec.org/)

Parrot is another open-source distribution commonly used for security. Similar to KALI LINUX™, Parrot comes with pre-installed tools related to penetration testing and digital forensics. It has both GUI and CLI.

Parrot is often considered more "lightweight" and is designed to be used as a daily-driver OS (with a home edition), whereas Kali is primarily optimized for penetration testing environments and is less commonly used as a general-purpose daily driver.

## Red Hat® Enterprise Linux®-Based Linux Distributions

### [Red Hat® Enterprise Linux®](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux)

Red Hat Enterprise Linux is a subscription-based distribution of Linux built for enterprise use. Red Hat is not free, which is a major difference from the previously mentioned distributions. Because it’s built and supported for enterprise use, Red Hat also offers a dedicated support team for customers to call about issues.

### [AlmaLinux](https://almalinux.org/)

AlmaLinux is a community-driven Linux distribution that was created as a stable replacement for CentOS. CentOS was an open-source distribution that is closely related to Red Hat, and its final stable release, CentOS 8, was in December 2021. CentOS used source code published by Red Hat to provide a similar platform. AlmaLinux is designed to be a drop-in replacement for CentOS 8. This ensures that applications and configurations that worked on CentOS will continue to function on AlmaLinux.

## Key Takeaways

KALI LINUX™, Ubuntu, Parrot, Red Hat, and AlmaLinux (a community-supported replacement for CentOS) are all widely used Linux distributions. It's important for security analysts to be aware of these distributions that they might encounter in their career.
