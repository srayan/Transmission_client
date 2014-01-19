Transmission_client
===================

This is an altered Transmission settings.json file I use on my Pogoplug computer to handle automatic torrent enqueueing. 

When you have transmission running on a network attached computer, you can access the transmission URL only from the network, the computer is on. Transmission, which is a powerful but lightweight URL based torrent client allows you to add and download torrent files from a URL based GUI. With this transmission daemon setting you can add torrents to Transmission from any network in the world. However this script would not allow you to view the transmission URL window though. But it does get the work done.

I have a transmission daemon running on my Pogoplug computer at home. You can read more about the device on www.pogoplug.com. Additionally I also wrote about how I got transmission to work on it on www.srayan.tk.

This setting makes transmission look for new torrent files (and enqueue them for download) from a particular folder.
So should I need to initiate a torrent download on my PLug computer, and I am not in the home network; then I will just add the torrent file to a specified folder location on my Plug computer (I ssh into it from any location) and the transmission daemon will enqueue the torrent file and start the download onto one of the attached drives.

So by the time I get home, the torrent file is hopefully ready for me :)
