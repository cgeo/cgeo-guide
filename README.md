# cgeo-guide
Snapshot of the c:geo DokuWiki user guide.

**This repository is only for backup purposes. Updates to the user guide are done directly on its website https://manual.cgeo.org**

## Background
This repository is used as a backup of the relevant content and DokuWiki configuration files of the c:geo user guide installation running at https://manual.cgeo.org
As the current server installation is owned and maintained privately by a c:geo team member (Lineflyer) it might be wise to have a backup available in case of need.

## Content of this repository
- /data/pages - Contains the current content pages
- /data/meta - Contains meta information of the pages
- /data/media - Contains the current media files (Images and other files uploaded to the Wiki)
- /data/media_meta - Meta data for the media
- /data/attic - All old versions of the content pages
- /data/media_attic - All the old versions of media files
- /conf - Some relevant configuration data (without confidential information)

## Update of the repository
The repository is updated manually from time to time by pushing a snapshot of the current state of the server content as a backup.
This backup follows the guide for content backup as described here: https://www.dokuwiki.org/start?id=faq:backup

## Restoring data to DokuWiki
In case of need the content of this repository can be used to restore the content data (texts, media) and their meta data and history. Configuration details (such as styles and themes) and user accounts are however not covered by this repository and need to be set up manually.
Corresponding installation and configuration guides and the DokuWiki software itself can be found on https://www.dokuwiki.org

## Useful information
Other useful information to restore a working DokuWiki with similar functions and styles. Not all of this is needed to restore basic functionality. Information considered relevant to restore (e.g. as it might be used on page syntax) is marked by an asterik (*).

- Used sytle templates:
  - adoradark
- Used plugins:
  - Anchor(*)
  - Batchedit
  - Bookcreator
  - Color
  - dw2pdf(*)
  - goto(*)
  - oauth (for Github)
  - orphanswanted
  - revert
  - wrap(*)
  - indexmenu(*)
  - enforcesummary
