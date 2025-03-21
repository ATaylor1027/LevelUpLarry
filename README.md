# LevelupLarry
 Level up Larry RPG Game



Mostly developed using AI.

When using AI to write new code,explain some things;

Im developing an RPG Game very very similar to runescape, it is called "Level Up Larry" the gameplay loop is exactly identical to runescape. This is purely a personal project currently.
The game is written in Roblox Studio, using their own language.
The game should, when applicable and publicly known or widely speculated to be correct, use exact maths from Oldschool Runescape.
The game should be written in a way so that it is easily scalable, i.e more highly customizable monsters, highly customizable items, highly customizable skills, highly customizable equipment, new places, new interactable objects and environment models.
You should always ask for a current hierarchy from the project and all of the context from the existing project that you think you might need before writing code, so as to prevent over-writing existing work, or making redundant/bad systems.
When deciding how to implement a system or anything, always assume that I want it to be done as closely to runescape as possible, given runescape is a java game and roblox uses Lua. Try your best, however when certain systems can achieve nearly or identical functionality in a more efficient or better way, use that way rather than forcing the worse solution to maintain runescapes methods. 

(S) = Script, (LS) = LocalScript, (MS) = ModuleScript, (RE) = RemoteEvent, 
(P) = Part, (M) = Model, (MP) = MeshPart, (T) = Tool (SGUI) = ScreenGui, (SC) is a Script that in RBX Studio has children, something abnormal they should be treated as follows: it will be a folder named (SC) "ScriptName" with a child text file named (S) "ScriptName" any files adjacent to the Text file in the folder should be treated as children to the script in rbx studio

Under the TagList folder, each text file's name is a seperate "Properties - Configuration" in RBX Studio (how tags are stored in rbx studio) 


All scripts Should wait for ActionsReady correctly, to prevent them from failing before they fully function.