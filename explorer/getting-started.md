# Getting Started

[BrightID explorer](https://explorer.brightid.org/) enables users to explore the BrightID graph. Nodes represent people in the BrightID graph and connections they make with each other represent links.

The default view of the graph is drawn using links that represent mutual connections with “Already known” or “Recovery” [levels](../getting-verified/making-connections/connection-levels.md). Connections that are one-sided or have “Just met” or “Suspicious” [levels](../getting-verified/making-connections/connection-levels.md) are ignored in the default view because they don’t represent real social relationships and aren’t useful for Sybil detection methods based on these relationships.

Links are colored based on [connection levels](../getting-verified/making-connections/connection-levels.md). “Already known” connections are orange and “Recovery” connections are blue. When different sides of a connection have different levels, colors of arrows on the links can help to find out the level of each side.

![](../.gitbook/assets/BrightID\_explorer\_1.png)

Nodes are colored based on their [verification](../getting-verified/) status. Verified nodes are blue and not verified ones are orange. Different verifications can be selected from the top menu. Most verifications assign scores to users and nodes’ size is based on their score. Statistics on the number of users that achieved each verification can be found under the “Statistics” section of the left side menu.

![](<../.gitbook/assets/BrightID explorer (2).png>)
