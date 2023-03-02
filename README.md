# w-generator-offline
W Generator - A powerful frontend tool for penetration testers to generate customized wordlists - Local (offline) version for maximum privacy


# Intro

This tool is a frontend wordlist generator that allows you to generate wordlists to be used in Dictionary Attacks based on publicly available information on a target. (i.e. potential passwords)

The aim of this tool is to assist cybersecurity proffessionals but to also raise awareness on the predictability of passwords used by the average user.

Supports multiple languages in both English and non-English characters (tested on ~40 languages)


# About this version

This version is a built/compiled version of the tool which you can download and run locally without connectivity to the internet.

It is almost an exact copy of the online version, with the only difference being that Google Analytics and sign-up forms are removed to maximize privacy for those who need it.

Note: Even the online version does **NOT** collect any data related to the input data or the wordlists generated, but since understandably some users might have concerns, this version aims to give you full control.



# Instructions

Clone this repo:

```
git clone https://github.com/waelmas/w-generator-offline.git
cd w-generator-offline
```

Install npm serve:

```
npm install --global serve
```

You can now go fully offline if you're paranoid.

Anytime you want to run the app using serve:

```
serve -s build
```

