+++
title = "Ryza"
hascode = true
date = Date(2021, 2, 13)
rss = "A short description of the page which would serve as **blurb** in a `RSS` feed; you can use basic markdown here but the whole description string must be a single line (not a multiline string). Like this one for instance. Keep in mind that styling is minimal in RSS so for instance don't expect maths or fancy styling to work; images should be ok though: ![](https://upload.wikimedia.org/wikipedia/en/3/32/Rick_and_Morty_opening_credits.jpeg)"
+++
@def tags = ["syntax", "code"]

# Table of contents

\toc

## Resources
- Ryzen 3950X
- RTX 3090
- 64 GB RAM 

## Philosophy
- This is not a substitute of bwUniCluster. For massive computations, please use the cluster.
- Don’t occupy more than 8 CPU cores for non-instantaneous tasks
- Don’t use more than 400GB Disk space
- Think before you type

## Admin philosophy
- Manually installed software should be installed to /opt/ or /usr/local
⇒ add the path to /etc/environment s.t. all users can use the programm

## Current base
- Room 3.020, CS 20.30

## Access
- IP: 129.13.160.119 (only accessible within KIT intranet)

## Softwares available
- anaconda: /opt/anaconda3
- cuda: /usr/local/cuda
- jupyter: /opt/anaconda3/bin/jupyter
- python: /opt/anaconda3/bin/python
- zerotier: /usr/sbin/zerotier-cli

### APT modules installed as root:
- general: gcc, git, ...
- fish
- screen
