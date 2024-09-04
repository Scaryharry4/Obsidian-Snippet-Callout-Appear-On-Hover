# Hover Callouts
Hover callouts functions so that Obsidian.md callouts that are not set to be open or closed with a toggle will be collapsed until hovered over at which point they will expand.

# !!IMPORTANT!!
If the content of your callout is more than 41 lines (With default text size) or otherwise exceeds 1000px in height you must adjust the snippet in order for your content to not be cut off.

This callout has not yet been tested on non default callout themes. If you adjust this to function with a theme of your choice I encourage you to make a fork on the Github
https://github.com/Scaryharry4/Obsidian-Snippet-Callout-Appear-On-Hover

Below is the Obsidian markdown to generate the image above and to test the snippet for yourself
```
> [!NOTE] Normal
> This callout is closed by default but on hover will appear
> > [!example]+
> > [!NOTE] Normal
> his callout is closed by default but on hover will appear

> [!TIP]- Collapsed
This callout is collapsed by default with the "-" symbol
> > [!example]+
> > [!TIP]- Collapsed
> This callout is collapsed by default with the "-" symbol

> [!ERROR]+ Open
This callout is open by default with the "+" symbol
> > [!example]+
> > [!TIP]- Collapsed
> This callout is open by default with the "+" symbol
```
