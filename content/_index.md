---
description: An example site for hugo-theme-gallery. Images from Unsplash.
#lastmod: 2023-07-05
title: Hugo Gallery
resources:
  - src: https://drscdn.500px.org/photo/1109502553/q%3D90_m%3D2048/v2?sig=593cc44469ca2d2fcf1a064f7f77cd84849424111d2719f9858a20c4a619d08f
    params:
      cover: true # cover of the home page is used for OpenGraph cards, etc.
menus:
  main:
    name: Home
    weight: -1
# sub-galleries on list pages are sorted by date and weight (descending)
#cascade:
#  build:
#    publishResources: false # do not include full images. Also disable download
---
