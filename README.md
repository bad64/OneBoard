# The One Board
### (Yes this is a very lame name)

Modular board for the [Gnome](https://github.com/bad64/OpenFightStick/tree/main/Gnome) and [Goblin](https://github.com/bad64/OpenFightStick/tree/main/Goblin) enclosures.

## Tools

- A soldering iron *or* hot air station. Hot plate could potentially work but I don't have one.
- Enough hotswap sockets for your layout of choice (a full board requires 21 sockets)
- 5 6x6 tactile switches, height to taste and function (Both the Gnome and Goblin use 9.5mm tall switches)
- An ESP32-S3-WROOM-1 module if you opt to not have it soldered by your boardhouse of choice. **DO NOT get the ESP32-S3-MINI-1x**, it is not compatible with this board !!

## Ordering guide

Order from JLCPCB (other boardhouses might work, this is just the one I tried). Tweak the order to your liking, but make sure to choose Standard PCBA instead of Economic PCBA. The ESP32 is a Standard-only part for some reason. If you feel confident that you can solder it yourself feel free to omit it from your order, you'll save a few bucks !

## Soldering guide

What neither the BOM nor Pick & Place file includes is what's left for you to solder on, namely the Kailh Choc hotswap sockets, and maybe the ESP32-S3-WROOM-1 if you opted for the cheap SMT option. They're all easy but since there's a whole gaggle of sockets, it's gonna take a minute.

Just remember to do the sockets first: the tactile switches tend to get a bit in the way...

### The sockets

TODO: Pics

If you have a hot air station, this is massively easier as you can just tin both pads (or use solder paste), place the socket, then heat it. Just push'em down firmly with something heat resistant and wait for them to set. (I probably don't need to teach you how to use a hot air station but this is for the sake of being exhaustive)

If not, grab your iron, a thin spade bit, and lightly tin one of the pads, you want barely a millimeter of the stuff on the pad. Place the socket in the holes, heat up the tinned pad again (add more solder if needed) then push down on the socket with something heat resistant. **Maintain the socket while the solder cools.** Then do the other side, make sure the solder makes a strong connection between the pad and pin (you should not be able to lift off the socket once you're done)
