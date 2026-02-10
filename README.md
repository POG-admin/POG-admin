🌌 MoonsecV1.2

> “We are a galaxy, and every map is a star.”
“Should you build it? No, you load and customize.”


MoonsecV1.2 is a creative build loader engine designed to let you instantly load, customize, and interact with builds, fanmade content, and maps — all inside a lightweight, command-driven system.


🚀 Overview

MoonsecV1.2 isn’t just a loader. It’s a miniature cosmic ecosystem:

Engine: MoonsecV1.2

Systems: Collections of maps (like solar systems)

Plansets: Official, number-coded builds (“plain sets”)

FMOs: Fanmade Maps Original — unique, first-of-their-kind community submissions

AFCs: Added Fanmade Content — team-reviewed and slightly modified FMOs

Message Loops: Automatic credit & info display when loading content


Moonsec translates builds into executable commands, reconstructing maps part by part. Think of it as decompiling, rebuilding, and making it work… all in one command.

🌟 Loader Philosophy

1. Load, don’t build.
Most content is ready to use. Customize it, tweak it, or combine it — no need to start from scratch.


2. Cosmic branding.
Every map is a star, every system is a galaxy, and MoonsecV1.2 is the engine powering your universe.


3. Community & originality.
FMOs allow fans to submit original maps. AFCs let the team refine these while still giving full credit to creators.


4. Controlled flexibility.
Numbers for standard builds (Plansets), strings for unique content (FMOs), ensuring order within chaos.

⚡ Using MoonsecV1.2

Loading a Planset

local code = 2567  -- Number for Planset
-- Moonsec will automatically load the corresponding build

Loading an FMO / AFC

local code = "hell"  -- String code for fanmade map
-- Moonsec checks for originality and team-reviewed status

Message Loop & Credit System

When loading FMOs / AFCs, Moonsec automatically posts messages like:

"FMO: HorrorHouse by UserX loaded!"
"AFC: Modified version by Moonsec Team loaded!"

This ensures proper recognition for creators.


🪐 Contributing

Want to add a Planset or FMO?

1. Submit your build in the #suggestions channel on our Discord.


2. Ensure it’s unique to qualify as an FMO.


3. Our team will review and, if approved, create an AFC version for integration.


🔧 Technical Notes

All builds are reconstructed using the command system:

!addpart me color transparency reflect shape material surfacetype anchored collision size offset rotation name

Numbers (e.g., 2567) are used for standard Plansets.

Strings (e.g., "hell") are used for FMOs / AFCs.

Loader ensures uniqueness and proper dispatching internally.

🌌 Tagline

> “We are a galaxy, and every map is a star.”
“Should you build it? No, you load and customize it"

This README establishes MoonsecV1.2 as both a functional engine and a creative universe.
