# SEDeb

In this project, we explore a:
- Hardened Debian Installation and,
- Virtualization setup
The design is minimalistic by concept,reducing attack surface,
providing maximun compatibility& configurability, but
finally and most importantly, providing easy to audit code.

The setup consists of a Base system (HOSTVM) and
1 VM, used for networking& Routing (WALLVM), and
VMs, used for all activities (VMn), based on a secure;
Always Offline Image.

The core concept& target is for the user to be able to either:
- A) *Safely* reproduce the final design, using basic documentation,
        template .confs and common sense.
- B) *Comfortably* execute preconfigured scripts, designed to harden
        security& Configure System/ Packages.

This Project is by no means a "Secure Solution" !
It is what I hope to be an open, community driven platform for
Debian (& Linux) Security Enchantments ( Thus Name ).

The Project is also Inspired by the teams of QubesOS and Whonix
containing also work from them, and the TOR team as well.

