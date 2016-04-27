===============================================================================================
MCG76 MCPE WorldEdit plugin for PocketMine alpah 1.4x MCPE 0.10.x
===============================================================================================
This is a fun and time saving tool that give player power to build while walking over the block  

Testing Status:  Verified 
-Minecraft Pocket Edition 0.10.x
-PocketMine Server: Latest Alpha 1.4 Build 

===============================================================================================

MCPE WorldEdit alpha 0.5.0  - April 03, 2015

What's New?
- fixed bug in //limit command
- add new commands 
   - cylinder   - Usage: // cylinder [block id:meta] [radius] [height]
   - hcylinder  - Usage: // hcylinder [block id:meta] [radius] [height]
   - overlay    - Usage: // overlay [block id:meta]
   - walll      - Usage: // wall [block id:meta]
   - plant      - Usage: // plant [type] [radius] [spaces]
   
supported plant type:
tree, grass, tallgrass, rose, dandelion, redmushroom, brownmushroon, pumpkin, lantern, cobweb, water, lava, stone

   
@Commands: 

"// cylinder [block id:meta] [radius] [height]"  -- cylinder shape
"// hcylinder [block id:meta] [radius] [height]" -- holo cylinder shape 
"// overlay [block id:meta]"                     -- add top layer to exisitng block
"// wall [block id:meta]"                        -- create a wall 
"// plant [type] [radius] [spaces]          -- generate a forest 
  
"// wand"   	-- activate selection wand  -- Iron Hoe
"// copy"   	-- copy selected blocks
"// paste"  	-- paste selected blocks
"// cut"    	-- cut selected blocks
"// remove"    	-- remove selected blocks
"// sphere" [block id:meta] [radius]    -- sphere selected blocks
"// hsphere [block id:meta] [radius]"   -- holo sphere selected blocks
"// pos1"  		                   -- set position 1
"// pos2"    	                   -- set position 2
"// set [block id:meta]"        	       -- set selection blocks to specified block-name
"// replace [block id: meta] [block id:meta]" -- set selection blocks to specified block-name
"// desel"                         -- clear selection blocks
"// expand [size in times]"        -- expand size of selected blocks
"// grow [size in times]"          -- grow size of selected blocks
"// movedown [# blocks]"           -- move down selected blocks  
"// help"   -- dipslay help

$output .= "Commands: // cut, // copy, // paste, // sphere, // hsphere, // desel, // limit, //cylinder //hcylinder //overlay //wall //plant  // pos1, // pos2, // set, // replace, // help, // wand, // toggleeditwand\n";
					
					
@Usage Steps

Step 1 - make selection using "// wand" or "// pos1" "// pos2"
Step 2 - make changes using "// cut" "// replace" "// set" "// paste" or "// remove"
Step 3 - done

@Installation: 

Just drop .phar file into PocketMine Server plugin folder 
Restart server

@Bug Report:
Author: MinecraftGenius76 

================================================================================================

Youtube Channel: https://www.youtube.com/user/minecraftgenius76/videos
(Likes and Subscribe for more future videos)

Twitter: https://twitter.com/minecraftgeni76
Facebook: https://www.facebook.com/minecraftgenius76

Planetminecraft: http://www.planetminecraft.com/member/minecraftgenius76/
(Posted Projects)

Thanks for your support.
