---
title: "wazero Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the wazero Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-03 00:46:08
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/wazero/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/wazero/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/wazero/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/wazero/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 1st     | `sha256:59c9f472f2925f1832a4b7b99ec425518d7dce7bce8248d40717fbac9e99774b` |
|  `latest`     | May 23rd     | `sha256:805e09618e910fe132b3d14915275a6f3d4eedf83b41cc2bc8feefdb9511dc6a` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                     | Last Changed | Digest                                                                    |
|---------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` `1.7-dev` `1.7.2-dev` `1-dev` | June 1st     | `sha256:c41e59b7d65e897485434ff5b5c0680e4a2f729b4d216fa8744bdf3ff73f68ff` |
|  `1.7.2` `latest` `1` `1.7`                 | May 23rd     | `sha256:6c3aab1f194ff64123ac5de9b3a8d000683f02200aed903fb8f415b357ae34c8` |
|  `1.7.1-dev`                                | May 8th      | `sha256:ef3d5afc152ec35d30a95380e03eb0612675081c5e1146200d5a4ed9010b89e6` |
|  `1.7.1`                                    | May 8th      | `sha256:f24499e05fe5f466f1c3760f9e24101c083042c9a91af401022ba6d200398022` |

