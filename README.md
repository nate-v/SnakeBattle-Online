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
    1. Open command prompt, run "ipconfig" and feed the IPv4 address
        into the ip variable in the constructor. NetworkListener does
        not need the ip because it listens on the port, not the address.
    2. Allow your JDK through the firewall, it likely will not prompt you.
        You must have administrator access. If you are on JGrasp, the
        bundled JDK is located in C:\Program Files(x86)\jGrasp\bundled\bin
        Allow java.exe and javaw.exe through the firewall for both private 
        and public networks. Secondly, if this does not work, allow the jar
	      file "SnakeBattleOnline" located in the same folder as this README
	      through the firewall.
    3. The port number can be whatever you want. It will crash if the port
        number is already in use. Open command prompt and run "netstat -a -n -o"
        to see all active ports. Do not use any ports in the UDP section. Most likely
	      any number you randomly think of between 1000 and 65535 will not be in use.
    4. If it still does not work, create a new inbound rule by going to control panel ->
        system and security - > windows defender firewall -> advanced settings -> 
	      inbound rules -> new inbound rule.
    4b. Choose "port", "UDP", and either allow a specific port or all of them through
	      public and private. If you want to play across different Wi-Fi connections, 
	      create an outbound rule the same way (playing across different connections is 
	      very unreliable, and may not work).

You MUST run the program through the JAR file, do not use a compiler to run any classes
or else it will not work properly.
