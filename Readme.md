# Shaeru

This is a node.js command line utility which can be used to share the contents of a folder via browser on the local network.


## Installation

Use **-g** for global install

```bash
npm install -g shaeru
```

## Using

Go to the directory you want to share, and run `shaeru`.

### Examples

Share the current folder available on `<your_hotname/your_ip>:3000` on the local network:

```bash
shaeru
```

Share the current folder available on `<your_hostname/your_ip>:12345` on the local network:

```bash
shaeru --port 12345
```

### IMPORTANT

Filenames starting with a dot or hidden files are assumed to be private and are not served.
