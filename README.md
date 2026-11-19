# AIPICORA model files

Model files that the AIPICORA app can download (optional) to search photos by
description **on the phone**. Photos, faces and search words never leave the
device; the app only downloads these files.

Downloads are on the [Releases](../../releases) page. The app checks every
file against its SHA-256 checksum (see `SHA256SUMS.txt`) before using it.

| Release | File | Size | What it is |
|---|---|---|---|
| search-1 | `siglip2_vision_int8.onnx` | 94.6 MB | Google SigLIP 2 base image encoder, int8 ONNX |
| search-1 | `search_table_wordnet_1.bin` | 20.2 MB | Word and phrase table built from WordNet 3.0 |

## Licences

- SigLIP 2: Apache License 2.0 (`LICENSE-APACHE-2.0.txt`).
- WordNet 3.0 Copyright 2006 by Princeton University. All rights reserved.
  WordNet licence and disclaimer in `LICENSE-WORDNET.txt`.

See `NOTICE.txt` for details. The AIPICORA app itself is not in this repository.
