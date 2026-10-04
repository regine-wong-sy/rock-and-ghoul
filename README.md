# Rock & Ghoul

Team game built at DigiPen (CSD2451) on a custom C++17 engine. You are Rock, one half of the guitar duo Rock & Ghoul. When Ghoul steps away before the gig at Jam Out SG, malicious spirits attack. Use your guitar's newly found powers to fight through to the stage and find Ghoul.

This repo hosts the Windows installer. The source is not published here.

## Try it (Windows)

1. Download `RockAndGhoul_Setup.exe` (about 650 MB) from the [latest release](../../releases/latest).
2. Run it. Windows SmartScreen may warn about an unknown publisher because the installer isn't code-signed. Choose **More info, then Run anyway**.

## Controls

| Action | Keyboard | Controller |
| --- | --- | --- |
| Move | WASD | Left stick |
| Dash | Left Shift | A |
| Melee | E | RB |
| Cast a spell | Arrow-key sequence, then 1 / 2 / 3 to fire | LT + Y/X/B/A for the sequence, then X / Y / B to fire |
| Pause | Esc | Start / Back |
| Advance dialogue | Space | A |
| Skip cutscene | Esc | Start / Back |
| Fullscreen | Alt + Enter | |

Spell sequences: Soundwave is Up, Down. AOE is Up, Left, Down. Shield is Down, Down, Right. Healing is Right, Up, Right.

Press **F1** to open the in-game editor and **F3** to show the FPS counter.

## The engine and editor

The engine has a dockable ImGui editor with panels for the game view and play/stop testing, entity inspector, prefabs, UI editing, scene management, asset browsers (images, audio, video, fonts), render layers, a collision layer matrix with spatial-grid statistics, and a build-size analyzer. Libraries: GLFW, GLEW, FMOD, ImGui, ImGuizmo, nlohmann/json, Mono (C# scripting) and FFmpeg. It builds with CMake.

## Team Avid Divas

Regine Wong (tech lead, programmer), Kervin Guan Cheng Ong, Yasmin Tazi, Manfred Sim, Tan Jun Quan (project manager), Tan Ying Clarissa (audio lead), Danny Shannon Wong Jia Jun (design lead, UI/UX), Kelly Keli Goh (artist).
