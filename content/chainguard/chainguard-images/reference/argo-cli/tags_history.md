---
title: "argo-cli Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the argo-cli Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-03 00:46:08
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/argo-cli/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/argo-cli/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/argo-cli/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/argo-cli/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 1st     | `sha256:f7a9e46e50970c512f2b59e15b6f1cdc764366d00de200a93447f4a77cc68cbf` |
|  `latest`     | May 31st     | `sha256:c128bf957dcd6806ed1954a6d26f24bd5c845d77b94a76adbf26e7877fcb9aa2` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                     | Last Changed | Digest                                                                    |
|---------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `3-dev` `latest-dev` `3.5-dev` `3.5.7-dev` | June 1st     | `sha256:34edfa1b20cdf60049f8655e6ac28e87ddfbfa8b408c9f90e5b73e892edf9c8f` |
|  `3` `3.5` `latest` `3.5.7`                 | May 27th     | `sha256:0a9d38eda53c69b7d60c7af279f00ff64e7165c439b50dba6d29d34588cf01c1` |
|  `3.5.6-dev`                                | May 24th     | `sha256:450b28dec861cd3e8f90e161cc1356814cc5f41a23df847843fa246ed624620f` |
|  `3.5.6`                                    | May 23rd     | `sha256:fcc37c026ede0ed3b4640d7e2aa89cc3955c755acc1d8081e2ef81760ab20e4a` |

