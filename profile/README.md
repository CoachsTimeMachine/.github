<div align="center">
<h2>CTM is a work in progress effort. Stay tuned!</h2>
<img src="https://avatars.githubusercontent.com/u/274413706" width="128" height="128">
<h1>Coach's Time Machine</h1>
</div>

Coach's Time Machine (abbreviated CTM) is a collection of open source patches, utilities, and servers for old Rec Room builds.

Naming scheme follows the formula `Type.Name` (example: `server.2017E`).

<sup>Yeah, i'm following the Roblox client naming scheme for my releases. I will still refer to Rec Room builds by their proper release. It's easier to call server releases E, M, L.</sup>

The default license for any CTM projects is [AGPLv3 license](https://github.com/CoachsTimeMachine/.github/blob/main/LICENSE) unless otherwise specified.

## The Team

### stuartt ([RealMCoded](https://github.com/RealMCoded))

*"Back in January 2023 I created Rec.js, a FOSS replacement for OpenRec - designed for tinkering. In May 2023, I created LunarRec, another FOSS replacement for OpenRecLive - designed as a live server. 3 years later, I'm starting the Coach's Time Machine project to celebrate classic Rec Room. And yes, it's all FOSS."*

<sup>FOSS = Free Open Source Software</sup>

<sub>at the moment i am the only team member... sob</sub>

## Motivation

Compared to LittleBigPlanet server projects (the two most popular ones are open source), Rec Room server projects are usually always closed source. As someone who believes in open source software, I want to see that change.

CTM won't be the best, we aren't claiming the best, but I beleive this will be a great "first step" in open sourcing information, without taking from other projects.

# Patches

Patches for BepInEx or MelonLoader, written in C#.

| Name | Loader | Description |
|------|--------|-------------|
| [DebugCameraControl](https://github.com/CoachsTimeMachine/patch.debugcameracontrol) | BepInEx | Small patch for pre-Screen Mode Rec Room builds to enable DebugCameraControl ("screen mode"). |

# Utils

Misc. Rec Room related tools.

| Name | Description |
|------|-------------|
| [PhotonPatcher](https://github.com/CoachsTimeMachine/util.photon-patcher) | In-browser Photon PUN and Voice patcher. |

# Servers

Servers are created with Typescript and [Bun](http://bun.com/). I am aiming for servers to be as period correct as possible (e.g. item unlocking, progression, registrations*) with as many features working again (e.g. custom rooms in mid-2017).

<sup>\* emails are not sent and registations auto complete after a few seconds.</sup>

A compatability list for servers can be found [here (COMPATABILITY.md).](https://github.com/CoachsTimeMachine/.github/blob/main/COMPATABILITY.md)

> [!IMPORTANT]  
> ### Coach's Time Machine servers are not designed for production use.
> 
> These servers are designed to be basic enough get builds working again. Every server is designed to work for multiple connections though (this aint OpenRec or RecJS).
>
> The ideal use for CTM servers is personal and small scale usage (like with friends). You can also use it as a "template" to build your own servers from.
> 
> If you don't know what "production use" means, you probably shouldnt try making a Rec Room revival.
