<!-- markdownlint-configure-file {
  "MD013": {
    "code_blocks": false,
    "tables": false
  },
  "MD033": false,
  "MD041": false
} -->

<div align="center">

# VMAttack - Research Tool

VMAttack is a **work-in-progress** project focused on **.NET Virtual machines**. 
It's currently exploring the **virtualization techniques**.

The goal is to help security researchers detect and identify malware that uses them.

[Getting started](#getting-started) •
[Implemented VM's](#implemented-vms) •
[Dependencies](#dependencies) •


[![forthebadge](https://forthebadge.com/images/badges/powered-by-black-magic.svg)](https://forthebadge.com)

</div>

## Getting started 

This project is an open-source (GPLv3) being under heavy work in progress and is being created as a study for anyone who wants to explore .NET VMs and learn about `CIL Virtualization` techniques and how to read them.

`Virtualization` is a common form of code obfuscation. It transforms code into a virtual program that is no longer recognizable as its source code, allowing it to be executed without the need for a human-readable form. However, this makes it difficult for security analysts to understand the behavior of virtualized programs, as the internal mechanism of commercial obfuscators is a black box.


## Implemented Code Virtualization Obfuscators 
-------------------
- [Eziriz .NET Reactor](doc/Eziriz/Readme.md) [WIP]

## Dependencies
---------------
- [AsmResolver](https://github.com/Washi1337/AsmResolver)
- [Echo Framework](https://github.com/Washi1337/AsmResolver)

## License
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
