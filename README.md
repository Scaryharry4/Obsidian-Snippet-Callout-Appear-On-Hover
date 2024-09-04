# Hover Callouts
Hover callouts functions so that Obsidian.md callouts that are not set to be open or closed with a toggle will be collapsed until hovered over at which point they will expand.

# !!IMPORTANT!!
If the content of your callout is more than 41 lines (With default text size) or otherwise exceeds 1000px in height you must adjust the snippet in order for your content to not be cut off.

This snippet has not yet been tested on non default callout themes. If it does not work with your theme of choice and you adjust it to function with said theme I encourage you to make a fork.

Please note that this does not apply to nested callouts at the moment.

![Example Gif](https://github.com/user-attachments/assets/424138cd-065e-419d-b3d2-6ed866102ce6)

Below is the Obsidian markdown to generate the example above and to test the snippet for yourself
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


### Thanks
Thanks to kapirklaa on the Obsidian discord for recommending the use of flex-grow to get this working
