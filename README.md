# DS Orchestra Complete Community Edition

DS Orchestra Complete Community is an open source version of the [DS Orchestra Complete](bit.ly/DS-OC) by Shovan Das

## How to use

You need the [Decent Sampler](https://www.decentsamples.com/product/decent-sampler-plugin/) free vst to use this instrument

Download this repository and extract it into your `Sample Library` folder

The folder name should be `DS-Orchestra-Complete-CE`

> [!TIP]
> The default `Sample Library` path is:
>
> `%appdata%\Decidedly\DecentSampler\Sample Libraries`

The path to your `1st Violin Section` should be `C:\Users\USERNAME\AppData\Roaming\Decidedly\DecentSampler\Sample Libraries\DS-Orchestra-Complete-CE\Modwheel Controlled\01 String\01 1st Violin\01 1st Violin Section - Staccato.dspreset`

## About

This library has a Velocity Controlled and a Modwheel Controlled version

### Velocity Controlled

The Velocity Controlled version listens to the note velocity and change its dynamics based on that

### Modwheel Controlled

The Modwheel Controlled Version listens to the note velocity and change its dynamics based on that

## FAQ

### Why is Sustain separated into `Sustain Attack` and `Sustain Legato`

Most of the time there is no need to use both
Decent Sampler can handle legato in a single instrument and `Sustain Attack` works for both

So, when using the `Sustain Attack` instrument, while you hold a note, the next notes will be the same as `Sustain Legato` notes (without an attack) until you release all notes and press a new one

However, this system of overlapping notes is the same used for portamento (sliding notes)
So if you want to have control of portamento and legato individually, use `Sustain Attack` and `Sustain Legato` as articulations in 2 different instruments and use the same portamento settings in both of them
