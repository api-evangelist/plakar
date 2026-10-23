---
title: "Backing up kubernetes clusters with Plakar"
url: "https://www.plakar.io/posts/2026-02-18/backing-up-kubernetes-clusters-with-plakar/"
date: "2026-02-18"
feed_url: "http://plakar.io/posts/index.xml"
---
We built a Kubernetes integration for Plakar that backs up clusters at three levels: etcd (disaster recovery), manifests (granular restore and inspection), and persistent volumes (via CSI snapshots). This enables full cluster recovery, fine-grained restores, and data portability across environments.
