
# faek station
=======
<img width="1116" height="392" alt="rebase" src="https://github.com/user-attachments/assets/91eccd27-9618-46ac-9d58-e67e2e9b0a42" />

# End Of Life Notice: Repository Rebase in Progress
This project is currently in process of being rebased on top of delta-v. This repository is no longer maintained and will be archived after our main server changes around 1st of March, 2026. Our new repository URL is https://github.com/Floof-Station/Panta-Rhei/ .

## Why are we doing this?
- First off, Wizden is planning to [dehub all servers that use an engine version older than 1 year](https://forum.spacestation14.com/t/we-will-now-have-an-engine-support-period-old-servers-must-update/25672/1), starting on the 1st of march, 2026. This means that this project cannot continue existing unless we upgrade 30+ engine versions up.
- We cannot update our engine version because of massive codebase incompatibilities. And we cannot merge wizden changes because EE made its codebase incompatible with wizden. And we are an EE fork.
- We cannot merge EE because our design and principles have diverged. EE focuses on writing sloppy code and unmaintainable code, and starting somewhere in 2025 began targetting LRP forks rather than MRP+ as its founders intended. Also, we are so far behind that even if we were to just merge with EE, it'd take us months to catch up.

As such, we've decided to rebase on top of Delta-v, the fork of Space Station 14 that Einstein Engines, the upstream of this fork, was based on.

This is a manual rebase, meaning that we are porting existing content on top of the delta-v codebase.

## Differences

\+ Work at a Pizza Place emote sounds, snd_ominous and snd_ominous_cancel emote sounds, boowomp sound for frowning

\+ Knuckle cracking emote sounds

\+ Icarus Winters moth plushie / Error plushie

\+ Some picky grammar fixes that nobody else cared enough about to fix

\+ Tarazicon honeymoth chemical

\+ Questionable legal practices

\- Players and contributors (I eated them they're all gone)

## About

Some images and / or sounds that reference popular meme culture in this project are not licensed under Creative Commons.

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
