# GrumbleBundle

**Update 29/05/2019: this repository is now archived, as HumbleBundle
implemented the bulk download feature on their end.**

An add-on to download an entire ebook Humble Bundle in a single click.

## Usage

1. Go to the page dedicated to your bundle (URL should be of the form `https://www.humblebundle.com/downloads?key=<somekey>`);
2. click on the extension logo;
3. pick your format;
4. it's downloading!

## Environment

Should work on any browser that supports WebExtensions (any recent one should
do).

## Install

### Firefox

1. Go to `about:debugging`;
2. click on `Load temporary add-on`;
3. load the `manifest.json` file.

### Other browser

I don't know but you can make a PR to tell me how to do it.

## Known bugs/peculiarities

Here's a list of known bugs I won't fix myself for now because I don't have
time for this:

- Doesn't really make it clear that it started downloading.

Waiting for your PR :-)
