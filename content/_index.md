---
title: ""
date: 2020-04-23T18:41:38+02:00
draft: false
---

## use Hugo and tailwind AND Sass, at the same time
Hello this text is from `content/_index.md`.  
To style **Hugo** rendered documents with tailwind and sass, use
`@apply`  

``` css
article {
  h2 {
    @apply text-5xl;
    @apply text-red-600 font-bold;
  }

  strong {
    @apply text-yellow-500 block bg-blue-200;
  }
}
```

