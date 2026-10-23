---
title: "Audit of Plakar cryptography"
url: "https://www.plakar.io/posts/2025-02-28/audit-of-plakar-cryptography/"
date: "2025-02-28"
feed_url: "http://plakar.io/posts/index.xml"
---
Independent cryptographic audit of Plakar by Jean-Philippe Aumasson confirming a sound overall design, with recommendations to modernize components. Key improvements include switching to Argon2id for password hashing, AES-GCM-SIV for chunk encryption, AES-KW for key wrapping, and replacing SHA-256 digests with keyed BLAKE3 MACs. No major security issues were found, and follow-up review validated the updated architecture, algorithms, and implementation.
