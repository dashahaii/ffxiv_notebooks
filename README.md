# Tanuki is under Development, join discord for information or to contribute.

[Join the Tanuki dev discord server!](https://discord.gg/WauSVWzpZ3)

In the discord, we can slot you onto a team to craft/gather, or help you start your own crafting projects. We are here to make you Gil.

## NOTICE

We uphold strict ethical standards when it comes to working with the Tanuki platform, people who use RMT **at all** (real-money trading) or knowledgeably profiting off the work of bots will be shut off the platform, and reported to Yoshi P. For example, laundering your (unethically-obtained) gil through the market board between characters & accounts, is strictly prohibited. You may move assets between characters and accounts, but not if the source is knowledgeably from botted work.

## NOTEBOOKS

* item_notebook (Django) -> compiles crafting & gathering recipes, gathering nodes, and interacts with the real game data obtained from XIVAPI. This is similar to teamcraft lists in functionality.
* project-notebook (Deno/Oak) -> manages project artifacts such as holds, contributions, members, and all related data after the item service does its job.
* market_notebook (Django) -> TBA, queries Universalis market board API and generates insight into *what to craft* for these crafting projects.
* experimental (???) -> TBA, experimental notebooks that don't fit in anywhere else.
Please open an issue in the repository as bugs and errors arise, this is a solo dev team with some support from FFXIV community, and other people's great tools.