---
title: "Lorem Arrested Development"
subtitle: "How to add panelsets in R Markdown posts."
excerpt: "Add tabbed sections with code and results."
date: 2021-05-24
author: "Alison Hill"
draft: false
# layout options: single, single-sidebar
layout: single
categories:
- evergreen
---

## Am I where I think I am?


```
## Rows: 344
## Columns: 8
## $ species           <fct> Adelie, Adelie, Adelie, Adelie, Adelie, Adelie, Adel…
## $ island            <fct> Torgersen, Torgersen, Torgersen, Torgersen, Torgerse…
## $ bill_length_mm    <dbl> 39.1, 39.5, 40.3, NA, 36.7, 39.3, 38.9, 39.2, 34.1, …
## $ bill_depth_mm     <dbl> 18.7, 17.4, 18.0, NA, 19.3, 20.6, 17.8, 19.6, 18.1, …
## $ flipper_length_mm <int> 181, 186, 195, NA, 193, 190, 181, 195, 193, 190, 186…
## $ body_mass_g       <int> 3750, 3800, 3250, NA, 3450, 3650, 3625, 4675, 3475, …
## $ sex               <fct> male, female, female, NA, female, male, female, male…
## $ year              <int> 2007, 2007, 2007, 2007, 2007, 2007, 2007, 2007, 2007…
```


## But first, panelsets with R code chunks

{{< panelset class="greetings" >}}
{{< panel name="Plot" >}}

<img src="{{< blogdown/postref >}}index_files/figure-html/plot-1.png" width="672" />

{{< /panel >}}
{{< panel name="Code" >}}


``` r
plot(pressure)
```

{{< /panel >}}
{{< /panelset  >}}

## I'm half machine. I'm a monster.

It's a hug, Michael. I'm hugging you. I'm half machine. I'm a monster. There's only one man I've ever called a coward, and that's Brian Doyle Murray. No, what I'm calling you is a television actor. Bad news. Andy Griffith turned us down. He didn't like his trailer.

No, I did not kill Kitty. However, I am going to oblige and answer the nice officer's questions because I am an honest man with no secrets to hide. Guy's a pro. Really? __Did nothing cancel?__ *Get me a vodka rocks.* And a piece of toast.

## No… but I'd like to be asked!

Oh, you're gonna be in a coma, all right. Steve Holt! I hear the jury's still out on science. No, I did not kill Kitty. However, I am going to oblige and answer the nice officer's questions because I am an honest man with no secrets to hide.

1. Really? Did nothing cancel?
2. That's what it said on 'Ask Jeeves.'
3. Get me a vodka rocks. And a piece of toast.

### That's what it said on 'Ask Jeeves.'

Did you enjoy your meal, Mom? You drank it fast enough. What's Spanish for "I know you speak English?" Bad news. Andy Griffith turned us down. He didn't like his trailer. Really? Did nothing cancel? I care deeply for nature.

* Michael!
* No! I was ashamed to be SEEN with you. I like being with you.
* We just call it a sausage.

Well, what do you expect, mother? It's called 'taking advantage.' It's what gets you ahead in life. Now, when you do this without getting punched in the chest, you'll have more fun. No, I did not kill Kitty. However, I am going to oblige and answer the nice officer's questions because I am an honest man with no secrets to hide.

I'm half machine. I'm a monster. It's a hug, Michael. I'm hugging you. Guy's a pro. First place chick is hot, but has an attitude, doesn't date magicians. He'll want to use your yacht, and I don't want this thing smelling like fish.

He'll want to use your yacht, and I don't want this thing smelling like fish. Now, when you do this without getting punched in the chest, you'll have more fun. We just call it a sausage. Guy's a pro. Bad news. Andy Griffith turned us down. He didn't like his trailer.

There's only one man I've ever called a coward, and that's Brian Doyle Murray. No, what I'm calling you is a television actor. It's called 'taking advantage.' It's what gets you ahead in life. We just call it a sausage.

Michael! First place chick is hot, but has an attitude, doesn't date magicians. I've opened a door here that I regret. Guy's a pro.

Army had half a day. Michael! Now, when you do this without getting punched in the chest, you'll have more fun. Well, what do you expect, mother? Now, when you do this without getting punched in the chest, you'll have more fun.

But I bought a yearbook ad from you, doesn't that mean anything anymore? Oh, you're gonna be in a coma, all right. It's a hug, Michael. I'm hugging you. I've opened a door here that I regret.

There's only one man I've ever called a coward, and that's Brian Doyle Murray. No, what I'm calling you is a television actor. That's why you always leave a note! He'll want to use your yacht, and I don't want this thing smelling like fish.

I've opened a door here that I regret. Now, when you do this without getting punched in the chest, you'll have more fun. I care deeply for nature. It's called 'taking advantage.' It's what gets you ahead in life.

It's a hug, Michael. I'm hugging you. No… but I'd like to be asked! What's Spanish for "I know you speak English?" It's called 'taking advantage.' It's what gets you ahead in life. It's a hug, Michael. I'm hugging you.

I don't understand the question, and I won't respond to it. Really? Did nothing cancel? Did you enjoy your meal, Mom? You drank it fast enough. Bad news. Andy Griffith turned us down. He didn't like his trailer.


