---
title: "Feasibility"
date: 2022-03-30
publishdate: 2022-03-30
resources:
- name: featuredImage
  src: "cover.jpg"
---
### Is my project idea feasible?
 
One of the most important factors in starting a project is determining whether it is actually possible or not. In this post, I analyze the feasibility of my current project idea.
 
### Hardware
 
*What hardware equipment is necessary to run this project?*
 
The system requirements for the Unity Editor on Windows are the 64-bits versions of Windows 7, 10, or 11; CPU with X64 architecture with SSE2 instruction set support; graphics API or DX10, DX11, and DX12-capable GPUs. My personal machine does reach the first two requirements for sure. I can not find what my machine's graphics API is, but I believe this requirement is met as well.
 
I can not find specific requirements for the most recent version of Godot, but the consensus is that Godot has lower requirements than Unity. Therefore, it is likely that Godot would run just fine on my machine.
 
### Tools
 
*What software do I need to complete your project?*
 
Software wise, I am between using the Unity or Godot game engines. If I choose Unity, I will need the C# programming language. If I use Godot, I will likely be using GDScript, but there is also support for C#, C++, and C.
 
### Skills
 
*What skills do I need to complete your project?*
 
I will need to gain skills working with the game engine of my choosing. At the moment, I open up the Unity Editor and am immediately overwhelmed by all of the various functions and buttons. I will definitely need some time to get accustomed to a game engine to understand what I'm looking at. I am also unfamiliar with C# and GDScript and will need to learn a new language no matter which engine I pick. I'm confident that I will be able to pick up on a new language fairly quickly. The most scary and tricky part of this for me is my lack of knowledge of content generation algorithms. I fear that there are just so many out there with very little code or documentation available.
 
### Time
 
*How long do I anticipate for this project to take? How long will each part of the project take to complete?*
 
Estimating the time this will take me is fairly difficult due to my lack of knowledge on the subject. I can imagine that actually developing the code that generates the map will take longer, as this is the bulk of the project. Overall, developing this code may take a month, with various aspects of this large task being broken down into smaller time segments. Initial code and graphics may take a week, with a second week being devoted to tweaking and debugging. At that point, hopefully the third week will be left to polish up the product; resolving any remaining issues. After that, a month's worth of time will likely be devoted to analyzing my results. I'm sure that even after the first month, the code itself may need additional tweaking. Hopefully the second month will consist of me winding down and really finishing the code and determining whether the results are "successful."
 
### Results
 
*What do successful results look like? How will I test my project for both correctness and efficiency?*
 
I think that determining what "success" is may be its own aspect of the project. Since the current idea for my project is to generate game maps, the success of the outcome may be subjective. One clear factor I can think of right now is the playability of the map. If generated rooms are inaccessible or destructive, that would be an unsuccessful outcome. I believe that success may be determined by how appealing the maps are as well, but this will be tricky to define.
 
### Analysis
 
*How will I analyze the results? What experiments will I run to demonstrate my project and obtain results for analysis?*
 
I plan on analyzing the results based on whether the map is appealing and playable. I hope to define factors that contribute to whether a map was "appealing" or not. I hope to test playability by determining whether the map actually works in a game setting. It would be great if I am able to make a character to traverse the levels as well in order to make a simple game that will utilize the maps I generate. In that case, experiments may include manually testing the maps by playing through them.
 
### Threats to Validity
 
*What might invalidate my reported results?*
 
My project could be invalidated by claims that it is not complex enough or that it is not a very academic topic. My results could also be invalidated if my definition of a "successful" level is not the same as the reviewers' definition. What I consider to be a success may not be what they consider to be a success. It is also possible that reviewers may not like the algorithm or generation method that I use. They may think that it is too simple, inefficient, or something along those lines. It is also possible that the randomness of the generated map may make it hard to reproduce exact scenarios.