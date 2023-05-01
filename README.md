# JavaConcurreny
Implementation involved in Google Drive/ Dropbox.
Implementation of functionalities like uploading a file, downloading a file, allowing multiple users to perform operations like read, write, delete, update etc.

1) File Synchronization using Delta Sync: Files must be synced continuously as changes are detected. To detect the changes a watcher is implemented.
2) Enabling the options to suspend and resume the ongoing synchronization process.
3) Multiple clients must be able to view synchronization status and other information like metadata of file, may be previous version updates etc.
4) Error Handling must be implemented during the cases like poor network (Network Throttles), Invalid Operation from user etc.
5) The connection between multiple clients to the server must be established using UDP.
