To use this bot:
1) Launch HatBot.exe

2) Click on Settings and type in your Twitch username, 
the bot username you are going to be using (This can be the same account).

3) Click on "Get my oauth token" and follow the 
instructions on the console. It should take you
to a website to login with your Twitch bot account.

4) Copy the oauth token into the area that says "oauth Token".
Do not show anyone else this token as then they will have access
to sending messages with that twitch account. You can revoke this token
at any time in your twitch account settings.

5) Navigate to "Character Request Settings" on the left, and change
the settings to your liking. Scroll down below for an explanation on each part.

6) You may want to add an OBS source for the next character request. These files are
in "stream sources" as "character_next.txt" and "character_next_image.jpg"

7) Close out of the program and launch it again. Press start to connect to twitch. Now
that the bot is set up, you can also click "autostart" so that the bot connects
as soon as you launch it in the future.

CHARACTER REQUEST SETTINGS EXPLANATION
Most of the commands only mods or higher can use the command. 
All of the commands can be customized but the examples I use
will be what I use for Smite.

Mod Request Character Command:
	How a mod can add a character to the request list. They use it by
	typing '!godreq Hou Yi' which would then add "Hou Yi" to the request list.

Mod Remove Character Command:
	When a request is complete, you want it removed from the list. A mod can
	type "!remove 1" to remove the request at the front of the list. They can also
	remove any other requests based on where they are in the list such as "!remove 3"
	to remove the third request.

Mod Replace Command:
	Sometimes a request needs to be replaced in the list because of a typo or something.
	A mod can type "!replace 3 Kuzenbo" to replace the third request with Kuzenbo.

Mod Insert Character Command:
	Sometimes a request needs to be inserted in a specific position. A mod can use
	this command to insert that request into any position and the requests behind it
	will be moved back. They can type "!insert 1 Ullr" to add Ullr to the front of the
	request list.

Mod Clear Character Command:
	All it does is clear the request list and make it empty. Just type "!clear".

User Show Character List:
	This is the command for ALL viewers so they can view which characters are in the
	request list. If someone types "!godlist" it will show the request list.
	Here's an example of what this command would show.
	(1 Ymir)(2 Ganesha)(3 Morgan Le Fay)(4 Ullr)

How to Request Command:
	This is for your viewers to know how to request! They should type this to learn if they need to sub, donate, or what.

How to Request Command Message:
	This is what the bot will tell the viewer after using the How to Request Command. For example if you set
	The How to Request Command to "!godrequest", you could have your bot say "Just sub to the channel and I will
	play a God Request for you!"

Text when there is not a request:
	This is what the text file for the next request will show when there are no requests.

Character Type:
	While this bot was designed for Smite, it can be used for any game. For example if you were using it for Dead
	by daylight, you wouldn't call them "god requests". You might just put Character Type as "killer" or "survivor".
	For smite I just put "God". It's for the lingo the bot uses for some of the commands.

Character Image Format:
	Just the type of images that the bot should use for the next character request image. This feature will probably
	be changed in the future to just include .png, .jpg, and other popular image types.