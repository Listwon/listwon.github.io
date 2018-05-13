---
layout: post
title: "Pixel Perfect 2D w Unity"
crawlertitle: "Pixel Perfect 2D w Unity"
summary: "Rozwiązanie"
date: 2018-04-25
categories: wpisy
tags: ['gamedev']
author: "Bartłomiej T. Listwon"
---

Co trzeba uwzględnić?
<!--more-->

* wyłączone MSAA (anti aliasing) - ustawienia kamery i quality settings
* wyłączone filtrowanie tekstur (no filter) - ustawienia importera tekstur
* TilemapRenderer i SpriteRenderer z nałożonym materiałem Sprite/Default z włączonym Pixel Snap
* ustalona całkowitoliczbowa rozdzielczość kamery w edytorze (najlepiej typowa, podzielna przez 2)

[Artykuł o Pixel Perfect 2D na oficjalnym blogu Unity](https://blogs.unity3d.com/2015/06/19/pixel-perfect-2d/)
