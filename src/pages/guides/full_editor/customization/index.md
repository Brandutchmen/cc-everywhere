---
keywords:
  - Express Embed SDK
  - Express Editor
  - Adobe Express
  - Embed SDK
  - Quick Actions
  - SDK
  - JavaScript
  - Embed
  - SDK Reference
  - Editor component 
  - Customize
  - Locale
  - Template Type
title: Adobe Express Editor - Customization
description: This guide will show you how to customize the Adobe Express editor component. 
contributors:
  - https://github.com/amandahuarng
  - https://github.com/pklaschka
---

# Customization

The full editor component can be configured and customized to fit the needs of your users.

## Locale

The Adobe Express Embed SDK lets you customize the locale during initialization. The default value is `'en_US'`. This determines the language setting for users experiencing SDK components.

| Locale | Description
| :-- | :--
| 'en_US' | English
| 'fr_FR' | French
| 'de_DE' | German  
| 'ja_JP' | Japanese
| 'it_IT'| Italian
| 'es_ES'| Spanish
| 'pt_BR'| Portuguese
| 'ko_JR'| Korean  
| 'da_DK'| Danish
| 'nl_NL'| Dutch  
| 'nb_NO'| Norwegian
| 'sv_SE'| Swedish
| 'fi_FI'| Finnish
| 'zh_Hans_CN' | Chinese (simplified)
| 'zh_Hant_TW'| Chinese (traditional)

## Template Layout Ratio

`canvasSize` allows you to specify a string value that initializes the full editor loaded with templates that fit that layout ratio.

| Template Layout Ratio | Description
| :-- | :--
| 'Instagram' | Instagram post
| 'InstagramStory' | Instagram story
| 'InstagramPortrait' | Instagram portrait
| 'InstagramLandscape' | Instagram post (landscape)
| 'facebook' | Facebook post
| 'FacebookProfileCover' | Facebook profile cover
| 'FacebookPageCover' | Facebook covers
| 'FacebookEventCover' | Facebook event cover
| 'Twitter' | Twitter post
| 'TwitterHeader' | Twitter header
| 'YouTubeChannelArt' | YouTube channel art
| 'YoutubeThumbnail' | YouTube thumbnail
| 'LinkedInBlogPost' | LinkedIn blog post
| 'LinkedInProfileCover' | LinkedIn Profile Cover Picture
| 'SparkVideoSlide' | Spark Video slide
| 'SparkVideoSlideSquare' | Spark video slide (square)
| 'SnapchatStory' | Snapchat Story
| 'KindleCover' | Kindle cover
| 'Pinterest' | Pinterest post
| 'BlogPost' | Blog post post
| Twitch banner | Twitch banner
|'EtsyCover' | Etsy cover
 'EventbriteEventImage' | Eventbrite event image
| 'Square' | Square
| 'iPhone' | iPhone
| 'Letter' | Letter
|'Poster' | Poster
| 'Card' | Card
| 'A3'  | A3
| 'A4'  | A4
| 'A5'  | A5
|'1:2' | aspect ratio of 1:2
| '2:1' | aspect ratio of 2:1
| '2:3' | aspect ratio of 2:3
| '3:1' | aspect ratio of 3:1
| '3:2' | aspect ratio of 3:2
| '4:3' | aspect ratio of 4:3
| '16:9' | aspect ratio of 16:9

## Template Type

Developers can pass the `createDesign()` method a `templateType`, for the user to start creating with. Browse "[All templates](https://express.adobe.com/sp/search?homeBackType=home)" on Adobe Express to get an ideal of each category.

| Template Type | Adobe Express Template Category
| :-- | :--
| 'Flyers' | Flyers
| 'Instagram_Post' | Instagram posts
| 'Instagram_Story' | Instagram Stories
| 'Logo' | Logos
| 'Youtube_Thumbnail' | YouTube thumbnails
| 'Collage' | Collages
|'Facebook_Post' | Facebook posts
| 'Facebook_Cover' | Facebook covers
| 'Card' | Cards
| 'Invitation' | Invitations
| 'Business_Card' | Business cards
| 'Menu' | Menus
| 'Brochure' | Brochures
| 'Resume' | Resumes
| 'Poster' | Posters
| 'Desktop_Wallpaper' | Wallpapers
|'Presentation_Graphic' | Presentation Graphics
|'Album_Cover' | Album covers
| 'Book_Cover' | Book covers
| 'Worksheet' | Worksheets
