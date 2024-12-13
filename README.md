# Processing Download

This is a cold backup of the legacy dependency files used for building Processing.

> [!WARNING]
> This repository does NOT and SHOULD NOT directly serve NOR continuously deploy files to `download.processing.org`.

> [!NOTE]
> Larger files are stored on GitHub using Git LFS.

## Context
To [build Processing](https://github.com/processing/processing4/blob/main/build/README.md), the build system downloads various dependencies, such as OpenJDK and OpenJFX, as specified in the [`build.xml`](https://github.com/processing/processing4/blob/2a97f64607f8d73ff07ccd1c1e7e8b22dffcec40/app/build.xml) file. Historically, some of these dependencies have been hosted on a server accessible via stable urls at `download.processing.org`. This was set up as a fallback solution, in case any of those files end up no longer being hosted by their original distributors.

## Purpose
This repository acts as an archival backup for these files. Its primary role is to ensure a copy of these dependencies is available if needed (for example, in case we need to deploy a new download server).

