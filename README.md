# Wiz-CLI
With this CLI you can control your wiz lights from the terminal or program.

# Sources

- [Hacking Philips Wiz lights via command line](https://aleksandr.rogozin.us/blog/2021/8/13/hacking-philips-wiz-lights-via-command-line)
  This is a document how to make command in the command line.
- [Wiz-CLI with Python](https://github.com/infinityInfinite/philips-wiz-CLI)
  I don't think this CLI is easy or fast to use, but it provides the information of the UDP message format
- [Code for pinging all IP-address in local network threaded](https://www.reddit.com/r/rust/comments/11rz8qu/comment/jdpaypj/?utm_source=share&utm_medium=web2x&context=3)
  Using this for pinging all IP-address to `arp -a`

# Goals 

- [ ] Create a CLI that detects all wiz lights in the local network
- [ ] a CLI that is easy and quick to use

# Install

If you don't have `net-tools` install on your system then use this command:

```bash
sudo apt install net-tools
```
