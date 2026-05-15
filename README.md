<img width="477" height="179" alt="ECSX" src="https://github.com/user-attachments/assets/8d6775e9-7f74-427d-83ef-75f6b4cf3777" />

# Ecstatica Recompiled (1 and 2)
Ecstatica I & II — Modern Windows Recompilation

A full 64‑bit native port of the legendary ellipsoid survival classics
Spacefarer Retro Remasters proudly presents the definitive way to experience Ecstatica and Ecstatica II on modern hardware.

For the first time in decades, both games run smoothly, stably, and beautifully — exactly as you remember them, but finally playable again.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/efa6c845-1123-4b46-9fb1-5b6ba4fcf747" />

⭐ Features
Complete 64‑bit recompilation of Ecstatica 1 & 2
Rebuilt from the ground up to run natively on modern Windows systems.

Full HD rendering (1920×1080 minimum)  
The new engine is hard‑coded for crisp, faithful fidelity.

Direct3D 12 (Feature Level 11)  
Modern GPU pipeline, zero legacy dependencies.

60 FPS gameplay  
The original experience, now fluid and responsive.

Modern controller support  
Powered by an SDL3 input layer to replace archaic Win95 direct pooling.

Enhanced audio  
SoLoud + MIDI playback for clean, stable sound on modern systems.

HD background support  
Preserves the iconic pre‑rendered look with modern clarity.

Runs flawlessly on Windows 10 / 11  
No compatibility mode. No wrappers. No VM.

🖥️ System Requirements
Component	Requirement
OS	Windows 10 or Windows 11 (64‑bit)
Resolution	1920×1080 minimum
Graphics	Direct3D 12 compatible GPU (FL11)
Sound	SoLoud / MIDI compatible output
Input	Keyboard, mouse, or modern game controller

⚠️ Note: This port is Windows‑only.
Linux/Wine and macOS are not supported.

🚀 Why This Exists
Ecstatica is a cult classic — but running it today was practically impossible.
Between ancient APIs, broken timing, and OS‑level incompatibilities, the original binaries simply couldn’t survive the jump to modern systems.

After countless requests from fans, Spacefarer Retro Remasters rebuilt the entire runtime, delivering a version that finally just works.

📦 Installation
Download the latest release from the Releases page.

Extract the archive.

Launch the executable (Ecstatica1Recomp_Win64.exe, or Ecstatica2Recomp_Win64.exe)

Enjoy Ecstatica the way it was always meant to be played.

🛠️ Technical Notes
Engine is hard‑coded for 1080p to maintain visual consistency and avoid scaling artifacts.

Audio stack uses SoLoud for modern stability and clean mixing.

Graphics pipeline is fully rewritten for D3D12.

❤️ Community & Support
If you encounter issues, open an Issue on GitHub.
Pull Requests are welcome — especially for controller mappings, QoL improvements, and documentation.

🕯️ A Tribute to a Lost Era
Ecstatica was weird, bold, atmospheric, and utterly unlike anything else.
This project exists to preserve that magic — not to change it.

Welcome back to Tirich.
Welcome back to the nightmare.

<img width="1536" height="1024" alt="ECRecomp" src="https://github.com/user-attachments/assets/70384ed3-96af-4945-a27d-887360a16114" />

CONTROLS

Basic Keyboard Layout

Below is a table displaying all keyboard commands including descriptions of the actions. Note that the game does not provide an internal option to remap the controls but an external tool like DOSBox' Mapper program can be used to rebind the keys for inreased convenience (it also allows mapping to gamepads).
Command 	Key 	Description
Move forward 	↑ 	A tap will make the character execute a single careful step.
Move backwards 	↓ 	
Turn left 	← 	
Turn right 	→ 	
Basic attacks 	Ctrl + Cursor keys 	When the control key is held down the cursor keys will execute different kinds of attacks instead of moving the character.
Advanced attacks 	Ctrl + Left Alt + Cursor keys 	When the control and alt keys are held down the cursor keys will execute different kinds of attacks instead of moving the character.
Dodge roll 	Left Alt + Cursor keys 	Executes a dodge roll in the direction specified by the cursor keys.
Jump 	Left Shift 	Executes a small jump suitable for skipping some traps and short gaps. Can only be executed forwards.
Use, pick up / drop item or weapon 	Space 	Makes the hero interact with environmental objects or pick up / drop items. Weapons cannot be dropped, only replaced.
Drop weapon or item 	Right Alt 	Makes the hero drop whatever he is carrying in his hands.
Open Icon Page 	Return 	Displays a statistics and inventory screen.
Instant healing 	F12 	Instantly fully regenerates the hero at a cost of 30,000 gold pieces.
Menu 	Escape 	Allows to save / load the game, access options and quit the game.
Quick save 	S 	Saves the game in a special quick save slot.
Hide / display Icon Bar 	I 	Hides or reveals the HUD.
Detailed Keyboard Layout

