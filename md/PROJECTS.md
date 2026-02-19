## DIVISOR

    Scope

        Computer software
        Consumer‑grade hardware target
        Mid-range devices (Laptop/Desktop)
        Open source
        Generative AI
        Local & offline generation
        Diffusion models only
        Flow‑match schedulers
        Multimodal output support


    Philosophy

        Diffusion is a Journey: Walk your own path
        Principally Subjective: Output is complete when the operator declares it
        Feedback: Tangible, rapid system feel. Instantaneous creativity demands instant tools
        Keep Flow State: Perpetuate the disruptive and unique as long as possible
        Transformation & Iteration: Exploration over refinement
        The End Game: Tractable chaos equilibrium


    Objectives

        Step‑wise diffusion: edit parameters while generating (live latent walk)
        Generation window: ≤1s inference for all use‑cases
        Intermediate Preview = Final Product: always display/save current state
        Input: adjust all parameters within the time for Generation window
        Corruptions: ≥10 significantly transformative parameter adjustments (one per finger)
        Code: abstracted from model frameworks, generalizable to any diffusion modality
        Hackable & Branching: Reversible and revisionable output
        Create Value: Store and share every edit and the process leading to it

Related readings:
https://diffusionflow.github.io/
Diffusion Meets Flow Matching
Flow matching and diffusion models are two popular frameworks in generative modeling. Despite seeming similar, there is some confusion in the community about their exact connection. In this post, we aim to clear up this confusion and show that <i>diffusion models and Gaussian flow matching are the same</i>, although different model specification...

Shadowbox
What it does -

---

    Its an ML system that runs models using the fastest library per system type
    No-code system, self-arranges to run more models than I even know about
    It creates images and generates text
    Its totally local and offline (ie private)
    As libraries update, it immediately supports them

## Where we are -

    We are able to recognize any kind of open source AI model in Transformers, Diffusers, and GGUF, and some MFLUX/MLX, ONNX models too
    All models supported run right out of the box with no questions asked
    We are able to generate several types of media with no configuration required

## Why we are here -

    share workflows certain to work on any computer (impossible w/o docker & even often with)
    create optimized, auto-arranged workflows
    hand this system to a non-experienced person and they can use it
    allow people to explore with guidance from the system with no fear of breaking it
    concentrates and distributes legacy model knowledge
    future proof due to versatility of upstream channels, always-up-to-date
    deeply reduce complexity and learning required to get to peak performance with any model (otherwise impossible), and then automate its construction per system

## Are we there yet? -

    For this to run at all/have any purpose on most computers, it needs :

    memory management - component recognition done, pipe needs to sequentially load
    model chaining - automatic chaining of models towards specific tasks

## Goals -

    add more libraries and the ability to install them via sdbx
    add a fuck ton of upscale/3d/audio/svg/midi models etc (things that arent already recognized by diffusers/transformers/etc)
    modularity - tasks need to be dynamically looked up and added to model chain
    deep analysis of models

https://darkshapes.org/docs/divisor/divisor/
https://darkshapes.org/docs/zodiac/zodiac/
https://darkshapes.org/docs/mir/mir/
https://darkshapes.org/docs/nnll/nnll/
