.. -----------------------------------------------------------------------------
   ..
   ..  Filename       : index.rst
   ..  Author         : Huang Leilei
   ..  Status         : draft
   ..  Created        : 2022-04-18
   ..  Description    : introduction
   ..
.. -----------------------------------------------------------------------------

Introduction
============

Project Tree
------------

   As the name suggested, git_example_rtl is an example for RTLs, which has the following project tree.

   ::

      ├── check                    all kinds of check environments
      │     ├── formality            formality based check environments
      │     └── spyglass             spyglass based check environments
      ├── document                 all kinds of documents
      │     ├── description          module-related documents
      │     ├── brief                branch-related documents
      │     ├── conclusion           phase-related documents
      │     ├── performance          evaluation-related documents
      ├── include                  definitions and top-level parameters
      ├── library                  all kinds of libraries
      │     ├── behave_rtl           behavior models used in designs
      │     ├── behave_sim           behavior models used in testbenches
      │     └── *                    models of technology * (for example, TSMC65, GF28)
      ├── reference_model          reference models
      ├── script                   all kinds of scripts
      │     ├── runListUpdate.sh     update script
      │     └── runListCheck.sh      check script
      ├── simulation               all kinds of simulation environments
      │     ├── rtl                  RTL-level simulation environments
      │     └── netlist              netlist-level simulation environments
      ├── source                   all kinds of source files
      │     ├── *                    source files for *
      │     │     ├── interface        interface-related source files
      │     │     ├── kernel           kernel-related source files
      │     │     └── memory           memory-related source files
      │     └── common               common codes
      ├── synthesis                all kinds of synthesis environments
      │     ├── design_compiler      design_compiler based synthesis environments
      │     ├── quartus              Quartus based synthesis environments
      └     └── vivado               Vivado based synthesis environments

   I will introduce those directories in the following pages
