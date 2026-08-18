---
date: 2026-08-08
title: I've been vibe coding
# description: >-
#  Vibe coding insights and life recently
# tags:
#   - tech
#   - lifestyle
layout: post
published: true
---
It has been almost a year since I last wrote here (oops). Since I last posted, the Knicks won the NBA Championship for the first time in my lifetime, I turned 23, the world cup happened and completely disrupted my commute to NYC and my ability to get around North NJ for like 2 months, I signed a lease for an apartment in Jersey City (so I'm moving soon), I got a part-time job as a pilates instructor (yay!), had to quit said job due to the aforementioned move, and I went to Singapore (my first time in Asia!!). Safe to say a lot has happened.



<div style="text-align:center; margin-bottom: 2.5em;">
  <img src="/assets/pilates.JPG" alt="pilates" width="500">
  <br>
  <em>Me at the pilates studio I was working at</em>
</div>


<div style="display: flex; justify-content: center; gap: 20px; margin-bottom: 2.5em; text-align: center;">
  <div style="flex: 1; max-width: 500px;">
    <img src="/assets/singapore-skyline-grace.JPG" alt="singapore-skyline-grace" style="width: 100%; height: 300px; object-fit: cover; border-radius: 8px;">
    <br>
    <em style="font-size: 0.9rem;">Me in Singapore!</em>
  </div>
  <div style="flex: 1; max-width: 500px;">
    <img src="/assets/singapore-casino-hotel.JPG" alt="singapore-casino-hotel" style="width: 100%; height: 300px; object-fit: cover; border-radius: 8px;">
    <br>
    <em style="font-size: 0.9rem;">The famous Marina Bay Sands hotel in Singapore, from the ground</em>
  </div>
</div>

Part of the reason it has taken so long, besides being generally busy, is that I've been considering switching to substack. I think this format is more technical, and I get more control over the layout and content. Plus I think it looks better on job applications if my "website" has "github" in it; I am a software engineer. But substack has a slightly easier way of reaching an actual audience.

TODO: research ways to link a personal blog to substack to automatically cross-post. 

Anyway, as the title suggests, I have been vibe coding a lot lately. If you check my github commits, there are bunch of brighter green tiles in the past 2-3 weeks or so. That's because I'm trying to just build stuff, whatever I think would be cool, or might solve a small problem. I'm a very type A person, and so I always like to have as much information as possible before I go and do something, and that applies to programming as well. I would always wait until I finished a particular course about something, or read a certain book before I actually began building. Then, I would forget about the book or course, not finish it, and never actually get to building. I have decided to stop that. The fastest way to learn these days (and you have to be fast just to keep up), is to just do it. Build, create, write, etc. Whatever you want to become good at, you just have to do it, and know that you're gonna suck for a bit. With AI tools, learning something comprehensively from a top down approach is finally feasible. 

Some things I have vibe coded (all of which you can find on my github): 
- A [satellite collision tracker](https://satellite-trackr.vercel.app/) that calculates orbits of satellites and potential collisions between them over the next 24 hours.
- An [LLM powered cli tool](https://github.com/gracel0721/error-explainer) that explains errors given an error text output, log file, piped input, or repo
- A (very in progress) map tool called [HealthMaps](https://healthmaps-gqj3.vercel.app/), that shows free healthy living resources on a map, searchable by address, zip code, or city/town.
I'm also currently working on a "Second Brain" RAG pipeline for myself that can connect to digital tools I use like Github, Spotify, Notes, and GSuite, so I can have everything in one place. 

All of these I spun up in a weekend or less. The error explainer was built and tested in like 2 hours. They may not be the highest quality, but there is an application. It exists, and can be iterated upon fairly inexpensively. I think everyone should just take that idea they have, give it to Claude code, or whatever tool they use, and see what happens. It's been helpful for exposing me to new technologies and languages that would otherwise take me much longer to learn and build with. I was able to use terraform to deploy the satellite tracker backend architecture to GCP, which is awesome because, 1. I've never had to use terraform before, and 2. I've never used GCP before, only AWS. But I was able to create the files, deploy, and now I have a terraform deployment example, and a good idea of what GCP services equivalent to the AWS ones that I am already familiar with. The speed of learning and creation is skyrocketing with the use of these tools. 

If you're curious about my AI tools setup, I use Claude Code (CLI), but with models pulled from Ollama. If you have enough space, a GPU, and a powerful enough CPU, I highly recommend downloading and running a model locally. I have an older laptop, so I do pay for the lowest tier Ollama pro, but I have yet to get anywhere near the usage limits. 
I use Gemini and the general ollama chat with whatever model to iterate over ideas and generate plan and spec files before actually implementing them. It's a practice I picked up at work (since the stakes are a bit higher there, and that is what they ask us to do to optimize token usage and not break qa), but it has been helpful for vibe coding things faster personally. 

I also use the free tier Claude and ChatGPT models to explain unfamilar subjects top-down, and give examples of applications or projects I can build (if relevant) to garner a deeper understanding. Any terms or technologies it mentions that I don't know, or don't understand, I will point out and ask it to explain, and then the cycle repeats, almost recursively. 

I got the recursive learning with LLMS idea from [Gabriel Petersson](https://x.com/gabriel1). He's got some genuinely good advice, ideas, and hot takes, so I recommend checking out some of his stuff. 


Hopefully I can actually post on a regular cadence, and it won't be a year before the next post I make.


Currentlies: 
- Currently Reading: Poor Charlie's Almanack, which is a compilation of speeches and talks given by Charlie Munger. It was a gift, and I promised the bestower that I would read it, so I am. It's very good practical advice so far, almost up there with the book of Proverbs. I said almost.
- Currently Listening: Fire From the Hip, by Finn Wolfhard. I went to the NYC show on the tour for this album on my birthday two weeks ago. It's a solid one, feels a bit coming-of-age movie meets sorta country folk music. Follow is my favorite song on the record.
- Currently Watching: Rick and Morty S9. I've been watching it since like 2017, so I have to see it through. This season has been a bit all over the place in my opinion. Some episodes are a whole lot of nothing happening for 30 minutes, but I do like how they're actually starting to acknowledge Rick's alcoholism and its effects beyond it being long running gag. I don't try to analyze it too hard though. It's Rick and Morty.
- Currently on my wish list: Blue light glasses. My trusty old ones that I've had for 5 years cracked at the frames where the lenses are held in, and I tried to fix it with superglue, but to no avail. With all the late night vibe coding, I really need a pair so I can get decent sleep and not fry my eyes and brain


Some pictures of life recently:
<!-- Each figure is centered with spacing below. Adjust width= for size, margin-bottom for spacing. -->


<div style="text-align:center; margin-bottom: 2.5em;">
  <img src="/assets/cat-knee.JPG" alt="cat-knee" width="500">
  <br>
  <em>Cat tax: Wayne curled up in the crook of my knee</em>
</div>



<div style="text-align:center; margin-bottom: 2.5em;">
  <img src="/assets/finnwolfhard-nyc7-21-26.JPG" alt="finnwolfhard-nyc7-21-26" width="500">
  <br>
  <em>Finn Wolfhard Concert at Webster Hall in NYC on my birthday!</em>
</div>