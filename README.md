# Stainless Linux

Stainless Linux is an independent, community driven Linux distribution focused on technical clarity, long term hardware support, and freedom from corporate influence. The project is in early planning. Volunteers are welcome.

## Vision
Provide a practical, maintainable operating system that prioritizes engineering and hardware longevity. Keep the project community controlled and avoid unnecessary complexity.

## Goals
1. Independent kernel fork
   - Fork the Linux kernel to preserve a clean, auditable, community driven codebase.
   - Remove corporate driven changes that compromise independence.
   - Replace Rust components with C implementations.
   - Preserve upstream hardware support.

2. Full 32-bit support
   - Restore and maintain full 32-bit compatibility.
   - Fork or reimplement software that has dropped 32-bit support.
   - Keep older hardware usable and secure.

3. Unified 64-bit support
   - Treat x86_64 as a single architecture.
   - Avoid artificial segmentation of 64-bit hardware.

4. X11 graphics stack
   - Remove Wayland and related dependencies.
   - Support X11 servers such as xlibre.

5. Practical hardware support
   - Allow proprietary firmware and binary drivers when required for real hardware use.
   - Maintain hardware support with the upstream kernel.
   - Avoid breaking functionality for ideological reasons.

6. Code focused development
   - Keep development focused on code, engineering, and collaboration.
   - No political tests or ideological gatekeeping.

## What we need
- Kernel developers: strong C, kernel internals, revert Rust to C.
- Package maintainers: patch, fork, or port software to restore 32-bit support.
- System architects: design distro layout, build systems, packaging.
- Documentation writers: specs, contributor guides, technical docs.
- Testers: validate builds on 32-bit and 64-bit hardware.

## How to contribute
- Star the repository to follow progress.
- Open an issue to introduce yourself or propose ideas.
- Join discussions about architecture and planning.
- Submit code, documentation, or testing when development begins.

## No CoC
This project does not maintain a code of conduct. Contributors are expected to act like responsible adults, focus on code and collaboration, and treat others with basic respect. Harassment and abuse are not acceptable and will be addressed firmly.

## License
Stainless Linux is licensed under GPLv2.
