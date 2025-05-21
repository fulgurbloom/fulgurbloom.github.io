---
title: Mother 3
---
The "modern era" of the EarthBound 64 community began in 2019 with a Discord server created by member legogarrettz (now PolyGarrett) to showcase his recreations of models and future game development endeavors. I (Kristen, formerly Zen64) worked on programming and modding games for most projects Garrett was involved with.

| Title                    | Developer        | Engine                    | Timeframe             |
| ------------------------ | ---------------- | ------------------------- | --------------------- |
| Unnamed(*?)              | JG Productions   | Blender Game Engine v2.79 | Apr. 2019 - July 2019 |
| OcarinaBound             | Garrett & Kristen    | Ocarina of Time           | Nov. 2019 - Aug. 2020 |
| Mother 3 Spin            | Garrett & Kristen    | Unity                     | Feb. 2022             |
| EarthBound 64 Recreation | Team Pollysoft   | Godot                     | July 2022 - Aug. 2024 |
| Project Chili            | The Chili Bois   | Unity                     | Jan. 2023 - Aug. 2024 |
| Scoville                 | Kristen              | Godot                     | Oct. 2023 + July 2024 |
| libdrago                 | Team Save Hiroki | Nintendo 64               | Nov. 2024 - Dec. 2024 |

---
#### JG Productions - Blender Game Engine
The first modern attempt at recreating the game began in April of 2019 by community member JG Productions utilizing the Blender Game Engine, a now defunct game engine running in Blender v2.79.

Future content note: I remember effectively none of this era, will need help for this.

-----
#### Garrett & Kristen - Ocarina of Time
Custom models of Flint and Lucas created by Garrett that were imported into Ocarina of Time, with Lucas replacing young Link and Flint replacing adult Link. Models and textures were created by Garrett, while rigging and mods applied to Ocarina of Time were done by me.

The project was covered by Tony from Hard4Games.
![](https://www.youtube.com/watch?v=Er1rHUiOCRI)

More misc. footage, with custom maps by Garrett and custom music imports by me.
![](https://www.youtube.com/watch?v=QxT_B2fTplg)
![](https://www.youtube.com/watch?v=5iDgFZzZSKI)
![](https://www.youtube.com/watch?v=nzdAJwSgR_g)
![](https://www.youtube.com/watch?v=OcTgjxmmhAQ)
snowwood would go on to create several animations utilizing the OcarinaBound ROM, which was built off of the Ocarina of Time Debug ROM, allowing for features such as custom cutscene creation.
![](https://www.youtube.com/watch?v=UgwXlL5pLYo)
![](https://www.youtube.com/watch?v=PNR2cd7A_xU)

Future content note: snowwood's custom animations post-OcarinaBound.

------
#### Garrett & Kristen - "Mother 3 Spin"
The first Unity build made by Garrett and I, internally dubbed the "spin" build for its unique attack animation which was later found to be a mistranslation. https://github.com/fulgurbloom/Mother3
Build is made within one month as a proof of concept and is quickly dropped due to burnout.
A rudimentary pork bean controller would later be implemented by Garrett.

This was the first private test video recorded of the project, which would then go on to be leaked to the then growing Chili Bois Discord server by a user named Snakeshroom.
![](https://www.youtube.com/watch?v=Y5JijLp6bdo)



![](https://www.youtube.com/watch?v=wFgUZ4SuAaQ)
![](https://www.youtube.com/watch?v=xeqzc20jWd8)

-----
#### Team Pollysoft - Godot "The EarthBound 64 Experience"
Team Pollysoft begins development on their recreation project, initially titled "EarthBound 64 Recreation" and later rebranded to "The EarthBound 64 Experience."
https://video-game-beta-remakes.fandom.com/wiki/The_EarthBound_64_Experience
![](https://www.youtube.com/watch?v=Arxu8pLnqlM)
![](https://www.youtube.com/watch?v=_cinEFntdnw)
![](https://www.youtube.com/watch?v=cZtoFUTEo0A)
![](https://www.youtube.com/watch?v=ReOQL4KpDIg)

August 2024 was the last time an announcement was made regarding development with radio silence following after, although development has supposedly continued internally.

-----
#### Kristen - Godot + Unity "Scoville"
Beginning in October 2023, I attempted to utilize Earthbound 64 assets and my existing knowledge of C# in attempts to learn the Godot engine under the title Scoville, a reference to the prior team name and a measurement of heat in chili peppers. Short-lived, but relevant.

In August 2024, I would go on to quickly recreate a rudimentary form of Project Chili's foundation in a less bloated and more easily testable format. All development done on this test was recorded... and completely forgotten and unused! Lots of wasted time toying with Unity's quirks, settings, and packages. Fun nonetheless.
![](https://www.youtube.com/watch?v=tuxxjFpJ28s)

-----
#### The Chili Bois - Unity "Project Chili"
The most mature demo developed by fans to date is *Project Chili*, with a team consisting of:

| Kristen           | Programming                    |
| ------------- | ------------------------------ |
| Garrett       | Art recreations                |
| SamTheSalmon  | Art recreations                |
| Echoes        | Writing, fact-checking         |
| PineappleCarl | Fact-checking                  |
| snowwood      | Art recreations, fact-checking |

The goal of the project was to recreate the [Spaceworld 1997](https://en.wikipedia.org/wiki/Nintendo_Space_World) demo build of the game as accurately as possible.

The project ends development in August 2024 as a final rough demo is built and sent off to *Kody Nokolo*, a controversial community member (vermin) visiting a Q&A session with Shigesato Itoi with intent to showcase the demo and give a copy to him. This did not happen. I left the project immediately after this for personal reasons. Garrett would then take over and invite a new programmer to briefly flesh out the battle system and implement new playable environments.

----
#### Team Save Hiroki - Nintendo 64 "libdrago"
A brief reach into the Nintendo 64 homebrew development scene. The team for this project consisted of:

| Me            | Programming     |
| ------------- | --------------- |
| Zucchino      | Art recreations |
| Picto         | Art recreations |
| SamTheSalmon  | Art recreations |
| Echoes        | Fact-checking   |
| PineappleCarl | Fact-checking   |
Utilizing [libdragon](https://github.com/DragonMinded/libdragon) and initially with the [raylib4Nintendo64](https://github.com/raylib4Consoles/raylib4Nintendo64) framework, this homebrew project aimed to create a barebones game engine capable of running on real Nintendo 64 hardware with the intention of creating new assets with greater accuracy than before.

Over time, raylib4Nintendo64 was scrapped due to its instability and lack of usefulness. Only a few screenshots were taken of this version of the project, its main features including a functional [[ECS]] implementation, model and texture rendering, and basic debugging tools. Much of the structure of this project was derived from a previous game engine developed by me, [[Bloom]]. Plans included utilizing a modified version of Bloom's ECS scene editor to efficiently create and modify levels usable on the Nintendo 64.

The first functional version build of the project, running in [ares](https://ares-emu.net/). At this point, the project was still utilizing raylib4Nintendo64, and in this screenshot you can see Raylib's `DrawGrid()` and `DrawModelWires()` functions in use with a model of Flint created by Picto.

![[libdrago_raylib_poc_nov2024.png]]

This video was taken on TheJokerDeluxe's Nintendo 64 when I was visiting him while he was sleeping on the couch, ignoring his guest.

![[libdrago_raylib_render_nov2024.gif]]