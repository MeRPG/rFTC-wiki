# /r/FTC Wiki
This readme will act as a guide for how to edit the wiki according to guidelines. __If guidelines are not met, your pull request will NOT be fulfilled__

***Remember, if you want to contribute, make a fork, and then submit a pull request to master.***

## Guidelines
 - All files must be written in Reddit-compatible Markdown syntax in Markdown (\*.md) files.
 - The text must adhere to a reasonable definition of *Gracious Professionalism*
 - It is recommended to write in 3rd person as much as possible. *i.e. "Our team, XXXXX, did try etc." versus "Team XXXXX tried using etc."*
 - You must adhere to the following file layout unless an urgent reason is provided, major changes to the file layout is discouraged. New files, however, can be added easily provided a good reason.
```
rFTC Wiki (From the point of view of the front page)
"Appearance" is to clarify how pages will look to the
user.
(MAIN) /r/FTC Wiki
       |-(FOLDER) building-systems
       |          |-(FILE) MATRIX-Robotics
       |          |-(FILE) TETRIX
       |          |-(FILE) GoBilda
       |          |-(FILE) Actobotics
       |          |-(FILE) VEX-EDR
       |          |-(FILE) VEX-Pro
       |          |-(FILE) Andymark
       |          |-(FILE) REV-Robotics
       |          |-(FILE) 8020
       |          |-(NOTE) It is discouraged to add 
       |          | pages for individual building 
       |          | components of little importance, 
       |          | however, if an important part 
       |          | like a ServoBlock is given an 
       |          | article, it can be placed into a 
       |          | folder with the same name of the 
       |          | building system and placed in 
       |          | this directory.
       |-(FOLDER) programming
       |          |-(FILE) ftc-app
       |          |-(FILE) java-tutorials
       |          |-(FILE) android-phone-connections
       |-(FILE) building-systems <-Appearance:
       |                          "Building Systems"
       |-(FILE) programming
       |-(FILE) getting-started <- For rookie teams
       |-(FILE) starting-a-team
       |-(FILE) frequently-asked-questions
       |-(LINK) FIRST Tech Challenge
       |-(LINK) /r/FTC
       |-(LINK) FTC Forums
       |-(LINK) Chief Delphi
```
## Guidelines (continued)
 - Git pulls must have all changes documented, excessive commits are discouraged.
 - All files must start with the latest header format specified in header.md
 - All files must end with the latest footer format specified in footer.md
 - All hyperlinks that reference other /r/FTC wiki pages must reference itself relative to the subreddit.
 For example:
 ```Markdown
 More information is at [Java Programming](/r/FTC/wiki/programming/java-programming).
 ```
