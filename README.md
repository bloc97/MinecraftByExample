MinecraftByExample
==================

The purpose of MinecraftByExample is to give simple working examples of the important concepts in Minecraft and Forge.
If you're anything like me, a good code example is worth several screens' worth of waffling explanation, and can very
quickly explain the key concepts.  I also find it much easier to adapt and debug something that already works, than to have to
synthesise something from scratch and spend hours trying to discover the missing bit of information I didn't know about.

Anyway, each example is split up to be totally independent of all the others.  The only parts of the code common to all
examples are the MinecraftByExample, CommonProxy, ClientOnlyProxy, and DedicatedServer classes.

I've tried to keep the code simple and obvious and to resist the urge to be clever.  You will probably see more efficient
ways to do things and to reduce some of the redundancies.

If you want more information and explanatory text about the concepts, the following links might be useful
Guide to how Minecraft works-  http://greyminecraftcoder.blogspot.com.au/p/list-of-topics.html
Forge Modding articles- http://www.wuppy29.com/minecraft/modding-tutorials/forge-modding-1-8
Forge Tutorials listing- http://www.minecraftforge.net/forum/index.php/board,120.0.html

How to use this example-
A) You can browse directly in GitHub, or alternatively download it as a zip and browse it locally.

B) If you want to install it and compile it, the basic steps for beginners are:
1) Download the project as a zip.  Unzip it to an appropriate folder on your computer, such as My Documents.  (Or, if you know
   how to fork a project on GitHub and import it into a local git repository, you can do that instead).
2) From the command line, run gradlew setupDecompWorkspace to install Forge and configure the project.  This will take
   quite some time, maybe 20 minutes or more.
3) From the command line, run gradlew idea if you are using IntelliJ IDEA, or gradlew eclipse if you are using Eclipse.
4) Open IntelliJ or Eclipse, then open the project.  If you want, you can import the gradle project so you don't have to
   use the command line when building the mod.

For some extra help if this doesn't make sense to you
http://www.minecraftforge.net/forum/index.php?topic=21354.msg108332#msg108332

Some extra help for installation of forge:
https://www.youtube.com/watch?v=8VEdtQLuLO0&feature=youtu.be
