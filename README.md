# UFW Application Profiles for UFW

Repository contained my application profiles for several applications for using in UFW on VPN-server

For using simple copy files from `profiles/` directory to `/etc/ufw/applications.d/`. Then reload profiles:

    ufw reload

And activate profiles as needed:

    ufw allow vpn

Done.
