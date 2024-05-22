# Broadcast

> This guide assumes Zoom and Twitch are the tools of choice. Other tools are available and some may perform better or be better suited to your needs. It's worth researching each one in depth to understand if it will work for your specific circumstances.

## Broadcast setup

It is recommended to have the main Zoom meeting room as a "**green room**" where speakers, and volunteers can join without impacting the live broadcast. Setting the **broadcast room** up as a breakout room. Volunteers should be in the main **green room** welcoming speakers who have just joined, testing their slides/audio before broadcast, calming any nerves, and communicating with the hosts in the **broadcast room**.

![Broadcast setup](/media/broadcast-setup.png)

**Note:** There are a few options that need to be checked in order for speakers to be able to present without issue inside a breakout room.

### Breakout rooms

Breakout Room setup was as follows:

- Allow participants to choose room (**UNCHECKED**)    
- Allow participants to return to the main session at any time (**CHECKED**)
- Automatically move all assigned participants into breakout rooms (**CHECKED**)
- Auto close breakout rooms after [XX] minutes (**UNCHECKED**)
- Countdown after closing breakout room (**UNCHECKED**)

Breakout rooms, after being created, needed to be “opened” in order to be accessible to all participants. An occasional bug, requiring speakers to be given the Co-Host role in order to share their screen in a breakout room, may rear its head. It's recommended to check the meeting settings _before_ creating breakout rooms to allow screen sharing by default. 

**Note:** giving speakers Co-Host role may seem dangerous however they "cannot end meeting for all" so long as a host is in the room at the same time.

### The hidden participant

It's recommended to have a dedicated machine that's sole purpose is to broadcast the contents of the broadcast room. This machine requires broadcast software (such as OBS), a stable internet connection, and will be required to join the broadcast meeting room as an "observer".

Some settings within Zoom need to be adjusted in order for this hidden participant to go unnoticed.