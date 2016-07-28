###Hosts and Targets
The Holonforth IDE's are cross-development systems. We use the Host/Target concept usually applied to embedded systems. 
The IDE is the host that develops into a target application - via an umbilical (tethered) connection. 

Every Holonforth-DOS system is a *host* when you use it for application development. But the systems have themselves been developed as *targets* of Holon86 - including Holon86 itself (since the day when Holonforth was on its own). 

###Projects
Holonforth IDE's are devoted to a specific application. For a new project you create a copy of the Holon-system (86, 11, J or X) and give it the name of the project or application. The IDE stores the state of development and restarts with the project exactly as you left it. You can continue to develop immediately.

The repo includes the four projects Host86, Host11, HostJ and HostX that were used to develop the respective IDE's. These projects contain the source code for the following Holonforth systems.


###Holon86 
DOS->DOS Forth IDE

http://www.holonforth.com/holon86.html 
  
Develop umbilically from DOS to a DOS application 

###Holon11 
IDE for 68HC11 targets

http://www.holonforth.com/holon11.html 
 

###HolonJ
Forth to JVM IDE

http://www.holonforth.com/holonj.html
  
Compiles Forth to JVM code - Write Java programs in Forth.

###HolonX
A universal source code handler and refactoring browser with change control (validation).

http://www.holonforth.com/holonx.html

###DOSBox

These systems run in Windows XP and earlier  
and in a [DOSBox](https://www.dosbox.com/wiki) everywhere

