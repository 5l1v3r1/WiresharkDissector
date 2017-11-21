# WiresharkDissector
Lua dissector for Minecraft 1.8.9 PC Edition

Minecraft.lua

Author: Haiyang Si
 
Works as of Wireshark v2.0.2
This is a Lua dissector for Minecraft 1.8.9 PC Edition validation.
It supports most of Minecraft actions whose 'Packet ID' are unique.
 
Notice:
1. For the actions share the same 'Packet ID' It lists all the possible actions' names
2. Map Chunk Bulk's length range is extraordinary, so now the disector doesn't support it well.

Setup
1. Copy 'Minecraft.lua’ to somewhere in your wireshark directory. For example, C:\Program Files\Wireshark.
2. Open ‘init.lua’ in your wireshark root directory. Comment the line ‘disable_lua = true’ or change it to ‘disable_lua = false’.
3. Add 'dofile(DATA_DIR.."Minecraft.lua")' into 'init.lua'

Blog:
For more details about Minecraft please read Ixia Official blog [ATI Minecraft](https://www.ixiacom.com/company/blog/ati-minecraft) .
