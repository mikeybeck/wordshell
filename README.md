# wordshell

## NOTE: This wordshell now uses a local copy of the controller file and doesn't pull it in from remote storage

Was formerly sold (with a GPL licence; is now MIT) at wordshell.net (probably the domain will be bought by someone else in future, so please do not assume that I still control it), but after end-of-life, that site was archived to remove the maintenance burden. So, the manual that was there is gone (but you can probably get it at the Internet Archive). You can also do `wordshell --help` (or just read the source).

You should probably use WP-CLI instead. But WordShell still has a few interesting features that I think aren't in WP-CLI yet. e.g. Difference analysis and recording and auto-patching; and accessing sites via FTP/SFTP.

### mikeybeck's mods:
- 05/16: Addition of --no-maintenance mode, which prevents site from going into maintenance mode when updating plugins.  (not recommended but y'know...)
- 06/16: Made remote controller local only so I can make changes (no longer fetches from Amazon s3)
- 06/17: Added numerical index to plugin list to make selection/specification easier (display is a bit buggy but selection should work ok)
- 03/18: Fixed numerical index to plugin list (still doesn't always display correctly though)
