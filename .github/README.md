# obsidian-library-module
This is a quick and dirty copy/paste job. I'll flesh this out in the near 
future.

# library guidelines

# 1 nomenclature
## library nomenclature
The library has broad terms to encompass the content recorded within:

> [!note]
> ASSET
> An asset is any document that is not a note or a card. This includes PDFs, Pages docs, etc.

> [!note]
> CARD
> Cards are markdown documents that enumerate a specific asset. Book Cards enumerate book documents; Paper Cards enumerate academic paper documents; etc.

> [!note]
> NOTES
> Notes are descriptive markdown documents that are neither Cards nor Assests.
## asset nomenclature
Assets are further categorized according to particular nomenclature:

> [!note]
> BOOK
> Books are documents containing entire books. Fiction, non-fiction, instructional, educational, for entertainment purposes, whatever.

> [!note]
> PAPER
> Papers are documents that are academic in nature. These are often published in journals and made available as individual documents. This category includes whitepapers.

> [!note]
> ARTICLE
> Articles are exported or scanned documents of posts found online or in paper magazines and newspapers. These are different from academic papers.

## frontmatter nomenclature
Regarding notes' frontmatter, some clarity on property names:

> [!note]
> CATEGORY
> Is it a book, paper, or article?

> [!note]
> TAGS
> This enumerates the genre(s) an asset may fall into. As many documents span multiple genres, the tagging system within the library is specifically aimed at managing cross-genre pollination. 

> [!note]
> KEYWORDS
> Keywords operate much as tags would in systems outside of the library. These are oriented toward describing topical placement of assets.

# 2 a single bibliography exists to enumerate all notes, cards, and assets in the library

> [!caution]
> IMPORTANT
> Every single asset that is included in the library must be accompanied by a citation. No exceptions.

The bibliography groups assets by category and lists them alphabetically. Citations should accompany each asset. Assets are linked by their titles with their respective citations directly below them. Depending on the context of the vault, citations will be in either APA or Chicago style.

> [!note]
> Example Bibliography Entry
> [[Myth of the Privacy Paradox]]:
Solove, Daniel J., The Myth of the Privacy Paradox (January 29, 2021). 89 George Washington Law Review 1 (2021), GWU Legal Studies Research Paper No. 2020-10, GWU Law School Public Law Research Paper No. 2020-10, Available at SSRN: https://ssrn.com/abstract=3536265 or http://dx.doi.org/10.2139/ssrn.3536265 

# 3 one note, one singular identifying piece of information
Each individual note enumerates a single piece of information:

- Cards enumerate assets specifically. One card per asset.
- Notes may enumerate topics that gather assets into a collection. One topic per note.
- Notes may enumerate publications, in which all books, papers, or articles are collected. One publication per note.
- Notes may enumerate authors. One author per note.

Etc, etc. The idea is to maintain a strict scheme by which to confine the introduction of arbitrary and useless content.

# 4 the glossary
## the glossary is a single directory, one-level deep, at the root of the library.
It contains all of the definitions arising from the reading.
## if a vault has a glossary, it has a library.
The glossary lives in the library, as most often, definitions will arise and be created out of the reading material.
## one term per note
Per [[#3 one note, one singular identifying piece of information|one note, one 
piece of information]], each note included in the glossary is atomic and 
contains exactly one term. Terms may be linked to each other as a means of 
expressing relationships. Aliases may be included. The definition itself may 
be drafted to be an entire encyclopedia entry all on its own. Despite all of 
these possibilities, each note contains and defines one single term.
# 5 assets management
## assets belong in a single directory, one-level deep, at the root of the library
This directory can be called whatever you want, but it is singular and 
contains no nested directories. All assets are included in this singular 
directory and organized by Card at the root of the library.
## cards exist with the asset
When an asset is added to the library, a Card is created detailing the asset 
and placed in the root of the library, and an entry is made in the 
bibliography linked to the Card. When an asset is removed from the library, 
its companion card and bibliography entry are also removed.
# 6 internal linkages only
Anything within the library--assets, Cards, notes--may only link to each other 
and not to references outside the library. This makes the library 
self-contained and highly portable. When imported into a vault, notes in the 
vault outside of the library may link to items within the library, but items 
within the library may not link to items outside of it.
# 7 vault concerns
## templates
The library has its own set of templates. If the library exists as a 
standalone unit within vault wrapper, the `templates`  directory may be made 
use of directly. If, however, the library is placed within the context of a 
larger vault, copy the library templates into the template directory of the 
vault and use accordingly.
## plugins
This is where things may get a little dicey. Plugins are great tools, but care 
must be made with regard to what tools are being implemented within the 
library. To keep the library highly portable, these plugins are currently in 
use and operate upon the library:

- [Dataview](https://github.com/blacksmithgu/obsidian-dataview) 
- [Custom File Explorer sorting](https://github.com/SebastianMC/obsidian-custom-sort) 
- [Iconize](https://github.com/FlorianWoelki/obsidian-iconize) 
- [PDF++](https://github.com/RyotaUshio/obsidian-pdf-plus) 
- [Note Definitions](https://github.com/dominiclet/obsidian-note-definitions) 
- [Frontmatter Markdown Links](https://github.com/mnaoumov/obsidian-frontmatter-markdown-links) 

When importing a library into a vault, install these plugins first.

This list may change at any time, and if so, all vaults will need to be 
adjusted accordingly, though this should not be subject to change often, and 
very much should not be arbitrarily affected.

## themes
Do what you want.

# conclusion
I think that's everything for now!
