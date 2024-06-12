# The Embedded Rust Book Work-Through

*My work-through[^1] of
[The Embedded Rust Book](https://doc.rust-lang.org/beta/embedded-book/).*

[^1]: The term "work-through" is what I've come up with for instances of my
  practice of working through examples, books, and tutorials to keep up with the
  software industry andcontinuosly improve my skills and knowledge.

## Dependencies

This repo depends on the
[build-systems](https://github.com/EngJay/build-systems)
repo to provide its build environment. It is included as a submodule in the
root of the repo. Clone this repo with submodules included recursively to pull
in everything needed to build in a Docker container.

## Building

TODO

To open a shell in a build environment container, run from the root of the repo.

```bash
> ./build-systems/scripts/shell.sh ORG_NAME:IMAGE_NAME:VERSION
```

You should get a similar response to this confirming the input.

```bash
Open Shell in Docker Image
============================================================

Org: ORG_NAME
Image: IMAGE_NAME
Version: VERSION

root@ca5eda15a2f0:/#
```
