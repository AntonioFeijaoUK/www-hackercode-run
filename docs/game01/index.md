---
title: "Mini-game crypto-challenge GAME01"
layout: single
classes: wide

author_profile: true

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: ../assets/images/Four-rotor-enigma.jpg
  actions:
    - label: "HackerCode.Run"
      url: "https://www.HackerCode.Run"
  caption: "Photo credit: wikipedia"

tags:
    - aws
    - gameday
    - awsgameday
    - unicorns
    - crypto
    - cryptography

description: "mini-game crypto challenge GAME01"
---


## Welcome

Welcome to the crypto-challenge version `v2 machine: nzv-09p6186nnp1781870`

First of all, can you find where the challenge is?

All I can say is that you will run it in the `us-east-1` region.

You also need something from this page, maybe you already saw it.

If you need a hint - "Julius Caesar..."

----

## When you find it

When you find it, ssh into to it and then, the game begins!

Note the login message.

Can you find the password that decrypts the first file which reveal the hidden message in it?

----

## How files were encrypted and how to decrypt the files

Files were encrypted like this:

`gpg --cipher-algo AES256 --symmetric --output file01.encrypted file01`


When you find the password for the next file, use the command like this:

`gpg --output file{01..05} --decrypt file{01..05}.encrypted`


Then you will be asked for a password.

Type it in to decrypt the file which will reveal the next hidden message.


If you need to clear the gpg cache, in case you used a wrong password, you might need to run this command `echo RELOADAGENT | gpg-connect-agent`

----

## Passwords use the full names of the services

(is not fun if you brute-force, but nothing stops you...)

The passwords to decrypt the files need the AWS or Amazon full names of the services.

Spaces matter. New lines matter. Everything matters!

- e.g. "Where would you store object files with 99.999999999% (11 9's) of durability?"

- Password answer would be: `Amazon Simple Storage Service`

----

## Good luck

We wish you the best of good luck!

----

## Find more about AWS GameDay

[AWS GameDay](https://aws.amazon.com/gameday/)

---

## Thank you

Cryptographic game was created by [Antonio Feijao](https://antoniofeijao.com/), AWS Infrastructure Architect @ Genomics England.


Thank you,

[Antonio Feijao](https://antoniofeijao.com/)
