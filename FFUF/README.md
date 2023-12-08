# FFUF - Fuzz Faster U Fool
* Written in Go
* Faster than Wfuzz
## Requirements
```
Setup
  > Go Lang
  > FFUF
Wordlists (for web fuzzing)
```
### Setup
```
> Install Go - https://golang.org/doc/install
> Clone FUFF - https://github.com/ffuf/ffuf (or) go get github.com/ffuf/ffuf
```
### Wordlists
```
Web fuzzing wordlists:
> https://github.com/danielmiessler/SecLists
> https://github.com/fuzzdb-project/fuzzdb
> https://github.com/swisskyrepo/PayloadsAllTheThings
> Jhaddix All.txt - https://gist.github.com/jhaddix/f64c97d0863a78454e44c2f7119c2a6a
> Jhaddix Content Discover - https://gist.github.com/jhaddix/b80ea67d85c13206125806f0828f4d10
> dicc.txt - https://github.com/rvrsh3ll/dirs3arch/blob/master/db/dicc.txt
```
## Usage
```
ffuf -c -w path/to/wordlist -u https://sub.example.com/FUZZ
```
