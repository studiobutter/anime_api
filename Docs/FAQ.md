# Why this repo was made

This Repository is meant for reseaching the Launcher inner workings and helping players do manual downloads. (i.e: Collapse Launcher, Snap Hutao, Starward) (not affiliate)

# Why is there more than one version of HoYoPlay

Contract and Complience, marketing and testing. They have some contracts to following if they want to add those games to other store (i.e: Epic Games Store requires the Epic Games Launcher and uses Epic Payment system, Google Play Games for PC requires to use Google Payments, BiliBili requires using BiliBili login and payment, seperate server on certain games and their own payment system)

# Will there be Beta API

No and Never.

# Why ZIP Packages no longer support?

As of October 23rd, HoYo have fully deprecated the ZIP package download mode from main use in favor of the better download system call Sophon which download game packages in segments, combining them, extracting and patch the game on the fly instead of waiting for indiviual step to complete.

With that, Manual Download is no longer supported. If you wish to download the game. Use the official launcher or the open source ones to continue.

- [Collapse Launcher](https://collapselauncher.com/)

- [Starward Launcher](https://github.com/Scighost/Starward)

I can't provide how to implement Sophon Download system, you can find resources [here](../Sophon/Imp.md)

ZIP Package system will still be use for the following:

- Launcher Plugin Package

- WPF Module Package (Genshin Impact's Miliastra Sandbox)

# What's WPF?

It's a new package endpoint for adding Game-Based Modules (i.e: Genshin Impact's Miliastra Sandbox)
