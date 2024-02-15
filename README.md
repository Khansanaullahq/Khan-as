#!/bin/bash

source src/bashutils/banner.sh
source src/core.sh

### khan (I know, this is obvious xD)
khan

### Check root priv
check_root_priv

### PYTHON SETUP
python_setup

### CREATE AND PARSE INFORMATION
python3 src/brain.py

### DOWNLOAD AND INSTALL PROGRAMS
main
