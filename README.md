# RMSI-Minecraft-Server-Interface (RMSI)
RMSI: An extensible interface for any type of Minecraft server.
It is implemented on *Virtual Console Provider (VCP)* and *Virtual Filesystem Provider (VFP)*. So RMSI does not rely on the console I/O redirection of Minecraft server and is not necessarily to be run on the same machine with Minecraft server.

Comparison with MCDaemon:
1. Independent. RMSI does not rely on console I/O redirection and local FS.
2. Safe. RMSI is less coupled with the Minecraft server, so if RMSI crashes, it's less likely to influence the real Minecraft server.
3. Extensible. Developers of RMSI put great attention on the code quality. Thus the plugin developer will be more relaxed and the software quality will be better.
4. Cross-platform. RMSI is written in pure Java code and rely on little external libraries. Users are enabled to run RMSI on any their favorited machines.
