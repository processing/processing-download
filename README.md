# Processing Download

This repository stores a backup of the legacy dependency files used for building Processing.

> [!WARNING]
> This repository does NOT and SHOULD NOT directly serve NOR continuously deploy files to `download.processing.org`. This must be done separately.

## Context
To [build Processing](https://github.com/processing/processing4/blob/main/build/README.md), the build system downloads various dependencies, such as OpenJDK and OpenJFX, as specified in the [`build.xml`](https://github.com/processing/processing4/blob/6a2cf8cda35552c62a1a794bb1e20f43fe8ffcda/app/build.xml) file. Some of these dependencies are hosted on a server accessible via stable urls at download.processing.org. This is a fallback solution, in case any of those files end up no longer being hosted by their original distributors.

## Purpose

This repository acts as a reliable source and backup for these files, using Git LFS for larger items. Its primary role is to ensure a backup is available for deploying a new download server if needed. 
