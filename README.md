# Secure Arch

**Evolution in Security Simplification:**
Secure Arch fine-tunes security for a smoother digital ride. Its mission: top-tier security accessible to all, with intuitive interfaces for every user.

**Hyprland Compositor Magic:**
The secret? Hyprland Compositor's desktop-like magic caters to both newbies and tech wizards, offering a seamless transition between graphical, text-based, and command-line interactions.

**Out-of-the-Box Versatility:**
Secure Arch is a security Swiss Army knife with Guix, Nix, and Flatpak. It's a pre-configured setup, empowering users with advanced security measures without tech jargon.

### Arch vs. Artix

Our choice of Arch over Artix prioritizes security and stability, aligning with stringent criteria. While Artix excels in speed, Secure Arch focuses on a comprehensive balance beyond speed, ensuring resilience and reliability.

## Community and Contributions

Yes, there's a [Discord](https://discord.com/invite/GTeVsV2vZd) and a [Reddit](https://www.reddit.com/r/secure_arch/s/HW96w6ZWvd).

We welcome contributions! Make a pull request on GitHub, fostering collaboration and enhancing our open-source project.

# Development Notes

Secure Arch prioritizes security over raw speed, designed to be lightweight yet fortified against vulnerabilities. The roadmap includes phasing out systemd for enhanced efficiency and speed, maintaining security measures.

The decision to remove systemd aims to fine-tune the balance between performance and security, ensuring optimal speed without compromising robust security.

Collaborating with ALHP and CachyOS repositories enriches software options without shared governance. Secure Arch remains independent, committed to security, and embraces collaborative efforts for a versatile software ecosystem.

## Development Goals

Secure Arch aims to be secure by default, fast, and user-friendly. Developers challenge conventional Linux paradigms for a more secure and innovative user experience.

# Disk Layout and Security Measures

Full disk encryption and TPM during boot fortify security, ensuring a robust defense mechanism. Secure Boot adds security layers, but the overall strategy includes encryption, TPM, and vigilant monitoring.

## Network Configuration and Init Systems

The choice between Wicked and Network Manager is pending, considering factors like integration, scalability, and compatibility. Initially implementing systemd, Secure Arch explores alternative init systems for flexibility and tailored approaches.

## UKIs and Kernel Fusion

Utilizing a UKI based on the Linux-hardened kernel enhances security, drawing inspiration from the Linux-zen kernel. The fusion aims for a tailored kernel, prioritizing security, performance, and adaptability in our system architecture.