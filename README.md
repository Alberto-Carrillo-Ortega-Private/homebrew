## A repository of Homebrew JSONs compatible with Pf2eTools by Alozen from Roll Initiative.
[![JSON Validation](https://github.com/Pf2eTools/homebrew/actions/workflows/test.yml/badge.svg)](https://github.com/Pf2eTools/homebrew/actions/workflows/test.yml)

## The Repo
#### Objetive
##### The game
- To provide a different outlook on the Pathfinder TTRPG.
- To bring up some underperforming feats and class features, as well as to add some more.
- To offer an optional focus on balance where every class feels better to play and the game is "less swingy."
- To remaster casters and spells so they get some actual power in exchange for their durability and feel less "gamefied". More resembling the editions of old.
- To facilitate access to all the small changes in the system that we make in our playgroup
- To provide a common place to store all the elements related to an original fantasy setting

---

#### Getting Brew (automatically)
1. Hit the "Manage Homebrew" button (if available) on a Pf2eTools page.
1. Hit the "Get Homebrew" button gear icon
1. Use this URL "*https://raw.githubusercontent.com/Alberto-Carrillo-Ortega-Private/homebrew/master/*"
1. Hit the "Get Homebrew" button
1. Click the title of a homebrew to add it to the site repository.
#### Getting Brew (manually)
1. Browse for the file you want.
2. Click "Raw" (top-right) and save it as `.json`.
3. Load into Pf2eTools via the Brew Manager.
#### Getting Help
Join the Pf2eTools Discord Server, and ask in the [#brew conversion](https://discord.gg/BjphcQGfJY) channel.
#### Creating and Contributing

_**Note:** one large advantage of contributing to this repo, is that your files will be kept up-to-date as changes are made to the main site._

- The easiest way to make your own is to copy one of the existing 'brews as a template and use the main [Pf2eTools data](https://github.com/Pf2eTools/Pf2eTools.github.io/tree/master/data) as a reference.
- Contributions are welcome. For the GitHub-literate, make a pull request.* For everyone else, create an Issue and post a link to your file (PasteBin is fine), and I (or other maintainers, in future) can add it for you.

\* _See the article [here](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) for a how-to._

A schema is available (`json.schema`) describing the layout of the and usage of the `_meta` property found in the various data files.

---

##### Conventions to Follow

There are a few conventions used which should be followed when creating homebrew:
 - Use tabs over spaces, "LF" as end-of-line, and UTF-8 (without BOM) encoding.
 - Format filenames as `Author Name; Homebrew Name.json`
 - Use a unique `"json"` source name; they should be uniquely identifiable across all homebrew. For example, for the hypothetical book "A History Of Dragons" by "A. N. Other," a sensible source name would be `"HistoryOfDragonsANOther"`. Note that this text is never displayed, so can be as long and as ugly as required. While this is not enforced, we reserve the right to change data as required to avoid naming conflicts.
 - Only include content authors in the source `"author"` field; conversion credit should be given in a `"convertedBy"` field (with the same format).
 - Include a `"dateAdded"` property in file metadata, which is a Unix timestamp (in seconds) at which the file was added. You can view and copy the current Unix time [here](https://www.epochconverter.com/).
