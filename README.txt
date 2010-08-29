This is a fork of http://ndumbster.sourceforge.net/ with a very simple change to fix a transaction deadlock in .NET 3.5+.

Without this change, using this library in .NET 3.5+ results in either a timeout or a very long (1-2 minute) wait time when sending emails to this server/reading them from it.

Thanks to whoever posted this issue on the project site for pointing out the fix.

http://sourceforge.net/tracker/?func=detail&aid=2840559&group_id=130537&atid=718120