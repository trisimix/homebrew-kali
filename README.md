# Homebrew Kali 
A Homebrew tap for Kali Linux tools.

# Goals
The ultimate goal is to brew all major Kali Linux tools (not already present in homebrew/homebrew).

# Development Plan
The development plan for this repository is as follows. Scritps are not guaranteed to work until 'Head-Only Installs' has been crossed off the list.

* ~~Skeleton scripts (not working)~~
* Head-Only Installs
* Full Formulae

# Usage
```
# Kali on tap:
brew tap b-ramsey/homebrew-kali
brew install [--HEAD] <package>

# Alternatively, without kali on tap:
brew install [--HEAD] b-ramsey/homebrew-kali/<package>
```

# Contributor Guidelines
* Don't touch any scripts marked with a 'complete' commit message
* Follow Homebrew's guides on [Acceptable Formulae](https://github.com/Homebrew/homebrew/blob/master/share/doc/homebrew/Acceptable-Formulae.md), the [Ruby Style Guide](https://github.com/styleguide/ruby) (for complex scripts).
* If you need help getting started, there's the [Homebrew Formula Cookbook](https://github.com/Homebrew/homebrew/blob/master/share/doc/homebrew/Formula-Cookbook.md), along with a [Formula Cheat Sheet](https://github.com/Homebrew/homebrew/blob/master/Library/Contributions/example-formula.rb).

1. Fork this repo
2. Edit *ONE* script
3. Pull Request

One script per pull request please. :)

# Already in homebrew/homebrew
* aircrack-ng - source only doesnt work
* amap - upstream fucked
* apktool - x86 only
* arp-scan - works
* binwalk - works
* capstone - works
* (cmu-)sphinxbase - works
* cowpatty - missing
* crunch - works
* dc3dd - source only doesnt work
* ddrescue - works
* dex2jar - works
* dns2tcp - works
* dnsmap - works
* dnstracer - works
* dos2unix - works
* ettercap - works
* fcrackzip - works
* foremost - works
* fragroute - works
* hping - works
* httptunnel - upstream fucked
* hydra - works
* john-the-ripper (as john-jumbo) - works
* libbtbb - works
* libewf - works
* libfreefare - works
* libmicrohttpd - works
* libnfc - works
* lynis - works
* masscan - works
* mfcuk - works
* mitmproxy - works
* msgpack (non-python) - works
* ncrack - works
* nikto - works 
* nmap - works 
* p0f - works
* pixz - works
* proxychains-ng - works
* pwnat - works
* qemu - works
* reaver - works
* rtl-sdr - works
* rtpbreak - missing
* sipp - works
* skipfish - missing
* sleuthkit - works
* slowhttptest - works
* smali - works
* sqlmap - works
* ssdeep - works
* sslscan - works
* thc-pptp-bruter - missing
* theharvester - works
* truecrack - works
* valgrind - linux only
* volatility - source only doesnt work
* wine - missing
* winexe - source only doesnt work 
* wireshark - works, need cask for gui
* yara (non-python) - woks

# Intentionally Ignored
* Arachni (Use official installer) 
* CaseFile (Commercial License)
* Android SDK (Use official installer)
* VirtualBox (Use official installer)
* Arduino (Use official installer)
* OllyDbg (No OS X support - may be possible with WINE? Investigate...)

# Revisit...
* ...

