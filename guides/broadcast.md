# Broadcast

> This guide assumes Zoom and Twitch are the broadcast tools of choice. Other tools are available and some may perform better, or be better suited to your needs. It's worth researching each one in depth to understand if it will work for your specific circumstances.

## Broadcast setup

It is recommended to have use the main Zoom meeting as the **green room** where speakers, and volunteers, can join without impacting the live broadcast. For the **broadcast room**, it is recommended to set up a "breakout room" (ensure breakout rooms are enabled for your meeting). Volunteers should be in the main **green room** welcoming speakers who have just joined, testing their slides/audio before broadcast, calming any nerves, and communicating with the hosts in the **broadcast room**.

If you're running a hybrid conference, it's worth making sure a few volunteers in the **green room** and **broadcast room** are in a quiet location, rather than them hearing feedback or the hustle bustle of the conference itself.

### Virtual conference broadcast setup

The following diagram assumes the conference is running purely virtually, where everyone (in effect) is a remote speaker, including the hosts.

![Broadcast setup](/media/broadcast-setup-remote.png)

### Hybrid conference, remote speaker broadcast setup

Both straightforward surprisingly complex, remote speakers with live audiences can be a bit of a headscratcher at first. Ensure you have a decent enough microphone that can pick up the host and audience questions (something handheld is ideal but hosts can always repeat audience questions), and a decent enough camera so the remote speaker can see the host / audience. 

![Broadcast setup](/media/broadcast-setup-hybrid.png)

### In-person broadcast setup

Remarkably, if you have a setup similar to that of Cooper's, it's incredibly easy to take a feed from OBS and broadcast it via any streaming platform. If you are running an event that doesn't have access to Coopers rigs, or and recording equipment, the following rough guide should be enough.

![Broadcast setup](/media/broadcast-setup-in-person.png)

### Breakout rooms

There are a few options that need to be checked in order for speakers to be able to present, without issue, inside a breakout room. Breakout Room setup should be as follows:

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