The exact actions executed by the character are largely dependent on the weapon/magic currently wielded and some other factors. The tables listed below describe each individual scenario in detail. The content of these tables is based entirely on the original game manual.
Unarmed

This is the command layout when the hero neither wields weapons nor magic.
Cursor keys 	↑ 	↓ 	← 	→
	Run forwards 	Walk backwards 	Turn left 	Turn right
Cursor key + Ctrl 	Double punch 	180° Elbow / Fist swipe 	Front left punch 	Front chop kick
Cursor key + Left alt 	Front flip 	Back flip 	Left roll 	Right roll
Cursor key + Ctrl + Left alt 	Front right punch 	Round house kick 	Left upper cut 	Right upper cut
Armed

This is the command layout when the hero is armed but not able to cast magic.
Cursor keys 	↑ 	↓ 	← 	→
	Run forwards 	Walk backwards 	Turn left 	Turn right
Cursor key + Ctrl 	Front stab 	180° back swipe 	Swipe 	Front chop kick
Cursor key + Left alt 	Front flip 	Back flip 	Left roll 	Right roll
Cursor key + Ctrl + Left alt 	Forward left punch 	360° swipe 	High head kick 	Round house kick
Wielding Magic

This is the command layout when the hero is unarmed but able to cast magic.
Cursor keys 	↑ 	↓ 	← 	→
	Run forwards 	Walk backwards 	Turn left 	Turn right
Cursor key + Ctrl 	Double punch 	180° Elbow / Fist swipe 	Front left punch 	Front chop kick
Cursor key + Left alt 	Front flip 	Back flip 	Left roll 	Right roll
Cursor key + Ctrl + Left alt 	Double handed magic

Lightning (medium power)
	Smart bomb

(strong power)
	Left handed magic

fire bombs (weak power)
	Right upper cut
Wielding Arms and Magic

This is the command layout when the hero is both armed and able to cast magic.
Cursor keys 	↑ 	↓ 	← 	→
	Run forwards 	Walk backwards 	Turn left 	Turn right
Cursor key + Ctrl 	Front stab 	180° back swipe 	Swipe 	Front chop kick
Cursor key + Left alt 	Front flip 	Back flip 	Left roll 	Right roll
Cursor key + Ctrl + Left alt 	360° swipe 	Smart bomb

(strong power)
	Left handed magic

fire bombs (weak power)
	Round house kick
Swimming Unarmed

This is the command layout when the hero is unarmed in deep water. Note that the hero is not able to pick up or drop items while swimming.
Cursor keys 	↑ 	↓ 	← 	→
	Swim forwards 	Swim backwards 	Turn left 	Turn right
Cursor key + Ctrl 	Swim punch left 	180° Elbow / Fist back swipe 	Left swim punch 	Right swim punch
Cursor key + Left alt 	Swim punch left 	180° Elbow / Fist back swipe 	Left swim punch 	Right swim punch
Cursor key + Ctrl + Left alt 	Swim punch left 	180° Elbow / Fist back swipe 	Left swim punch 	Right swim punch
Swimming Armed

This is the command layout when the hero is in deep water and wielding a weapon. Note that the hero is not able to pick up or drop items while swimming.
Cursor keys 	↑ 	↓ 	← 	→
	Swim forwards 	Swim backwards 	Turn left 	Turn right
Cursor key + Ctrl 	Front swipe 	180° back swipe 	Front swipe 	Front swipe
Cursor key + Left alt 	Front swipe 	180° back swipe 	Front swipe 	Front swipe
Cursor key + Ctrl + Left alt 	Front swipe 	180° back swipe 	Front swipe 	Front swipe
Armed with a magic weapon

This is the command layout when the hero is armed with a magic weapon but is not able to cast magic himself.
Cursor keys 	↑ 	↓ 	← 	→
	Run forwards 	Walk backwards 	Turn left 	Turn right
Cursor key + Ctrl 	Wand magic 	180° back swipe 	Swipe 	Front chop kick
Cursor key + Left alt 	Front flip 	Back flip 	Left roll 	Right roll
Cursor key + Ctrl + Left alt 	Forward left punch 	360° swipe 	High head kick 	Round house kick
Armed with a magic weapon and wielding magic

This is the command layout when the hero is armed with a magic weapon and able to cast magic himself.
Cursor keys 	↑ 	↓ 	← 	→
	Run forwards 	Walk backwards 	Turn left 	Turn right
Cursor key + Ctrl 	Wand magic 	180° back swipe 	Swipe 	Front chop kick
Cursor key + Left alt 	Front flip 	Back flip 	Left roll 	Right roll
Cursor key + Ctrl + Left alt 	Smart bomb

(strong power)
	360° swipe 	Left handed magic

fire bombs (weak power)
	Round house kick 

<img width="1536" height="1024" alt="EC2Recomp" src="https://github.com/user-attachments/assets/075a3032-6f1f-4af8-a826-4bc009e2a5f9" />

<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/4ece3d14-54d9-47f7-b96f-46216bd12594" />

