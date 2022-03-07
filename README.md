# Milano, a beamer theme designed to deliver outstanding (scientific) talks.
Heavily insipired by the great material and ideas provided by Jean-luc Doumont ([https://principiae.be](https://principiae.be/X0303.php)) this theme originates from the lack of a theme following *strictly* his philosopy and guidelines.
It combines the popularity of beamer with the best suggestions around, in a theme that will bring your talk to stand out for its clarity, design and professionality.
Invest in your talk: use this theme and understand the ideas behind it to enhance your presentations and stand out of the crowd.
Designed from scientists for scientists, every design choice can be easily understood and sustained by a scientific-method approach to design and formatting.

Find out more in the detailed example.

Based on the beamer theme "Verona", it uses the awesome "Fira" font family (used by Firefox too).
Due to the font family used, it **does not compile under pdfLaTeX**.
It compiles under **LuaLaTeX only**. This makes no practical difference to my experience.

Does this theme has options?
Not at all! But for intelligent reasons.

- do you want to add your name, date and location to every slide? No way you can do it here! Why? Because that is just *graphical noise* that row against the aim of delivering your messages. These information goes at the beggining and at the end of the talk, which is where people will wonder who you are and what day is it. 
- do you want a side panel showing the progress and structure of your talk? Go back to hell! No way you can do it with this theme. That's, again, just *graphical noise* that decrease the Signal-to-Noise (SNR) ratio of your slides. It distracts people, letting them wander how many slides are still missing.
- But can I have an option to add the slide number? No, you can't. Again, this is another example of graphical noise that reduces the SNR of your talk. Even worse if you'd also put something like 14/52. Then people will stare at it in dispair.
- Can I change the color scheme? Well, if your really want to, yes sure. Just dig into the .sty file and found the part where the colors are defined, and change their RGB triplet till it fits your ugly taste. 

### Usage
Download the .sty file (or the whole folder with examples) and place it in the same folder the the .tex file of your talk is.
Change the beamer selection to \usetheme[]{Milano}.
Change the compiler to LuaLaTeX.
Compile and enjoy.

## Examples
- MWE: minimal working example that compiles and nothing much more
- MIexample: my example, a structured and detail walk-trhough in the ideas of this theme.


# WORK IN PROGRESS, PASS BY AT THE END OF THE SEMESTER
