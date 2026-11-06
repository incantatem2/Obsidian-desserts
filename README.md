
# Desserts

My old themes Parfait and Cocoa merged into one light/dark theme. They also have some small style edits.
Tweaks from Parfait have also been added to Cocoa to make it more visually interesting and more visually similar to the light theme as well.


The original Parfait and Cocoa themes are going to be retired once this one is published.


#### left-aligned text

I removed the left-aligned text in this version, you can, however, add this detail back if you prefer, with this simple css bit:

```
.markdown-preview-view.is-readable-line-width .markdown-preview-sizer {
     margin-left: -1px; 
}
```

(Add this in the theme css itself, not as separate snippet.)


#### modes

dark mode (Cocoa): 
![](images/desserts-screenshot-dark-cocoa.jpg)


light mode (Parfait):
![](images/desserts-screenshot-light-parfait.jpg)



## Installation

1. Open Obsidian and go to **Settings > Appearance**.
2. Next to **Themes**, select **Manage**.
3. Search for "Desserts", then select **Install and use**.

To install by hand, download `manifest.json` and `theme.css` from the [latest release](https://github.com/incantatem2/Obsidian-desserts/releases/latest). Put both files in a folder named `Desserts` inside `.obsidian/themes/` in your vault. Then choose the theme under **Settings > Appearance > Themes**.
