# port-vesper

Port Vesper — Night Shift (major update)

A full rewrite of the engine and a substantial expansion of the game. ~2,500 → ~6,200 lines.

Visuals

New layered renderer: cached ground chunks, a separate additive light buffer, and a post chain (grade → wet reflections → vignette → film grain). Previously everything was drawn in one flat pass.
Night-first art direction — sodium streetlight against cyan-black, with real pools of light and wet-road reflections.
Buildings now have per-window lighting, roof furniture, parapets and neon signage; cars are tapered hulls with turning wheels, brake lights and visible crash damage; pedestrians have limbs and a walk cycle.
Weather (rain, wind, lightning), a day/night cycle, blood/scorch/skid decals, and screen feel — hitstop, trauma-based shake, muzzle light.

City

The uniform grid is gone. Avenues and side streets now differ in width, and blocks vary in size.
Five districts with distinct palettes, building heights and props: Financial, Old Quarter, Port Authority, Foundry Row, Vesper Heights.
A working harbour with piers, cranes and water you can drown a car in.

Gameplay

Four contacts with ordered job chains and unlockable perks; six mission types (steal, deliver, wreck, wipe, escort, heist).
Three gangs with territory and hostility tracking.
Gunplay rebuilt: magazines, reloads, recoil and accuracy bloom, plus grenades and molotovs.
Vehicle upgrades and nitrous, chop-shop want lists, buyable property with nightly income.
Police escalation: roadblocks at 3★, helicopter with searchlight at 4★, SWAT at 5★. Dispatch now broadcasts your car's description — a respray breaks the match.
Rebuilt traffic AI and oriented vehicle collision; save/continue support.

Interface

Redesigned HUD, minimap and city map, plus a contacts phone, dispatch radio log and kill feed.
Expanded procedural audio.
