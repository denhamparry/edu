---
title: "cadvisor Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the cadvisor Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-03 00:46:08
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/cadvisor/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/cadvisor/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/cadvisor/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/cadvisor/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 1st     | `sha256:061bd8f7a94881a070ab162309d462e822e09c770f209b415213b76e2f3404a4` |
|  `latest`     | May 23rd     | `sha256:dc2964001d41637e4bc1e842556699af3f08f7154e08a4563099091e2e94ca05` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                       | Last Changed | Digest                                                                    |
|-----------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `0.49-dev` `latest-dev` `0-dev` `0.49.1-dev` | June 1st     | `sha256:f6c91a4517b7e512ff4fcac3755a324900194e42d304fb84b21625db5bed309c` |
|  `0` `0.49` `0.49.1` `latest`                 | May 23rd     | `sha256:0b0bdd9db0a6c19e3ead5cdfdd6713569d4395ef3d5b44f3c5cf9319d1e661c6` |

