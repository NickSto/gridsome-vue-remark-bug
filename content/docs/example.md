---
title: A cool title
excerpt: Lorem Ipsum is simply dummy text.
---
// Import any Vue Component. Even other .md files!

import YouTube from '~/components/YouTube.vue'

// Import any JSON if you need data.

import data from '~/data/youtube.json'

// Use front-matter fields anywhere.

# {{ $frontmatter.title }}
> {{ $frontmatter.excerpt }}

// Use your imported Vue Components.

<YouTube :id="data.id" />
