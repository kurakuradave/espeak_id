espeak_id
=========

Repository for eSpeak pronounciation rules and dictionary files in Bahasa Indonesia

This repository contains only two files:
id_list
id_rules

Installing these two files will enable eSpeak to read text in Bahasa Indonesia.

How To Install:
---------------
0. Install eSpeak (if its not yet installed):
```bash
$ sudo apt-get install espeak
```

1. Clone this repo, on a terminal, type:
```bash
$ clone https://github.com/kurakuradave/espeak_id
```

2. Navigate into the espeak_id directory and execute a command to get eSpeak to recompile it's pronounciation rules for Bahasa Indonesia:
```bash
$ sudo espeak --compile=id
```

3. Type the following command to get eSpeak to read an example text, using the rules for Bahasa Indonesia:
```bash
$ espeak -v id "Apa kabar?"
```
 
4. If you have Orca installed, go to Orca Preferences -> Voice -> Person then select Indonesia-test (id). Then open gedit, any text typed in gedit should be readable by Orca.

5. Enjoy! :) 
