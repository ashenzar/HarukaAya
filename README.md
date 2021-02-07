# Synthetic Doll

![](images/haruka_banner.png)

SyntheticDoll is an open source Telegram group manager bot, this is a modular based 
Telegram Python Bot running on Python3 with sqlalchmey database.

This bot can be found and used on telegram as [Yumeko](https://t.me/SyntheticDollBot).
 
-------------------------------------------------------------------------------------


## Installation

<p align="center">
  <a href = "https://heroku.com/deploy?template=https://github.com/ashenzar/SyntheticDoll/tree/main"><img src="https://telegra.ph/file/57c4edb389224c9cf9996.png" alt="Press to Takeoff" width="490px"></a>
</p>

Click in the button above and fill the required vars.

#### How can I obtain `TOKEN`?

Just talk to [BotFather](https://t.me/BotFather) (described [here](https://core.telegram.org/bots#6-botfather))
and follow a few simple steps. Once you've created a bot and received your
authorization token, that's it! that's your `TOKEN`.

#### How can I obtain a `API_KEY` and `API_HASH`?

In order to obtain an API key and hash you need to do the following:

 - Sign up for Telegram using any application.
 - Login to your Telegram core: [https://my.telegram.org](https://my.telegram.org).
 - Go to '[API Development tools](https://my.telegram.org/apps)' and fill out the form.
 - You will get basic addresses as well as the `api_id` and `api_hash` parameters 
   required for Haruka's configuration file.

### Docker 

Run with docker! you can a local instance of Yumeko from the production branch
using the [Dockerfile](Dockerfile)

```shell
docker build -t="haruka" -f Dockerfile .
docker run -t --name haruka --restart always haruka
```

### From source

```shell
pip install -r requirements.txt
python -m haruka
```

-------------------------------------------------------------------------------------

## Branch purposes

SyntheticDoll will have multiple branches for different purposes, these are the
main branches you should understand before contributing to this project.

 - `main` This is the branch that uses the bot, I'll try to keep it as sstable as possible.

 - `dev` I use this branch for testing before pushing to main.
   
Any other branches should be treated as work in progress features that is currently
being worked on to release to production.

## Contributing to the project
 - You must sign off on your commit.
 - You must sign the commit via GPG Key.
 - Make sure your PR passes all CI.

## Thanks to
 - Intellivoid - Team that currently supports Haruka
 - RealAkito - Original Haruka Aya Owner
 - [Davide](https://t.me/DavideGalileiPortfolio) - For designing and creating Haruka Aya's display picture and banner
 - zakaryan2004 - For helping out a lot with this project.
 - MrYacha - For Yana :3
 - Skittle - For memes and sticker stuff.
 - 1mavarick1 - Introducing Global Mutes, etc.
 - AyraHikari - Reworked Welcome, Fed v2
 - Paul Larsen - Marie and Rose creator

And much more that we couldn't list it here!
