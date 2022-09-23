# AndroidSiteExtension
Add extra functionality to any URL in Android using Termux's URL handler

If you install [Termux](), you can find it in the Share menu.
Sharing a webpage to it runs the shellscript `bin/termux-url-opener`, with the URL as argument 1.

You can do whatever you want with this URL in this script.
If you want to pass a different URL back to the browser, you can call `termux-open` or `termux-open-url` with the new URL as an argument.

The example opens the current YouTube video with LoopTube.
`sleep 3` is needed at the end, since otherwise Termux would close before the new URL could be opened.