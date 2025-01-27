---
title: Create a New App
---

These are the commands you will need when creating a new application.

### Initialize a new app

Make sure you have completed the [install guide](../install).

1. Enter the Nix shell.
    ```bash
    nix-shell ~/.holonix/shellDrv
    ```
2. Download and unpack the Holo World sample DNA project.
    ```bash
    curl ??? | 

## Run from project root 

!!! tip
The following commands should all be run from the project root (e.g., `my_new_app/`).
```bash
cd my_new_app
```
!!!

### Generate a new Zome 

!!! note Run in `nix-shell https://holochain.love`
```bash
hc generate zomes/my_zome rust-proc
```
!!!

### Package an app 

!!! note Run in `nix-shell https://holochain.love`
```bash
hc package
```
!!!

### Run a testing Holochain conductor

!!! note Run in `nix-shell https://holochain.love`
```bash
hc run
```
!!!

!!! note Run in `nix-shell https://holochain.love`
```bash
hc test
```
!!!

### Run a Holochain conductor
You will need to create a config file. See the [hello_world](tutorials/coreconcepts/hello_world) tutorial for an example.

!!! note Run in `nix-shell https://holochain.love`
```bash
holochain -c conductor-config.toml
```
!!!

### Learn more

!!! note Run in `nix-shell https://holochain.love`
```bash
hc help 
holochain --help 
```
!!!
<script id="asciicast-hSQDLOnyqEN8Jm9Oyb00EDZdX" src="https://asciinema.org/a/hSQDLOnyqEN8Jm9Oyb00EDZdX.js" async data-autoplay="true" data-loop="true"></script>
