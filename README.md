# youtube-ticker
A lightweight, transparent browser-source ticker for OBS. It sits along the
bottom edge of the source, with a red live-style label and a continuous
right-to-left crawl.

## Use in OBS

1. Add a **Browser** source to your scene. You can enable **Local file** and
   select `index.html` to use the default message, or serve this folder and use
   its URL as the browser source to customize the ticker with URL parameters.
3. Set the source width and height to your canvas size (for example, 1920 ×
   1080). The ticker overlays the bottom edge; the rest of the page is
   transparent.
4. To change the ticker, add URL parameters to the browser-source URL:

   - `text`: the video or now-playing message
   - `channel`: an optional channel name shown beside the label
   - `speed`: crawl duration in seconds (10–120; lower is faster)
