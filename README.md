# Seamless-Point Project Synchronization Guide

This guide outlines the steps to synchronize the Seamless-Point project repository using the `repo` tool.

## Prerequisites

- Ensure you have `repo` installed. You can find installation instructions [here](https://gerrit.googlesource.com/git-repo).

## Steps to Sync the Seamless-Point Project

### 1. Create and Navigate to the Project Directory

First, create a new directory for the Seamless-Point project and navigate into it:

```sh
mkdir -p seamless-point && cd seamless-point
repo init -u git@github.com:kuzhylol/seamless-point-manifest.git -b main
repo sync -j$(nproc)
