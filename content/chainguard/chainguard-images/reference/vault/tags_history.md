---
title: "vault Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the vault Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-03 00:46:08
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/vault/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/vault/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/vault/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/vault/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 2nd     | `sha256:a873af234cad221782367bad58e8a262a44048f68c04e1a07f7f7f735f8dbfb2` |
|  `latest`     | May 31st     | `sha256:27f8bd7517d7df0d6748e1ccd8d75e0d49cb3a9a5ea345968ae94fc03839199d` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                       | Last Changed | Digest                                                                    |
|-----------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `1.15.8-dev` `1.15-dev`                      | June 1st     | `sha256:3242a19eaa0355ccaf3cd02a48a001609e0012bb956756648be845554ceaa44a` |
|  `latest-dev` `1.16.2-dev` `1.16-dev` `1-dev` | June 1st     | `sha256:85725e757f182bc6867f8d3bfd667c06df6f3ea19bedf502002088fed57ac045` |
|  `1.14.12-dev` `1.14-dev`                     | June 1st     | `sha256:6dc98cd6294b58064dfd32b8b7954f2a4530f3165d1e93117d86b29eb2d2460c` |
|  `latest` `1.16.2` `1.16` `1`                 | May 24th     | `sha256:4dcb9e16d87bd56c9d01d2b1014c998bac476a263c5ec8e7f4e79055bd4cbae1` |
|  `1.15` `1.15.8`                              | May 24th     | `sha256:b905fd40ddbfa212d70bafb7d6b79e3ec890f674907d47ac1dca84910c9a33ed` |
|  `1.14.12` `1.14`                             | May 24th     | `sha256:c57ea2ac3e68ec244e864b090a1fbfb5e7da5ba6af728ce5edb72a2788f328ea` |
|  `1.13-dev` `1.13.13-dev`                     | May 14th     | `sha256:f07262ce87225366516a80bb5ed890a173a8f2c0ee1ec69e613b4071d88280e3` |
|  `1.13.13` `1.13`                             | May 13th     | `sha256:35383fc342a68b25575442fb9e682f569a1eddcf0d8af31fade9d22c17e6b317` |

