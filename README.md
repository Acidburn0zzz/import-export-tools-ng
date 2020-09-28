# ![IETng icon] Import Export Tools NG


[ImportExportTools NG](https://addons.thunderbird.net/addon/importexporttools-ng/) adds import and 
export functions for messages, folders and profiles.

This derivative add-on is the update of [ImportExportTools](https://addons.thunderbird.net/addon/importexporttools/), 
the original work of [Paolo “Kaosmos”](https://addons.thunderbird.net/user/Paolo_Kaosmos/).

[Click here to view this add-on’s version history](https://addons.thunderbird.net/addon/importexporttools-ng/versions/).

Original add-on’s homepage:
https://addons.thunderbird.net/addon/importexporttools/

![IETng_version](https://img.shields.io/badge/version-v10.0.0-darkorange.png?label=ImportExportTools%20NG)
[![IETng_tb_version](https://img.shields.io/badge/version-v10.0.0-blue.png?label=Thunderbird%20Add-On)](https://addons.thunderbird.net/en-US/thunderbird/addon/)
![Thunderbird_version](https://img.shields.io/badge/version-v68.0--78.*-blue.png?label=Thunderbird)
[![License: GPL 3.0](https://img.shields.io/badge/License-GPL%203.0-red.png)](https://opensource.org/licenses/GPL-3.0)
![Release Status](https://img.shields.io/badge/Release%20Status-v10.0.0%20Released-brightgreen.png)

#

## Import Export Tools NG Add-On Features

Version 10.0.0 : New Features - September 26, 2020

- 78 Compatible
- New locales: el
- Index custom date format
- new tokens for filenames : sender/recipient e-mail
- Use `%d` in print settings header/footer for custom date

Bug Issues Fixed:
- #118, #63 Fixed conversion for plaintext
- #57 Use ForceDBClose to Close open files (fixes folders and messages)
- #77 Use global settings for PDF
- #130 scheduled backups
- #134 Correctly handle read, forwarded, replied flags

Thanks to many! : See issues


Menus:
 - Tools (most import and export functions including profiles)
 - Folders (most import and export functions)
 - Search dialog (export search results)
 - Selected messages (export or copy to clipboard)

Export:
 - Individual folder(s), optionally including subfolders (mbox format)
 - All folder messages in the following formats:
   - EML, HTML, PDF, CSV or plaintext
   - Export as individual files or a single file
   - Optionally include attachments
   - Export indexes as plain text or CSV
   - Extensive file naming convention options
   - Export messages from search dialog

Import:
 - Mbox files (including structure)
 - EML & EMLX files
 - Individual or all directory files

Profiles:
 - Export complete profile or just the mail files
 - Import profile
 - Auto profile backup with schedule on shutdown

SMS: Will be deprecated!

## Import Export Tools NG Add-On Installation

Normal install (requires Internet access) from [Thunderbird Add-on site](https://addons.thunderbird.net/):
- Download and install [ATN version](https://addons.thunderbird.net/addon/ImportExportToolsNG/) via the ``Add-ons Manager``.
- From the [Thunderbird Menu Bar](https://support.mozilla.org/en-US/kb/display-thunderbird-menus-and-toolbar), select ``Tools`` then ``Add-ons`` to open the ``Add-ons Manager``. Choose the ``Extensions`` tab, search for “TBD”, select ``+ Add to Thunderbird`` and follow the prompts to install and then restart.

Install (with or without Internet access) XPI directly:
- Download and install [GitHub XPI version](xpi) via the ``Add-ons Manager``.
- From the [Thunderbird Menu Bar](https://support.mozilla.org/en-US/kb/display-thunderbird-menus-and-toolbar), select ``Tools`` then ``Add-ons`` to open the ``Add-ons Manager``. Choose the ``Extensions`` tab, click the gear icon and choose ``Install Add-on From File…``
- Choose [XPI file](xpi), install and restart.

## Brief Usage Instructions

The extension adds a new menu item in the Tools menu.
(You may have to enable the Menu Bar from Preferences to make it display.)
The new submenu displays a number of additional actions which you can peform
to import or export various types of information into and out of Thunderbird.

The original add-on (link above) has a number of notes about individual commands,
though no structured user guide or handbook yet. (Sorry.)

## XPI Add-on Package Build instructions

Visual Studio Code:
 Build Default Task

Basic Command Line Build: (requires 7zip CLI version)
7z a ./xpi/import-export-tools-ng-4.0.0-tb.xpi ./src/*

## Issues & Questions
Post any issues or questions for Import Export Tools under [Issues](https://github.com/thundernest/import-export-tools-ng/issues)

## Changelog
 ImportExportTools NG changes are logged [here](CHANGELOG.md).

## Credits
Original Author: [Paolo “Kaosmos”](https://addons.thunderbird.net/user/Paolo_Kaosmos/)  
Developing Author: [Christopher Leidigh](https://github.com/cleidigh/)  

<html>
<div>Extension Icon: <a href="https://www.flaticon.com/authors/pixel-perfect" title="Pixel perfect">Pixel perfect</a> from <a href="https://www.flaticon.com/"                 title="Flaticon">www.flaticon.com & cleidigh</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/"                 title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>
</html>

[IETng icon]: rep-resources/images/import-export-tools-ng-icon-64px.png 
