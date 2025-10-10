# Global - Google Play and Epic Games - Genshin

Certain links can get in different languages like Vietnamese, Japanese, Korean, Flipinos, etc

On some links, add either one of these two:

```json
&lang={lang}
```

```json
&language={lang}
```

Note: Epic use a different sub_channel ID and cps ID than Google in the game's `Game_Data/config.ini`

## Google Play

```json
channel=1
sub_channel=6
cps=pcgoogle
```

## Epic Games

```json
channel=1
sub_channel=3
cps=pcepic
```

[Game Configs](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGameConfigs?launcher_id=8fANlj5K7I)

[SDKs - Epic](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGameChannelSDKs?launcher_id=8fANlj5K7I&channel=1&sub_channel=3)

Google Play does not have SDK as it's integrated in HoYo Login SDK. You will be asked to login to Google Play to verify your safeguard.

[Deprecated Files](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGameDeprecatedFileConfigs?launcher_id=8fANlj5K7I)

[Game Branches & Sophon](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGameBranches?launcher_id=8fANlj5K7I)

[Game Packages](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGamePackages?launcher_id=8fANlj5K7I)

[NEW - Mandatory Module Packages](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getWPFPackages?launcher_id=8fANlj5K7I)

[Game Plugins](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGamePlugins?launcher_id=8fANlj5K7I)

[Game Status](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGames?launcher_id=8fANlj5K7I&language=en-us)

[Game Executable Scan Check](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGameScanInfo?launcher_id=8fANlj5K7I)

[Game Events](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getGameContent?launcher_id=8fANlj5K7I&game_id=gopR6Cufr3&language=en-us)

[Background and Basic Info](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getAllGameBasicInfo?launcher_id=VYTpXlbWo8)

[Notification Alert](https://sg-hyp-api.hoyoverse.com/hyp/hyp-connect/api/getNotification?launcher_id=VYTpXlbWo8&language=en-us&type=NOTIFICATION_TYPE_RED_DOT)
