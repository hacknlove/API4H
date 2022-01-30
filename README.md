# API4H
API4H means API for Humans, and defines a standarized way for webapps to offer a specific API that make's it possible to create alternative interfaces for people with accesibility needs.

## Why
Maybe adding aria-tags and css media queries to a webapp whose UX experience has been designed for people without accesibility needs is not enough.

Sure they can turn an impossible to use interface into a usable one, but if you want to provide an optimized UX, a specific interface should be designed from scratch with the needs of the user in mind.

The role of API4H is to provice a standard way to find out if a site allows and makes it easy to create such alternative interfaces. 

So imagine there is this site with great accesibility `https://example.com` and but still, you think the UX could be better for your specific needs. You just try to open `https://example.com/API4H/index.md` and bingo!, you can creat it. But before, take a look at `https://example.com/API4H/interfaces.md` because maybe the interfaze you are looking for is already there.

## Basics

* Documentation files must be simple and well structured markdown.

## Basic Mandatory files
### `/API4H/index.md`
It's the description of the site, what it's about and how to use it.

### `/API4H/versions.md`
The list with the available versions available

### `/API4H/contact.md`
The accesible contact information for the site. (email, phone, etc)

### `/API4H/legal.md`
The accesible legal information for the site. (terms of use, privacy policy, etc)

### `API4H/interfaces.md`
A list with the alternative interfaces available.
## Version mandatory files.

### `/API4H/versions/1.0.0/index.md`
The description of the version. What you can do with ths version
