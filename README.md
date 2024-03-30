
# Crack Passwords in Kali Linux Using John The Ripper

version: 1.9.0 arch: any all



## Installation

Github link: https://gitlab.com/kalilinux/packages/john



![Logo](https://www.kali.org/tools/john/images/john-logo.svg)


## Usage/Example
1. Locate the file by using command line
```
cd Desktop
```
2. In desktop to find the list of files:
```
ls
```
3. conjunction with a password
```
pdf2john test.pdf > test.hash
```
4. The file goes through the hashing algorithm
```
john test.hash
```
5. password hash cracked 
