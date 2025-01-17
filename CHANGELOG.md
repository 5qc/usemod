# Release 1.2.0 (November 05, 2017)
* switch DTD to HTML 4.0.1 Transitional
* cleanup generated HTML code
* added CSS class wikibody to include all except wikiheader and wikifooter
** suggested by UngarPeter
* fixed bug CallingKeepFileName
** with suggestion from JuanMtnezPineda
* show IP address instead of faked DNS entry on RecentChanges
* add EditHash

## Bugfix Release 1.2.1 (December 01, 2017)
* closing div for class wikibody was missing at some places, added
* put <hr> class wikilinerc inside of div for class wikirc
* fix EditHash
* RSS: fall back to LogoUrl for RssLogoUrl
* cleanup generated HTML code on history page

# Release 1.1.0 (October 31, 2017)
* enable warnings (perl -w)
* fix warnings
* enable taint mode (perl -T)
* fixes for taint mode
** based on work by MarkIrons
* fixed bug UnusedVariableDeclaration
** fix contributed by JuanMtnezPineda
* fixed bug PwlistArray
** fix contributed by JuanMtnezPineda
* remove unused variables

# Release 1.0 (???)
## Bugfix Release 1.0.1 (July 9, 2007)
* SECURITY: fix cross-site scripting vulnerability (CVE-2004-1397)
** fix contributed by Christoph Berg (cb@df7cb.de)
* fixed bug PossibleToCreatePagesThatCanNotBeEdited
** fix contributed by RichardP
* fixed bug FileUploadManglesFile
*** aka bug Win32BinaryUpload
*** aka bug UploadOnWindowsNeedsBinmode
** fix contributed by Robin Rowe (rower@movieeditor.com) and DavidWall
* fixed bug CompareButtonFailsToDiff
*** aka bug DoHistory's_Form
** fix contributed by BrianHunter and ??
* fixed bug BadHtml
* fixed bug AmpersandBug
** fix contributed by UngarPeter
  
## Bugfix Release 1.0.2 (August 26, 2007)
* added CREDITS and Changelog (forgot them in 1.0.1)
* make .zip distribution for Windows users again (forgot it for 1.0.1)
* fixed range in SplitUrlPunct()
* fixed bug ActionEqIndexAndEmbedEqOne
** same problem with other actions and parameter embed
* moved CSS class wikilinefooter (for <hr>) inside class wikifooter
* fixed bug ClassWikifooterMissing
* fixed bug VariableParseParasYieldsOddOutput
** fix contributed by Trent, simplified
* fixed bug UploadTranslation
** fix contributed by UngarPeter
* added patch RobotsNoFollow version D
** contributed by Trent with suggestion by UngarPeter
** based on work by TomScanlan
* fixed bug ActionLinksExistsZeroSubPage
*** aka bug RequestedLinks
** based on fix by GyPark and MikeCastle
* fixed bug ImageExtensionsCaseSensitive
*** aka bug UppercaseImageUploadCausesProblemsWithDisplay
* added ico/tif/tiff to ImageExtensions
* fixed bug CamelCaseImageUploadCausesProblemsWithDisplay
** with suggestion from DavidClaughton

## Bugfix Release 1.0.3 (September 12, 2007)
* fixed bug IntermapedGifNotInlinedForLink
* fixed bug AuthenicationFailedNoHeader
* fixed bug BacklinksMissesSomeFreeLinks
** fix contributed by BrianHunter
* fixed bug EmptyTableElements
** fix contributed by StefanTrcek
* fixed bug MiscTranslation
** fix contributed by JuanMtnezPineda
* added more translation strings
* DoRC: when using rcidonly text was quoted too much
** noticed by CliffordAdams (bug was introduced with XssFix in 1.0.1)
* fixed bug UrlEncoding
** fix contributed by StefanTrcek
  
## Bugfix Release 1.0.4 (December 1, 2007)
* fixed bug NoDisplayFooterInActionLink
** fix contributed by JuanMtnezPineda
* QuoteHtml, GetPageLockLink, GetAdminBar: move function to allow defered compilation again
* fixed bug: make GotoBars at top and bottom look the same on the edit page
* added some missing ScriptLinkChar() instead of "?"
* updated barnesandnoble.com search URL

## Bugfix Release 1.0.5 (August 28, 2009)
* added patch RssLinkInHeader (but only for normal pages)
** contributed by UngarPeter
* added patch DoPageLockMinorTweak
** contributed by JuanMtnezPineda
* Allow "0" as page name if FreeLinks are allowed
* fixed bug NumericDatesNeedZeroPadding
** fix contributed by GunnarH
* fixed bug ExtraBRAtDoBackLinks
** fix contributed by JuanMtnezPineda
* fixed bug TTatDoEditBanned
** fix contributed by JuanMtnezPineda
* fixed bug NonEnglishRSS
** fixes contributed by GunnarH

# Bugfix Release 1.0.6 (November 05, 2016)
* fixed bug CookieIgnored
* fixed bug CGIStartformAndEndform
* fixed bug SkipMigratingParameterLock
** based on fix by GyPark
