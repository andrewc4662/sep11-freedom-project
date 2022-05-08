# Entry 4
##### 3/30/22
# current state
Since blog 3 the most progress has been made on the actual game and the final product. I went through many [phazer](https://phaser.io/tutorials/making-your-first-phaser-3-game/part1)lessons and learned a lot about how phazer works and what each code snippet does in the phazer js library. After doing that I came across a lesson that taught you how to make a game where the player has to collect stars and while they do it they have to avoid obstacles. I chose to study this lesson and go through with it as it matched my vision for a game perfectly. Since then I learned a lot about what affects a game and how to make a game a game. I learned that ` this.load.image` loads an image, `this.physics.add.collider` adds the physics and a collision where the sprites and the land/platform collide so that they stay on the screen instead of falling down the map/screen, `stars.children.iterate` would create multiple stars as that was what was in the stars variable and it would run every time all the stars have been collected,
<br>
 ``` 
function hitBomb (player, bomb)
{
    this.physics.pause();

    player.setTint(0xff0000);

    player.anims.play('turn');

    gameOver = true;
    
}
```
<br>
this would stop physics, set the characters color to red(to show they "died"), display the character in the set frame and it would set game Over to true which would set the score to say "You lost". There is many more things that I learned from that mini lesson about basically collisions.


# EDP
I would currently say that I am on step 7 of the [Engineering Design process](https://hstatsep.github.io/students/#edp) as I have a working prototype but I will keep improving as I want to make various changes to make it more unique than a simple lesson game. I have started on some changes and the main changes I want to do are having the whole game sort've cycle through like a tower game where you keep climbing the structure and my other idea was to randomize the spawns of the objects for points and I want to change the whole aesthetics of it. After doing these changes I feel like I would be at the final step of the EDP and present my final product to others.



# Skills
The major skills I have strengthened throughout the months I would say is my skill to learn and tinker as I would have to carefully read the lesson in order to understand what did what and how I could use this to change things in the future. This would later help me out as I would have an understanding on what did what and this skill could additionally help me in the future as I would have to use the skills of learning and tinkering to find out what something does whether in the code world or work space. Another skill I have strengthened is the skill of research as I had watched various videos on Phazerjs, I have followed many tutorials and I have tested various creations made with phazer all in order to get a feel of what could be made and what to sortve base off my project in the long run. I feel like this could also help me out in may as I would eventually have to study, search and learn about Ap chemistry and Ap Spanish so I could better raise my chanced of at least getting a 3 on both Ap tests and pass the classes with college credits.    
[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
