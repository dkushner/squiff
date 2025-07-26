# Squiff
*The famous ArmA scripting language, immortalized.*

## Origins
I've spent a great deal of my life creating, modifying and playing missions in the video game ArmA by Bohemia Interactive. It's been a touchstone of my friend group for over a decade and I've come to cherish every experience, no matter how jank. In this process, I've become familiar with the bespoke scripting language Bohemia uses across these games: SQF. 

```admonish info 
Okay, technically it started with SQS (Status Quo Script) with Operation Flashpoint which developed into SQF (Status Quo Function) over time.
```

## Purpose
This project is largely just an experiment with Rust, interpreters and VM design. SQF itself seems to have been built in the same spirit: curiosity and experimentation. Why else would an established studio create their own bona fide scripting language over integrating with some proven and existing language like Lua? 
In my experience creating sprawling Arma 2/3 missions I have fought with SQF extensively and have come to know it intimately. 

Let me be clear, SQF is not a *good* language. It was clearly created for the express purpose of enabling dedicated enthusiasts to manipulate ArmA into the gaming experience they envisioned. It was also clearly created by a group of (exceptionally talented) game developers working under harsh deadlines. Still, I think the core of the language itself possesses the potential to be a fun little toy, so I'm building it. I'm stripping out the stuff that only makes sense in the context of ArmA itself and trying to add more general-purpose functionality. I'm reinterpreting the intent of the original developers in order to make something at least slightly useful.