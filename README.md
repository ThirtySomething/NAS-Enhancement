[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![made-with-docker](https://img.shields.io/badge/Made%20with-Docker-1f425f.svg)](https://www.docker.com/)

# NAS-Enhancement

How to keep an older NAS with a small server in front.

## Baseline

I'm running at home a small [NAS][NAS]. This NAS is released in 2011 which is
quite very long time ago thinking in computer age.

## The purpose

The purpose of this project is to use an [ZBox ID 41+][ZBox] as server in front
of the NAS. The LaTeX document describes the long journey from the idea up to
hopefully a happy end.

## ToDo's

- Check if there is a way to use SMB/NFS instead of iSCSI.
- Figure out how to setup the Samba Server -- maybe shares could be used in Docker container.
- Gather more experience with
  - [ClamAV][ClamAV]
  - [MinIO][MinIO]
  - [Syncthing][Syncthing]
  - [restic][restic]
- Maybe it's neccessary to compose for each service an own Docker container.

[ClamAV]: https://www.clamav.net
[MinIO]: https://docs.min.io
[NAS]: https://www.synology.com/en-global/company/news/article/Synology_Unveils_DiskStation_DS411slim
[Syncthing]: https://syncthing.net
[ZBox]: https://www.zotac.com/ua/product/mini_pcs/id41-plus
[restic]: https://restic.net
