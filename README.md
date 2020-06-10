# tmc-instructions
Installation guide for installing the TMC plugin in Intellij. 

## Management summary
1. Download and install JDK 1.8: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html. You may 
have to create an Oracle account - use 10minutemail.com to remain anonymous.
1. Make sure `javac -version` returns `javac 1.8.0_251` or similar when run in the command line
1. Download and install Intellij IDEA Community Edition 2018.3.6 from https://www.jetbrains.com/idea/download/other.html
1. Startup IntelliJ and create or open any project, it does not matter which
1. File > Settings > Plugins. Look for TMC and install the plugin. This will start prompting you with all kinds of 
questions. Just go with the flow, login and start coding!


### FAQ
##### Q: `javac -version` returns another version or nothing at all?
Make sure your system PATH variable points to the JDK/bin folder. Help can be found here for windows: 
https://mkyong.com/java/how-to-set-java_home-on-windows-10/ and here for MacOS:
https://lmgtfy.com/?q=how+to+add+to+system+path+javac+macos

##### Q: I need to run a higher Java version for my job/hobby, or I just hate being behind. What can I do?
Using 1.8 is the most straight forward way, but I also heard some students getting results with other versions. Try at 
your own risk, not for the faint of heart. If you really cannot change the system PATH, you might achieve succes by 
using a different laptop or by running a VM. I had great results by using Ubuntu last year.

##### Q: I'm already using a more recent version of IntelliJ IDEA, can I use that one instead?
NO! Something broke in the backwards compatibility when IntelliJ IDEA moved to 2019.x and higher. However, you can run 
multiple IntelliJ IDEA installations on the same computer without issues. I have two installations on my machine,
and to help keep them apart. I have setup one of them in dark mode, and the other one in light mode.

##### Q: Why aren't we using Netbeans, while Intellik is constantly showing a BETA warning?
The TMC people are currently doing an overhaul and I could not find the Netbeans plugin. I know that the Intellij one
still works when following a strict set of rules, so this is this is now the recommended path.

##### Q: I have a suggestion for the process or I want to change your Dunglish to English?
Any feedback, suggestions or improvements can be put in an issue, pull request or if you have my address: an email.

##### Q: I have an unanswered question!
Same as the previous Q. Please ask your questions. If I notice the same question popping up more often, I'll update 
the process.
