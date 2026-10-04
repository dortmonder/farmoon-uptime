# farmoon-uptime

External health monitor for Farmoon. A GitHub Actions workflow probes the public sites and TLS
certificates every 5 minutes from GitHub's network. On failure it opens a single `outage` issue
(GitHub e-mails the owner); on recovery it closes it. It uses no secrets and only public URLs.
