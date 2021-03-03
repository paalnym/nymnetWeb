---
title: My third Blog Post
description: Learning how to use @nuxt/content to create a blog
img: https://images.unsplash.com/photo-1418065460487-3e41a6c84dc5?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60
alt: my third blog post
author:
  name: Paal Nymoen
  bio: All about Pål
  image: NymoenPål_300px.jpg
tags: 
- web development 
---

<author :author="author"></author>

## This is a heading

This is some more info

<div class="bg-blue-500 text-white p-4 mb-4">
  This is HTML inside markdown that has a class of note
</div>

### This is a sub heading

This is some more info

<info-box>
  <template #info-box>
    This is a vue component inside markdown using slots
  </template>
</info-box>

### This is another sub heading

This is some more info

## This is another heading

This is some more info

