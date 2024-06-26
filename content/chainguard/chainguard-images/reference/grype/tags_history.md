---
title: "grype Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the grype Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-03 00:46:08
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/grype/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/grype/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/grype/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/grype/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 1st     | `sha256:10736481e843ba4afb676b0acefcbebe3f7f2b872764f9274f6d9ad1fb3fd2a5` |
|  `latest`     | May 31st     | `sha256:7dcc4b3d6b0094ea690943c827ff2f60c71018ef2783af059287fc82fe0235f7` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                       | Last Changed | Digest                                                                    |
|-----------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` `0.78.0-dev` `0.78-dev` `0-dev` | June 1st     | `sha256:ae13b5ed7a6d1750464dd8d6f1b46d0fbcd8b1aa5511923e35fb5c6497a7ed49` |
|  `0.78` `0` `latest` `0.78.0`                 | May 28th     | `sha256:4b612697559e9544a23f422cbd7d6cc2bc2cd7bcdd0e8ec6272a506627a618a0` |
|  `0.77.4-dev` `0.77-dev`                      | May 24th     | `sha256:380f76ae00a7ec77a0f125428a37d819f80908e204579549f338809f1bcc1ad1` |
|  `0.77.4` `0.77`                              | May 23rd     | `sha256:50e200a933e4e5a9067245c9cee4ff6d26c96d89ae96b704d1a653b8113a1289` |
|  `0.77.3-dev`                                 | May 10th     | `sha256:e1b42bc5ed7bef8e05a4d586278175e3f9da60a1c117aa6609273b339f1d3190` |
|  `0.77.3`                                     | May 10th     | `sha256:1983c77db21053d04fcd3ff46f40db5fbfaa3852b77f1932dab0873f909a18c8` |

