# SEDeb

In this project, we explore A
- Hardened Debian Installation and,
- Virtualization setup

The design is minimalistic by concept,reducing attack surface, 
providing maximun compatibility& configurability, but
finally and most importantly, providing easy to audit Code.

The setup consists of a Base Debian OS (HOST),
A VM used for networking& Routing (WALLVM),
and VMs used for all activities (VMn), based on a secure
always Offline Image.

The core Concept & Target is for the User to;
- A) *Safely* reproduce the final design using basic documentation,
        template .confs and common sense.
- B) *Comfortably* execute Preconfigured scripts, designed to harden
        security & Configure System/ Packages.
And the Developer to;
- Contribute to the project, raise security standards and 
Give to the Community !

This Project is by no means a "Secure Solution" !
It is what I hope to be an open, community driven platform for
Debian (& Linux) Security Enchantments ( Thus Name ).

The Project is greatly Inspired by the teams of;
- QubesOS, 
- Whonix, 
- Tails, 
- and RiseUp.net
The incorporation of TOR is also crucial, as is in any "Secure System" today.

