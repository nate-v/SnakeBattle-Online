Java Development Kit version 26 is required to run SnakeBattle Online.
https://www.oracle.com/java/technologies/downloads/#jdk26-windows

```
© 2026 Nathan Vailikit. All rights reserved.

      []
      []
[][][][] ███    ██  █████  ██   ██ ███████ 
[]       ████   ██ ██   ██ ██  ██  ██      
[][][][] ██ ██  ██ ███████ █████   █████   
      [] ██  ██ ██ ██   ██ ██  ██  ██      
██████[] ██   ████ ██   ██ ██   ██ ███████ 
      [][][][][][][][]                                  
██████   █████   ███[]███ ████████ ██      ███████ 
██   ██ ██   ██     []       ██    ██      ██      
██████  ███████     []       ██    ██      █████   
██   ██ ██   ██     []       ██    ██      ██      
██████  ██   ██     []       ██    ███████ ███████ 
                    []                            
 ██████  ███    ██  []       ██ ███    ██ ███████ 
██    ██ ████   ██  []       ██ ████   ██ ██      
██    ██ ██ ██  ██  []       ██ ██ ██  ██ █████   
██    ██ ██  ██ ██  []       ██ ██  ██ ██ ██      
 ██████  ██   ████  [][][][] ██ ██   ████ ███████ 
                          []                  
                          [][][][][][][] 🍎


SnakeBattle Online is a multiplayer, networked snake game that supports up to 4 players. Slither around
to eat apples and gain power-ups to try to take down your friends. This game was created as a CS final
project, developed over the course of one and a half months.

IN ORDER TO IMPLEMENT ON THE FCPS NETWORK (OR ANY RESTRICTED NETWORK):

    1. Allow your JDK through the firewall, it likely will not prompt you if you are on a restricted network.
        You must have administrator access. To do this, go to control panel -> system and security -> windows
		defender firewall -> allow an app through firewall -> change settings.

			The JDK is located in:
			C:\Program Files\Java\jdk-26\bin
			(Make sure it says jdk-26 or higher, you need JDK26 or higher in order to run SnakeBattle Online)

			If you are on JGrasp, the
        	bundled JDK is located in C:\Program Files(x86)\jGrasp\bundled\bin

        Allow java.exe and javaw.exe through the firewall for both private 
        and public networks.

    2. If it still does not work, create a new inbound rule by going to control panel ->
        system and security - > windows defender firewall -> advanced settings -> 
	      inbound rules -> new inbound rule.

		Choose "port", "UDP", and either allow a specific port or all of them through
	      public and private. If you want to play across different Wi-Fi connections, 
	      create an outbound rule the same way (playing across different connections is 
	      very unreliable and may not work).

You MUST run the program through the JAR file; do not use a compiler to run any classes
or else it will not work properly.
```
