---
date: '1'
title: 'Fault-Tolerant Distributed System'
cover: './fault_tolerant.png'
# github: 'https://github.com/bchiang7/halcyon-site'
# external: 'https://halcyon-theme.netlify.com/'
tech:
  - Go
  - gRPC
---

- Implemented a distributed file storage system similar to Dropbox, with support for concurrent read/write accesses from   multiple clients, and CRUD/Sync operations on the files. Integrated the RAFT consensus protocol to make the system resilient to the failure of 50% of the servers.
