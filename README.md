SQL server hibernate dialect for XWiki
======================================

The filter function in the Livetable Macro is not working on MSSQL.
See [XWIKI-10606](http://jira.xwiki.org/browse/XWIKI-10606) for details about that issue.

This MySQL dialect suggested by [Josef Haimerl](http://jira.xwiki.org/secure/ViewProfile.jspa?name=jhaimerl) solve the
issue by replacing the mapping of the STR() function tu use a cast on SQL Server.
