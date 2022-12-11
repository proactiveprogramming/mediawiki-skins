# mw-Timless (MediaWiki skin)
Timeless strongly supports responsive web design and is optimized for a multitude of screen widths ranging from narrow mobile phone screens up to wide monitors. 

The skin is based on Winter.

## Installation
Download and add to "LocalSettings.php"

	wfLoadSkin( 'Timeless' );
	
Configure as required.

Check "Special:version"

## Features
Timeless incorporates the functionality of a desktop-focused theme such as Skin:Vector, the default desktop skin, onto all screen sizes. 

The general aim is to make a fully featured skin that emphasizes both content and editing tools, with multiple view modes for showing everything, focusing only on content (winter), or switching to dark/night viewing. One day it will actually do this. 

Timeless does not forcibly restyle tables for mobile resolutions, and instead expects and encourages users to make tables and templates responsive themselves, optimized to their particular usage.  In other
words, make sure that your table can handle reformatting between 
different screen sizes.

## Responsive website design.

### >= 1340 pixels
Site is visible in three columns.

The column with content is fixed at 1261 px.

### 1339 to 1100 pixels
Site is visible in two columns. This is the format of the original
Vector skin.

### Less than 1100 px
The site is visible in one column.  The content area
fills the whole screen.

The menus are collapsed into text menus.

### Less than 851 px
Adapted for mobile phones.

Major items are displayed using icons instead of text to save space.

## Version History

Version 1.0 (MediaWiki 1.39.x LTS, , with modifications)

The following changes are differences from the standard 
MediaWiki 1.39.x Timeless skin.  Original author did not update the 
version number with the new MediaWiki LTS version.

- Added Avatars from the "SocialProfile" extension.  The extension SocialProfile is a requirement of this skin.
- Removed the "background-image" from the css file, because we are using the SocialProfile extension.
- Added w3css (4.15) library to the skin (with colors).
- Changed to be only 1 column wide.
- Removed mid and large screen options, so we can have the maximum amount of space for the articles.  Why valuable screen space with side menus when we can use that space for actual article data?

Version 0.9.1 (MediaWiki, 1.39.x LTS, 2020-09-25)

Original author did not update the version number even though
the source code was updated for MediaWiki 1.39.x.

- Fixed calls to "user" class to be compatible with MediaWiki 1.39.x

Version 0.9.1 (MediaWiki, 1.35.x LTS, 2020-09-25)

- Original version.  See MediaWiki for details.



