# eBrowserMod
Redirects the eShop's error page (when using a dns to block Nintendo's servers, for example 90DNS) to https://dns.switchbru.com/ (This is not my website)
  
Here's a little mod I made to be able to enjoy and use the internal browser. This probably is only for people who block Nintendo's servers. SXOS' Steal Mode does not work with this.
This just replaces two out of three errorpages with a page that rediricts to google.com, and replaces the original eShop domain whitelist to allow all domains. Works on 5.x-6.x.
  
* The eShop unfortunately still starts loading until it times out. I'll see if there's a fix for that in the future. 
Edit: the os seems to block touch and controller input except for the homebutton, so you still can't navigate while it is loading in the background
* Screenshots cannot be taken
* No cursor, only the select box.
  
~~**If you want to use the above eBrowser you need a Nintendo Account connected to a user. For those who don't have such an account, you should use Xortroll's Browser in Goldleaf, but then you can't launch it via the eShop applet. For those who're willing to take the risk:  Idk who originally extracted this, but thanks to FuryBagguette and Hippy Dave for providing links. **Should be 6.1 only, but 6.2.0 seems to work too for some users + MAKE A NAND BACKUP BEFORE PROCEEDING!**  
Original download from GBATemp https://drive.google.com/file/d/1-A9_ASsoOoKIsHyBp97QPjXzTYwHkXxj/view?usp=sharing**~~
  
Installation: Put the two folders in your `sdmc://[your cfw (atmosphere/reinx/sxos)]/contents` folder and make sure you have LayeredFS enabled.
You can change the icon of the eShop by modifying __Combined.bntx in ResidentMenu.szs.
See https://gbatemp.net/threads/tutorial-qlaunch-custom-menue-icons.519249/ for more info.  
It is also possible to change the launch sound, but for that you'd have to edit qlaunch.bfsar and replace qlaunch_0000004B.bfwav.  
There also is a modified version of the loading screen, but sharing that would be illegal. It can be found somewhere in a Discord tho (Qcean) 
![Image](https://cdn.discordapp.com/attachments/272399519570722826/535079649856716811/unknown.png)
