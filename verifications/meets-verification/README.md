---
description: Seeds, Connection parties and meeting schedules
---

# ↔ Meets Verification

The Meets verification is the first and the most basic verification protocol/mechanism BrightID project has had since the beginning. For a long time it had been the only verification. [Bitu](../bitu-verification.md) and [Aura](http://127.0.0.1:5000/o/-Mk6LhpUAwiJGeZ-g2uM/s/jGtnCGfucgnFNbDgcdxy/) verifications are recent developments.\
\
The social identity network that BrightID project set out to build had a cold start problem. The graph needed to be seeded with people and their relations before higher level verifications could be built upon them. No existing social graphs fit the bill at the time when BrightID began, so Meets protocol mechanism was built for the purpose. While BrightID was never meant to settle on the verification protocol, it is still the widely used verification. The characteristic verification parties of the protocol is what most people have gotten to know BrightID by and the perception is up for change in the mid future with Aura.\
\
So far, when any one of the app in the BrightID app registry asks the public to connect their BrightID, it is checking whether the public has ever received the Meets verification. In that way Meets plays an important role until Aura takes off.

It is to be noted again that Meets protocol mechanism is an exception, and BrightID is meant to enable truly social identity network where one's identity depends upon, and is secured by, one's own close connections. The project has not reached that goal yet, but it should get there with [Bitu](../bitu-verification.md) and more specifically, [Aura](http://127.0.0.1:5000/o/-Mk6LhpUAwiJGeZ-g2uM/s/jGtnCGfucgnFNbDgcdxy/).

### How Does Meets work?

The Meets protocol mechanism works by the member of the public making a connection with one of the special set of people called Hosts. Internally the protocol calls them Seeds. "Seed" actually shows up as a special kind of badge in the Host's BrightID. Anybody that makes a "just met" connection with the host, and the host connects with them mutually, receives the Meets verification. Only one connection is enough.\
\
In practice, Hosts hold connection parties over zoom in a regular [schedule](https://meet.brightid.org) so that the member of the public can meet and make connection with the host.

As to the mechanism of how Hosts or Seeds come about, see the next section on [Seed Groups.](seed-groups.md)

### What does the public need to do in the meeting?

The protocol requires that the member of the public _show_ themselves clearly on video. They also need to _listen_ carefully and _respond_ sensibly if the host asks them to respond. If there is no response, or the response is not sensible, as can happen if the attendee does not understand the language of the meeting, then the host refuses to make connection with them. So, it is important for the member of the public to either attend meeting in the language they understand and speak well, or they need to take a human translator who can help them listen and respond appropriately during the meeting.

#### [Meetings are available in select languages.](https://meet.brightid.org)

Each meeting begins at the scheduled time and open to join only for 5 minutes. About 73K people have attended a meeting successfully so far.[\
](https://meet.brightid.org)\
[Making connection](../making-connections/) is same as the process of connecting with one's close connections. Host presents connection QR code over video which can be scanned with one's BrightID mobile app, or alternatively a link is presented that initiates the connection if one is attending the meeting with a mobile phone.\
\
After a successful meeting and connection, it takes about half an hour for the member of the public to receive the Meets verification. It shows up as a badge labeled "Meets" under their profile name in BrightID mobile app.
