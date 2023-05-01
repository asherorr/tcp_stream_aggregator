Hello all!

Cybersecurity professionals know that TCP is a continuous stream, and that the TCP stream is divided into packets arbitrarily. The divisions don't indicate anything significant about a message.

This script allows you to download an entire TCP stream into one text file. This way, you can search through it with VIM.

You can use display filters on Wireshark to look for relevant information, but it's way easier to use VIM on the text file.

Why? Because if you use the display filter on Wireshark, you still might have to click on many individual packets and look within them.

Thus, searching through the text file with VIM can make searching for relevant data faster. 

You can also apply filters to the stream aggregator itself, so that you can specify the data that enters the text file- like, only accepting transmissions that contain a certain IP address you're targeting.

Thanks for reading!