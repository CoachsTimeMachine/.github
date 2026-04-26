<div align="center">
<h2>CTM is a work in progress effort. Stay tuned!</h2>
<img src="https://avatars.githubusercontent.com/u/274413706" width="128" height="128">
<h1>Coach's Time Machine</h1>
</div>

Coach's Time Machine (abbreviated CTM) is a collection of open source patches, utilities, and servers for old Rec Room builds.

Naming scheme follows the formula `Type.Name` (example: `server.2017E`).

<sup>Yeah, i'm following the Roblox client naming scheme for my releases. I will still refer to Rec Room builds by their proper release. It's easier to call server releases E, M, L.</sup>

The default license for any CTM projects is [AGPLv3 license](https://github.com/CoachsTimeMachine/.github/blob/main/LICENSE) unless otherwise specified.

# Patches

| Name | Description |
|------|-------------|
| [DebugCameraControl](https://github.com/CoachsTimeMachine/patch.debugcameracontrol) | Small patch for early Rec Room builds to allow DebugCameraControl ("screen mode") inputs. |

# Utils

| Name | Description |
|------|-------------|
| [PhotonPatcher](https://github.com/CoachsTimeMachine/util.photon-patcher) | In-browser Photon PUN and Voice patcher. |

# Server

All servers are created with Bun and Typescript.

> [!IMPORTANT]  
> ### Coach's Time Machine servers are **not designed for production use.**
> 
> These servers are designed to be basic enough get builds working again.
>
> The ideal use for CTM servers is personal and small scale usage (like with friends). You can also use it as a "template" to build your own servers from.
> 
> If you don't know what "production use" means, you probably shouldnt try making a Rec Room revival.

## Compatability List

Detailed breakdown for current CTM support. If your build isn't listed here, it probably isnt supported yet.

In cases of reuploaded builds, the **latest revision** is used.

Dates may not 100% line up with their [Steam announcement](https://store.steampowered.com/news/app/471710).

---

> [!CAUTION]
> **2016 servers are insecure!!!** Do not host any servers from this version publicly.

<details>
<summary>2016 releases</summary>

| Date | Manifest | Server | Notes |
| ---- | -------- |--------|-------|
| 28 June 2016 | 4180590405597713716 | N/A | † |
| 29 June 2016 | 7926661550074548930 | N/A | † |
| 30 June 2016 | 5937396277352677720 | N/A | † |
| 6 July 2016 | 5234716332756009057 | N/A | † |
| 8 July 2016 | 675319925160172554 | N/A | † |
| 13 July 2016 | 2793222674831519927 | N/A | † |
| 20 July 2016 | 1105116417500379163 | N/A | † |
| 22 July 2016 | 2224171743476188630 | N/A | † |
| 27 July 2016 | 797475839536905254 | N/A | † |
| 29 July 2016 | 3601417244482181468 | N/A | † |
| 2 August 2016 | 356844315186453937 | N/A | † |
| 11 August 2016 | 20170328095030222 | CTM-2016E | |

<sub>† Pre-RecNet, only requires Photon patch. MOTD patch optional (http://www.againstgrav.com/motd in `IntroActivityManager`)</sub>

</details>

> [!CAUTION]
> **Early 2017 builds are insecure!!!** Do not host any servers from versions marked with ⚠️ publicly.

<details>
<summary>2017 releases</summary>

| Date | Manifest | Server | Notes |
| ---- | -------- |--------|-------|
| TBA  | TBA      | TBA    | ⚠️    |

<sub>⚠️ Insecure. Don't host publicly.</sub>

</details>
<details>
<summary>2018 releases</summary>
  
| Date | Manifest | Server | Notes |
| ---- | -------- |--------|-------|
| TBA  | TBA      | TBA    |       |

</details>
