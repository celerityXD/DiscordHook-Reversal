# DiscordHook-Reversal

# DiscordHook64.dll Reversal.

## WARNING: The offsets are outdated, the sigs will still work.

## Infos: 

-> Sigs of commonly used DiscordHook functions such as Present & GetAsyncKeyState

## Sigs & Offsets

DiscordHook_Present: 56 57 53 48 83 EC 30 44 89 C6 -> 0xE0080 (Updated as of: February 20 2023)

DiscordHook_GetKeyboardState: 56 57 48 83 EC 28 48 89 CE FF 15 ? ? ? ? -> 0x1B7948

DiscordHook_GetAsyncKeyState: 56 48 83 EC 20 89 CE -> 0x1B7858

DiscordHook_GetCursorPos: 56 48 83 EC 20 48 89 CE FF 15 ? ? ? ? 8A 15 ? ? ? ? -> 0x1B7880

DiscordHook_GetCursor: 8A 05 ? ? ? ? 84 C0 74 08 -> 0x1B79C0

DiscordHook_GetClipCursor: 56 48 83 EC 50 48 89 CE 48 8B 05 ? ? ? ? 48 31 E0 48 89 44 24 ? 8A 05 ? ? ? ? -> 0x1B7830

DiscordHook_GetCursorInfo: 56 57 48 83 EC 28 48 89 CE 8A 05 ? ? ? ? 84 C0 -> 0x1B78F8
