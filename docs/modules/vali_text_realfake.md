---
id: vali-realfake
title: Vali text realfake
sidebar_position: 7
slug: /vali-text-realfake
sidebar_label: Vali text realfake
---

# data.text.realfake

The following is a dataset that takes a folder of text, and draws real or fake samples from that folder of text. This means that it will take a folder of text, and draw samples from that folder of text. It will then return a sample of text that is either real or fake. This is useful for training a model to detect real or fake text. This uses a random variable.

## Register

```bash
c vali.text.realfake register tag=whadup
```

## Serve

```bash

c vali.text.realfake serve tag=whadup
```

## Stake

```bash

c stake {keywithbalance} {amount} vali.text.realfake::whadup
```