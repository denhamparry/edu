---
title: "etcd Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the etcd Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-03 00:46:08
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/etcd/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/etcd/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/etcd/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/etcd/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 1st     | `sha256:ee6761026286c5207dd676e1125ddb56b9841da14eb6cec475b698fcb95122e1` |
|  `latest`     | May 31st     | `sha256:4d522464f45548db24a50dc66cc9fb4875d217593858c47698d76ea046a11ac7` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                      | Last Changed | Digest                                                                    |
|----------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `3.4-dev` `3.4.32-dev`                      | June 1st     | `sha256:3148ac88170f6af8977a35fba3508d7481923d3ad743b269e354d2971f5e639c` |
|  `3.5-dev` `latest-dev` `3-dev` `3.5.14-dev` | June 1st     | `sha256:02bb03b556caeeb688a42b4b04d81438c28a108d13cf1c7c7ae7d1de48c99b15` |
|  `latest` `3.5.14` `3.5` `3`                 | May 29th     | `sha256:71856e3c0b03b3c334d71372d345c7b12cefb5df0c3159c0fd9098efe6674c72` |
|  `3.5.13-dev`                                | May 24th     | `sha256:8c6eb6ae17078c1b17378bb89830a53f6266d8077bf9ebca8fb21ed194981d9b` |
|  `3.4` `3.4.32`                              | May 23rd     | `sha256:ee3de210f4c4233692bf7d383e45713d63c5b06c57fe78b2ece91f51b683c440` |
|  `3.5.13`                                    | May 23rd     | `sha256:12b285e9204b41f1d65b690bb9225d469784a57f893d166b7aeb4dd53016a4f0` |
|  `3.5.8-dev`                                 | May 13th     | `sha256:5b821a307f18eab710c58a32e737f12670e35f9d433ca462be16b51aebab9eb9` |
|  `3.5.8`                                     | May 13th     | `sha256:ff1f804d0649f9cd97a9d0ff8de33d9b543a41bb4500c2af110e6c979d71c181` |

