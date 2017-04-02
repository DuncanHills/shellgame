Clever Title
============

---

Useful Commands
---------------

----

# echo

----

# pwd

----

# ls

----

# cd

----

# cat

----

# history

----

# less

----

# nano/vim

----

# rm

----

# which

----

# type

----

# man

----

# whoami

----

# users

----

# groups

----

# htop

----

# chmod/chown

----

# file/id

----

# grep

----

# hostname

----

# env

----

# diff

----

# mv

----

# curl/wget

----

# wc

----

# true/false

----

# alias

----

# ssh

----

# scp

----

# ping

----

# dig

---


Concepts
--------

---

## What is the shell?

---

## Commands

----

### Flags – short, long, help

----

### Quotes

----

### Exit conditions

---

## Files and directories

----

### Relative and absolute paths

----

### File conventions - hidden files, file extensions

----

### Spaces

----

## Wildcards

---

## Tab completion

---

## Variables

---

## Subshells

---

## Shell scripts

---

## Users and permissions

---

## Package management

---

Exercises
---------

---

# Getting started

----

## telnet towel.blinkenlights.nl

----

## Search for text

----

## chatbot

----

## Run a python script

----

## Write a plain text document

----

## Write a markdown document and render it in html

---

# Install homebrew

---

## Install cowsay

----

## Install lolcat

----

## Install and play a text adventure

---

# OCR demo

----

## Install tesseract

```sh
brew install tesseract
```

----

## Make the cow say the bad things

```sh
mkdir ocr && cd ocr
wget https://i.imgur.com/WaeTW8W.png -o gametheory.png
tesseract --help
```

----

## OCR Solution

```sh
tesseract ./gametheory.png gametheory.txt
cat gametheory.txt | cowsay

# alternative solution
tesseract ./gametheory.png stdout | sed -e '/^$/d' | tail -n 1 | cowsay
```

---

# SSH into an remote Computer

----

## Run a flask application

---

You Done It!
------------