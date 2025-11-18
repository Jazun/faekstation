# faek station

## Differences

\+ Work at a Pizza Place emote sounds

\+ snd_ominous and snd_ominous_cancel emote sounds

\+ Icarus Winters moth plushie / Error plushie

\- Players and contributors

## About

faek station is a friend-only server of the game [Space Station 14](https://spacestation14.com/).

faek station is a fork of the server [Floof Station](https://github.com/Floof-Station/Floof-Station) (https://github.com/Floof-Station/Floof-Station).

Floof Station is a fork of [Einstein-Engines](https://github.com/Simple-Station/Einstein-Engines).

## Building

Refer to [the Space Wizards' guide](https://docs.spacestation14.com/en/general-development/setup/setting-up-a-development-environment.html) on setting up a development environment and for general information. But do keep in mind that Einstein Engines, the codebase Floof Station is based on, is an alternative codebase to the base one provided by WizDen, and many things may thus not apply nor be the same.
We provide some scripts shown below to make the job easier.

### Build dependencies

> - Git
> - .NET SDK 9.0.100


### Linux

> 1. Clone this repository
> 2. Run `git submodule update --init --recursive` in a terminal to download the engine
> 3. Run `Scripts/sh/buildAllDebug.sh` after making any changes to the source
> 4. Run `Scripts/sh/runQuickAll.sh` to launch the client and the server
> 5. Connect to localhost in the client and play

### Windows (You Should Switch To Linux)

> 1. Clone this repository
> 2. Run `git submodule update --init --recursive` in a terminal to download the engine
> 3. Run `Scripts/bat/buildAllDebug.bat` after making any changes to the source
> 4. Run `Scripts/bat/runQuickAll.bat` to launch the client and the server
> 5. Connect to localhost in the client and play

### MacOS

> No
> 
> Screw apple all my homies hate apple

## License

Please read the [LEGAL.md](./LEGAL.md) file for information on the licenses of the code and assets in this repository.
