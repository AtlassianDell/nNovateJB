# nNovateJB
## What is nNovateJB?
nNovateJB (hereby nJB) is a jailbreak method for the Orion Instruments nNovate series.
## Which devices can run nJB?
### The ones that natively run it:
- nNovate CX series
- nNovate CX 2 series
- nNovate CE series
- nNovate E series
- nNovate CAS series
### The ones that require the ".mark" file, requiring more work:
- nNovate C series
- nNovate NC series
- nNovate Touch series (since its programming is weird)
### The ones that cannot run nJB:
- nNovate Touch 2 series (like really why does this look even worse than nT-Basic???)
- nNovate Clickpad (it can't run programs)

## How to install?
To install on native devices:
1. Install ```main.nvtf```
2. Create a new directory by using the cmd line (Settings\Management\CMD).
   2a. ```~ root -login```
   2b. ```\ mkdir C:\Home\~~"nJB"```
3. Now, cd into the new directory.
   3a. ```cd C:\Home\nJB```
4. Once there, connect to WiFi and enable Host WiFi Tethering.
5. ```pm compile github.com/AtlassianDell/nNovateJB/comp```
6. Once completed, there you have it! nJB has been installed!

To install on non-native devices:
1. Install ```main.nvtf```
2. Create a new directory by using the cmd line (Settings\Management\CMD).
   2a. ```~ root -login```
   2b. ```\ mkdir C:\Home\~~"nJB"```
   2c. ```\ mkdir C:\Home\nJB\~~"Additional"```
4. Now, cd into the nJB directory.
   3a. ```cd C:\Home\nJB```
5. Once there, connect to WiFi and enable Host WiFi Tethering.
6. ```pm compile github.com/AtlassianDell/nNovateJB/comp```
7. Once completed, install ```.mark``` with:
   7a. ```pm install github.com/AtlassianDell/nNovateJB/.mark```
8. ```pm compile .mark```
9. There you go!

## What to do with non-compatible devices?
Although nJB is unable to work with them, for some reason nSpire's jailbreak works with them. Use nDless for this.
