# ja2-fife-demo

Small demo for using the Jagged Alliance 2 Assets in the FIFE engine.

## Installation

### Step 1: Clone / Download this Repository

### Step 2: Install fifengine

Get and install it from https://github.com/fifengine/fifengine

### Step 3: Dumping the ja2 Assets

You need a licensed copy of Jagged Alliance 2 for this (tested with english version)

Clone the ja2-open-toolset from here https://github.com/selaux/ja2-open-toolset

Install the dependencies for the ja2-open-toolset (pyfilesystem and Pillow)

Dump the assets with the following commands:

```
cd ja2-open-toolset/ja2data
python cli-tools/dump_data.py -n /path/to/ja2/installation/Data -o /path/to/ja2-fife/ja2-data-dump
```

This might take a few minutes and print some notifications, but should work.

### Step 4: Start ja2-fife

```
python run.py
```
