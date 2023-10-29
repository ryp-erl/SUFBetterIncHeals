<img src="https://github.com/ryp-erl/assets/blob/main/ShadowedUF_BetterIncHeals/suf-betterincheals-wotlk.jpg?raw=true" width=100 align="right" />


# Shadowed UF - Better Incoming Heals

Provides better incoming heals on Shadowed Unit Frames for Wrath of the Lich King Classic.

## Explanation

If you installed Shadowed Unit Frames (SUF) for Wotlk Classic, you probably noticed that it only indicates incoming direct heals, ignoring heals over time (HoT) as well as beacon of light (BoL).

At the time of writing, the curseforge page for SUF in Wotlk Classic, you can find the following information:
> **Incoming Heals**: Supports the Blizzard Events for incoming heal data, no external libraries needed

So, I believe this behavior is due to some limitation with Blizzard API for Wotlk Classic. Therefore, I wrote this addon for SUF using the LibHealComm library to replace the current behavior and support HoT & BoL.

## Other addons

- [AutoLoggerWotlk](https://www.curseforge.com/wow/addons/autologgerwotlk/): Automatically start combat logging when entering a Wotlk raid.
- [Raiduku](https://www.curseforge.com/wow/addons/raiduku/): Minimalist World of Warcraft addon to help raid leaders managing loots in Wrath of Lich King Classic.

## License

[GNU GPLv3](LICENSE)