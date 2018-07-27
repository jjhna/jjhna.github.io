---
layout: essay
type: essay
title: "EEG to telekinetic powers"
date: 2018-07-16
labels:
  - BR41N
  - Hackathon
  - Unity
  - HTC VIVE
  - Simulink
---

<img class="ui image" src="../images/BR41N.jpg">

*Final picture of the entire hackathon participants*

# My thoughts on the BR41N 2018 hackathon

## Initial thoughts

My initial thoughts when I first joined this Hackathon, was a lot of doubt. This wasn't my first rodeo for a hackathon, but this was the first hackathon that I would be working with Brain Computer Interface (BCI). I had some experience with Unity but working with BCI and understanding EEG's were a whole different ballgame. Some of the first things that I did notice when I stepped through the doors was that it was empty for a hackathon. I guessed that it was the summer break and that students had no reason to come to school which meant less coverage and participants. Fortunately, I took the first step forward and went into the hackathon with an open mind and met new friendly people. 

## Issues

The first instance of trouble was setting up the Unicorn, there was a lot of additional software and licenses to install. Secondly, we had a lot of issues when dealing with Simulink (System simulation which auto-generate code for the program), we had to import a lot of custom code from one of the facilitators (thank you Martin) and filter out a lot of the channels from the Unicorn. Also, the Unicorn device isn't 100% accurate, sometimes we would get readings from -2000 to infinity while testing, which shows that even the most reliable code can sometimes be thwarted by a small hardware error, such as the VIVE headset putting pressure on the nodes which caused huge spikes in the EEG. We also had to find a way to get the EEG readings into useable data for Unity, just imagine getting your heartbeat EKG and turn that into something useful. Finally, we also faced a lot of GitHub issues when trying to push or pull code to a point where we had to switch to Unity Collab (GitHub version of Unity).

## What we did

So, our approach was to enable scene designers to create BCI VR/Games with less Unity C# development. SO, we encapsulated BCI data streams in Unity Scriptable Objects enabling Scene Designers to compose application in Unity Editor rather than coding C#. In other words, we made scripts that would make it easier for future developers to use to make it easier to make games for Unity instead of wasting time on doing what we did and making scriptable objects. So, our team found a way to get LSL data from the Unicorn through Simulink and have that data sent as UDP data to Unity through a script to receive data packets and set as circular buffers in scriptable objects. In other words, we got continuous streaming data from the Unicorn into our game. Finally, we had only enough time to make a small game called: Brain Breakout where the goal of the game is to relax to a point where you could telepathically knock over boxes. The calmer you were the faster you could knock down boxes through the VIVE headset. 

## Experience from this hackathon

One of the biggest thing that happened in this hackathon is that I won 2nd place! It felt great to win and I'm excited to attend future hackathons. Anyway, some of the biggest thing that I learned from this hackathon is the brain waves that our brain produces. For example, while we are awake and active we get alpha waves, if we are awake and resting we get beta waves, if we are sleeping we get theta waves and when we're in deep sleep we get delta waves. It was also interesting to learn how our brain works on the EEG screen, alpha waves are similar across the board and each wave have different Hz that are produced or how our brain registers an image before we can register it. Finally, I learned a lot of new Unity tips and code from my teammates that helped me during the hackathon. Unfortunately, we ran out of time and we could only make one part of the game but nevertheless I had a lot of fun testing out our build. 

## What I would do next time

The attendance was low in this hackathon and next time I would try to encourage and invite others to attend the hackathon. I also would practice more on using Unity before the hackathon. During this hackathon a lot of our time was dedicated into figuring out how the Unicorn worked, Simulink and how to send data from the Unicorn to Unity. Perhaps some instructional videos on Simulink before the hackathon may have helped me beforehand. One thing that I wish I had more in this hackathon was time, I always find myself lacking the time to do the stuff that I want. 

## Conclusion

In conclusion, as much as EEG's or BCI's are a new thing to me, I enjoyed the hackathon a lot. It was a unique experience and I would attend again next year. I also learned a lot about new medical knowledge of the brain and some Unity tips from my teammates. It felt good to win 2nd place in the hackathon but in the end its how much you've gained from knowledge than the prize money.

Here are also some links to my slide presentation of the hackathon and the projects page:

*requires UH Login or invitation* 

<a href="https://docs.google.com/presentation/d/1qGMmZckSgD-ZhXJu-6RnRfd9q0-GP7KBTcf9U5wOa-A/edit?usp=sharing"><i class="large google icon "></i>Presentation Slides</a>

<a href="https://jjhna.github.io/projects/BR41N"><i class="large github icon "></i>BR41N project page</a>

<img class="ui image" src="../images/Experience.png">

*As I state AGAIN: Experience is the best teacher in the world*
