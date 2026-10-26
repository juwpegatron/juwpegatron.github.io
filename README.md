# AIRIZ Console legacy update feed

This repository only keeps automatic updates working for AIRIZ Console 1.1.0
installations, which were built before the project moved to
[juw12/projects](https://github.com/juw12/projects).

- Legacy feed: `https://juwpegatron.github.io/projects/airiz-motor/updates/windows/latest.yml`
- Current feed: `https://juw12.github.io/projects/airiz-motor/updates/windows/latest.yml`

The legacy feed offers the same installer and SHA-512 hash as the current release.
It uses the former `github.com/juwpegatron/projects/releases/download/` address
because 1.1.0 only accepts that address; GitHub redirects it to `juw12/projects`.

Do not create a new `juwpegatron/projects` repository: it would break that redirect.
This repository can be removed after existing 1.1.0 installations have updated.
