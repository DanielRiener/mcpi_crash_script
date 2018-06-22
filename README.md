# mcpi_crash_script

from mcpi.minecraft import Minecraft
from mcpi import block	  

mc = Minecraft.create("ip adress", 4711)
while True:       
	count = 0                           
	x, y, z = mc.player.getPos()  
	mc.postToChat("yeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeet")

	mc.setBlocks(x+100, y, z+100, x-100, y-100, z-100, 0)
	count = count
