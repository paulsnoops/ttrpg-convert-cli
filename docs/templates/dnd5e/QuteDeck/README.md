# QuteDeck

5eTools deck attributes (`deck2md.txt`)

Extension of [Tools5eQuteBase](../Tools5eQuteBase.md).

## Attributes

[books](#books), [cardBack](#cardback), [cards](#cards), [fluffImages](#fluffimages), [hasImages](#hasimages), [hasMoreImages](#hasmoreimages), [hasSections](#hassections), [labeledSource](#labeledsource), [name](#name), [reprintOf](#reprintof), [showAllImages](#showallimages), [showMoreImages](#showmoreimages), [showPortraitImage](#showportraitimage), [source](#source), [sourceAndPage](#sourceandpage), [sourcesWithFootnote](#sourceswithfootnote), [tags](#tags), [text](#text), [vaultPath](#vaultpath)

### books

List of source books using abbreviated name. Fantasy statblocks uses this list format, as an example.

### cardBack

Image from the back of the card as [ImageRef](../../ImageRef.md) (optional)

### cards

List of cards in the deck

### fluffImages

List of images as [ImageRef](../../ImageRef.md) (optional)

### hasImages

Return true if any images are present

### hasMoreImages

Return true if more than one image is present

### hasSections

True if the content (text) contains sections

### labeledSource

Formatted string describing the content's source(s): `_Source: <sources>_`

### name

Note name

### reprintOf

List of content superceded by this note (as [Reprinted](../../Reprinted.md))

### showAllImages

Return embedded wikilinks for all images
If there is more than one, they will be displayed in a gallery.

### showMoreImages

Return embedded wikilinks for all but the first image
If there is more than one, they will be displayed in a gallery.

### showPortraitImage

Return an embedded wikilink to the first image
Will have the "right" anchor tag.

### source

String describing the content's source(s)

### sourceAndPage

Book sources as list of [SourceAndPage](../../SourceAndPage.md)

### sourcesWithFootnote

Get Sources as a footnote.

Calling this method will return an italicised string with the primary source
followed by a footnote listing all other sources. Useful for types
that tend to have many sources.

### tags

Collected tags for inclusion in frontmatter

### text

Formatted text. For most templates, this is the bulk of the content.

### vaultPath

Path to this note in the vault
