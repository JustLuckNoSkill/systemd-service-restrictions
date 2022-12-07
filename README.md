# systemd-service-restrictions

These are override files to restrict what systemd services can do and access. As far as I can tell, they introduce no breakage. Override files are located in `/etc/systemd/system/<service name>.d/`. Madaidan's [Linux Hardening Guide](https://madaidans-insecurities.github.io/guides/linux-hardening.html#systemd-service-sandboxing) explains what these sandboxing options do.
