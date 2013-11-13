---
layout: post
title: "Auto Update VirtualBox Guest Additions with vagrant-vbguest"
date: 2013-11-12 21:01
comments: true
categories: [vagrant]
---

## The Goal

- Keep the VirtualBox guest additions at the latest version using [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) built by [dotless-de](https://github.com/dotless-de).

<!-- more -->

## vagrant-vbguest

A beautifully simple Vagrant plugin to manage the guest additions on VirtualBox.

## install

```
spudBud@pineApplez> ~/Codestuff/vagrants/PuppetMaster $vagrant plugin install vagrant-vbguest
```

## bootup usage

vagrant-vbguest will run on every `vagrant up` or on a `vagrant reload` unless you specifically tell it not to.

## running VM usage

```
spudBud@pineApplez> vagrant vbguest --status
```
