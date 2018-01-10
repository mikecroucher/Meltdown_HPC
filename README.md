# Melthdown and High Performance Computing

## Authors (Alphabetical by surname): Mike Croucher (University of Sheffield), Adrian Jackson (EPCC), ADD YOUR NAME TOO AS SOON AS YOU'VE CONTRIBUTED

Collaborative blog post about the effect of meltdown on HPC systems. 

Once we've finished this, we can reblog where-ever we like.

# Introduction

The [Meltdown bug](https://en.wikipedia.org/wiki/Meltdown_(security_vulnerability)) which affects most modern CPUs has been called by some ['The worst ever CPU bug'](https://www.theguardian.com/technology/2018/jan/04/meltdown-spectre-worst-cpu-bugs-ever-found-affect-computers-intel-processors-security-flaw).  Accessible explanations about what the Meltdown bug actually is are available [here](https://www.facebook.com/Ozzard/posts/10157151940878975) and [here](https://www.raspberrypi.org/blog/why-raspberry-pi-isnt-vulnerable-to-spectre-or-meltdown/).

Software patches have been made available but some people have esitmated a performance hit of up to 30% in some cases. Some of us in the High Performance Computing (HPC) (See [here for the initial twitter conversation](https://twitter.com/walkingrandomly/status/949230133243768835)) community started to wonder what this might mean for the type of workloads run on our systems.  After all, if the worst case scenario of 30% is the norm, it will drastically affect the power of our systems and hence reduce the amount of science we are able to support.

# To patch or not to patch

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Given the size of the performance hit should we even *be* patching for this? Unless you need trusted computing, does it really matter for the average HPC?</p>&mdash; Phil Tooley (@acceleratedsci) <a href="https://twitter.com/acceleratedsci/status/949233180451713024?ref_src=twsrc%5Etfw">January 5, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Further discussion here

# Discussion about where the performance hits actually are

Stuff here

## Benchmark results from Filippo

Stuff goes here

## Benchmark results from Adrian

More stuff goes here

## More benchmark results

with your results underneath
