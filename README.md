# beamerthemeMilano
Milano, an effective and modern beamer theme designed to deliver outstanding (scientific) talks.
Heavily insipired by the great material provided by Jean-luc Doumont, that you can find at [https://principiae.be](https://principiae.be/X0303.php), including his awesome book "Tree, maps, theorem".

Based on the beamer theme "Verona", its uses the awesome "Fira" font family (used by Firefox too).
Due to the font family used, it **does not compiles under pdfLaTeX**.
It compiles under **LuaLaTeX only**. This makes no practical difference to my experience.
To compile with LuaLaTeX, just change the compiler of the editor you are using.

Does this theme has options?'''
Not at all! But for intelligent reasons.'''
- do you want to add your name, date and location to every slide? No way you can do it here! Why? Because that is just ~graphical noise~ that row against the aim of delivering your messages. These information goes at the beggining and at the end of the talk, which is where people will wonder who you are and what day is it. 
- do you want a side panel showing the progress fo your talk? Go back to hell! No way you can do it with this theme. That's, again, just ~graphical noise~ that decrease the Signal-to-Noise ratio of your slides. It distracts people, letting them wander how many slides are still missing.
- But can I have an option to add the slide number? No, you can't. Again, this is another example of graphical noise that reduced the SNR of your talk. Even worse if you'd also put something like 14/52. Then people will stare at it in dispair.
- Can I change the color scheme? Well, if your really want to, yes sure. Just dig into the .sty file and found the part where the colors are defined, and change their RGB triplet. 
