# Hemingway Mode Karabiner Config

This small config Karabiner config helps writers to put asleep their internal editor. So you just can get drunk. Edit later.

> Write drunk, edit sober.
>
> -- <cite>Ernest Hemingway</cite>

Technically it just disables any backspace handling, allowing only alt+backspace to backward delete whole words.

1. Install Karabiner
2. Set it up
3. Tune up MacOS Security settings to allow Karabiner handle system level events
4. Clone this repo, unzip it and run Terminal app
5. `$ cd hemingway_mode_karabiner`
6. Copy config to Karabiner complex modifications folder: `$ cp ./hemingway_mode.json ~/.config/karabiner/assets/complex_modifications/`
7. Edit Karabiner preferences → Profiles to create new Profile. Name it "Hemingway mode".
8. Activate it when you need "get drunk". Disable when need to "get sober".