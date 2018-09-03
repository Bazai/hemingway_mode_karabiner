# Hemingway Mode Karabiner Config
![Ernest Hemingway](http://ykl-res.azureedge.net/7951c4f4-c179-4943-a39b-2f859e713399/1.png)

This small config Karabiner config helps writers to put asleep their internal editor. So you just can get drunk. Edit later.

> Write drunk, edit sober.
>
> -- <cite>Ernest Hemingway</cite>

Technically it just disables any backspace handling, allowing only alt+backspace to backward delete whole words.

## Installation
1. Install [Karabiner](https://pqrs.org/osx/karabiner/)
2. Set it up
3. Tune up MacOS Security settings to allow Karabiner handle system level events
4. Clone this repo, unzip it and run Terminal app
5. `$ cd hemingway_mode_karabiner`
6. Copy config to Karabiner complex modifications folder: `$ cp ./hemingway_mode.json ~/.config/karabiner/assets/complex_modifications/`
7. Edit Karabiner preferences → Profiles to create new Profile. Name it "Hemingway mode".
8. Activate it when you need "get drunk". Disable when need to "get sober".
