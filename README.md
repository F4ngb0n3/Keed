# Keed
The official documentation for the Keed Minecraft Plugin

_Minecraft Home Security Plugin_

**Keed** is a SUPER simple approach to home security in your Minecraft server! With a couple commands and a single config value, your players can ensure that their doors are locked to ONLY them, keeping their valuables safe and secure whilst they romp aboot.

**How To:**
1. Walk **_RIGHT_** up to a **CLOSED** door _(Get all up in its business)_
2. Use the `/claimhome` command whilst staring the door down
3. **(O.P. / Perms Only):** Use the `/claimhome [player]` command to give the home to a player
4. **Abadnoning Only:** Same Step 1, and use the `/abandonhome` command.
5. **(O.P. / Perms Only):** Use the `/abandonhome [player]` command to give up the home
####  

## Config
| Key | Value | Description |
| --- | ----- | ----------- |
| prefix | "&c[&fKeed&c]&f >> " | The prefix prepended to each plugin message displayed to Players |
####  

## Commands
| Command | Args | Permission | Description |
| ------- | ---- | ---------- | ----------- |
| /claimhome | [player] | With [player] arg = keed.setowner / Without arg = keed.myhome | Allows a Player to claim a **SINGLE** home for themselves, or an O.P. or permed player to set additional homes for that Player |
| /abandonhome | [player] | With [player] arg = keed.removeowner / Without arg = keed.myhome | Allows a Player to abandon their home themselves, or an O.P. or permed player to remove the home for that Player |
####  

## Permissions
| Permission | Description |
| ---------- | ----------- |
| keed.myhome | Default for ALL Players. Allows them to claim / abandon a SINGLE home for themselves |
| keed.setowner | Allows a Player to set additional homes to a Player. Default for O.P. |
| keed.removeowner | Allows a Player to remove homes belonging to a Player. Default for O.P. |
####  

## Support
F4ngdev is always working tirelessly to ensure quality functional plugins, and should any questions or needs arise, we invite you to open a support ticket here on the CakeSMP Github where we can manage and get all things plugin related handled. If this forum isn't working for you, we always have the [F4ngdev Discord](https://discord.gg/k28sR69n5f) where everything plugin and development related is open-discussion.
