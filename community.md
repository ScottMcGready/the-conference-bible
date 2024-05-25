> TBC: Discord template link, carlbot setup

# Community

The vast majority of conferences now use Discord as the tool of choice when it comes to community engagement however other platforms (such as Slack) have been used successfully. Choose a platform that works best for you, your team, and your conference "feel" rather than the popular tool. Whatever you choose, it should be relatively easy to manage, moderate, and engage with your community.

## Automated template

TBC


## Manual setup

Discord makes it incredibly easy to create a new server. Simply open the app, and click the plus **"Add a server"** icon. From here click **"Create your own"** and **"For a club or community"**. Name your server something appropriate (the name of your conference is usually fine) and that's it done!


## Best practices

### Bots

![Discord Carlbot](/assets/discord-carlbot.png)

Bots can take over a lot of the management overhead of your server. It's highly recommended to use something like [carlbot](https://carl.gg) to help with moderation and automated tasks (such as assigning roles automatically upon joining or after interacting with certain posts.

![Discord Carlbot autoroles](/assets/discord-carlbot-roles.png)

### Enabling MFA for administrators

![Discord enable MFA](/assets/discord-enable-mfa.png)

Administrator accounts should be protected using MFA to ensure no malicious actions are taken in the event an admin account is compromised.

Enabling MFA is an automatic requirement if your server is in [Community mode](https://discord.com/community).

### Disabling @everyone

![discord @everyone](/assets/discord-everyone.png)

Unnecissary pings are annoying. Consider disabling the ability for non admin/moderator roles to be able to mention @everyone.

If you need to, you can enable "allow users to ping this role" for specific roles, which allows members to ping a moderation group or speaker group.

> **Note:** You'll need to do this for every role in your server up to the highest role you want to allow the @everyone ping.

### Role based access

![Discord roles](/assets/discord-roles.png)

Discord uses roles to control access to various channels and categories. Roles can also be purely "for show", these are known as [vanity roles](#vanity-roles), but can add a level of community spirit to your server. It's recommended to always use role based access, rather than adding users into a category or channel directly.

While permissions can be synced for an entire category, making management of the channels within it a bit easier, there may be some cases where you want or need different permissions for various channels within the category.

Users' handle will be the colour of the highest role they have. This can be useful if you want to visually define who's staff, speaker, or vendors for example.

> **Important:** Discord roles are hierarchical. This means that you may have to be careful where the role sits in the list so you don't override other role permissions, or worse - give someone more access to something than they need. To read more about roles, read the [Discord guide](https://support.discord.com/hc/en-us/articles/214836687-Role-Management-101).

### Transferring ownership to a breakglass account

![Discord crown](/assets/discord-crown.png)

If you've ever logged into a discord, you might have noticed one user has a little crown beside their name. This crown indicates that user is the server owner. If you're running a decent sized community server, it's worthwhile considering transferring the full blown owner permission to a generic "in case of emergency" style account.

This account should only be used for breaking changes but also removes the risk of an administrator accidentally (or maliciously) deleting the entire discord.

### Transparency

![Discord transparency](/assets/discord-transparency.png)

Sometimes things happen - be that server tweaks or members being kicked from the discord for various reasons. Consider having a transparency log to let members know what actions are taken, by which moderator, and why.

### Vanity roles

![Discord roles](/assets/discord-roles.png)

Vanity roles are exactly what they sound like - a vanity tag. These can be semi-serious tags (such as former speakers, or former members of the committee) or purely for entertainment purposes.