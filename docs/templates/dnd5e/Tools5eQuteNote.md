# Tools5eQuteNote

Attributes for notes that are generated from the 5eTools data.
This is a trivial extension of [QuteNote](../QuteNote.md).

Notes created from `Tools5eQuteNote` will use the `note2md.txt` template.

## Attributes

[hasSections](#hassections), [labeledSource](#labeledsource), [name](#name), [reprintOf](#reprintof), [source](#source), [sourceAndPage](#sourceandpage), [tags](#tags), [text](#text), [vaultPath](#vaultpath)


### hasSections

True if the content (text) contains sections

### labeledSource

Formatted string describing the content's source(s): `_Source: <sources>_`

### name

Note name

### reprintOf

List of content superceded by this note (as [Reprinted](../Reprinted.md))

### source

String describing the content's source(s)

### sourceAndPage

Book sources as list of [SourceAndPage](../SourceAndPage.md)

### tags

Collected tags for inclusion in frontmatter

### text

Formatted text. For most templates, this is the bulk of the content.

### vaultPath

Path to this note in the vault
