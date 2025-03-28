# Week 06 - Level Design 2
In today's prac, we are continuing our work on level design, creating further artefacts and iterations of our level. This is the second last prac before your assignment is due, so you'll want to ensure you have something ready for testing and polishing next prac. Remember that the assumption is you are also working on your assignment outside of class.

More than ever, the timings presented here are indicative. You are now at a stage where we have given you all the tools for good level design, and trust your ability to go forth and build. Follow this lesson plan to ensure you are hitting your goals, but don't worry if you end up lingering on one area for longer.

## Tools used
Today's task uses (but is not limited to):

* GitHub Desktop (or your GitHub client of choice)
* Unity
* Xbox Controller (Available from your instructor)
* Whatever prototyping tools you want!
  
## Assignment deliverable
Today, you will be creating a geometric prototype of your level, as well as completing the final section of the level. Don't worry if you don't get it all perfect - the idea is to have fully-sketched out your level by the end of today so you can work on further iteration.

## Section 3 (20 min)
Depending on how you went last week, you might already have the plans for Level 3. If not, now is a good time to work on this section.

Go through the steps of different prototyping methods from last week (narrative and topological layers). You should now have a bit of a better idea about the kind of prototyping that works for you, and may even want to experiment with the ones mentioned in the lecture. 

Whatever you do, <b>Make sure you are capturing your prototypes and storing them in the assignment repo</b>. A big part of your mark is going to be that you've engaged in an iterative process, so you need to make sure you can evidence this.

## Geometry Layer (20 min)
With all your sections constructed, it's time to build a geometry layer prototype. The geometry layer, as discussed in the lecture, is all about how the level fits together. Perhaps the most technical of all prototypes, this is where we need to consider the precise layout and arrangement of objects in our level. It can be very tempting to hop straight into engine and just start building out our level, but doing so we can get distracted on the wrong thing (polishing the level before it is ready, for instance). While the process of in-engine prototyping (like greyboxing) is quite valid, if you take this path, you must resist the urge to start placing down everything in the first run. Know thy self and choose your path accordingly.

### Some examples
Ultimately, you want to be building a to-scale level map, so something more precise than sketches or doodles is needed. Here are a few methods of geometry layer prototyping to try:

#### Annotated Level Map
Annotated level maps are drawn (by hand or using a drawing program) to scale, showing the layout of the level in a far more practical sense. Below is a rather "zoomed out" level map, but you may want to draw three different ones (one for each section) to give you the relevant level of fidelity. Using grid paper or something else with defined dimensions for scale is important.

![An image of a "zoomed out" geometric map of Hollow Knight, from Team Cherry.](images/HollowKnight.jpg)

#### Lego/Building Blocks
While we don't have Lego in class, this could be a method you experiment with at home. The idea here is that you are creating a physical representation of your level with defined dimensions. Although the level we are creating is 2D, seeing it from another angle can be an important part of design. Using blocks like Lego also gives great flexibility for reconfiguring your level as you work out the specifics.
![An image of Lego being used to create a level, from gamedeveloper.com](images/lego.png)

#### Greyboxes
Greyboxing is a digital prototype that is in some way "playable". It may not be made in the engine you are using for your final game, and instead built with more basic tools. For this assignment, it probably makes sense to use the Tile Map Editor and greybox in Unity, but be careful about fidelity. One of the good things about greyboxing is that it allows you to get something playable without worrying about set-dressings, etc. You don't want to add more than you need, because that makes things harder to iterate on and edit.
![An image of a greyboxed level of Celeste, by Maddy Makes Games.](images/Celeste.png)

Spend some time building your prototype, and consider the player's paths through it, possibly even annotating it by drawing lines through the level. Now, ask yourself:

* Is my level fully navigable? Can the player soft-lock themselves anywhere, or are there parts that they simply can't get to?
    * If there is a section that is locked off after a certain time, is this a deliberate part of the experience?
* Does my level encourage exploration? Are there loop-backs, hidden paths or anything else like it?
* Does the player need to clear all of Section 1 before moving on? If not, can they accidentally stumble into an encounter where they must use mechanics they haven't been taught about yet?
* Are connective spaces present and well designed, or are they just long-slogs with nothing to do?

Be brutal about your level and how it fits together. Don't be afraid to make some changes before...

## Building in Unity (20 min)
Time to build your level for real! Translate your geometric prototype (with any changes you've identified) into Unity, building out these sections. You may find that the actual implementation into engine results in a few more design changes for practical reasons. That's okay, but you should try to make sure you are iterating on your prototype, not just throwing it out and starting again!

Remember, you can use the Select tool in the Tilemap editor to move around chunks of tiles, so you could even build your level with your encounters being re-arranged here and there.

This is also a good time to get a controller and start playing the game with one, as you will begin to see the level in a new way when switching to the more common platformer control scheme. Ask your instructor for one.

## Back and forth prototyping (35 min)
Design is iterative. Move back and forth between your prototypes and your level, maybe even constructing new ones, as you refine your level. Let your design be driven by the following questions:

* Is there a natural path through the level? Is this the journey I want the player to go on, or are they missing things?
* Do my encounters nicely build on one another? Is the player ever put in a situation where they might not know what to do/how to progress?
* Are there any unintended challenges due to quirks in my level design? E.g., a jump that is supposed to just get from one part of the map to another is difficult because of the platforms around it. How do I fix this?
* Is the difficulty in my level providing an appropriate level of challenge, or is it "difficult for the sake of it"?
* Does my level encourage the player to explore? Can I include some more secrets, or a couple of alternative routes? How might I incentivise the player to take these routes (items, more challenges, shortcuts, etc)?
* Does my level give the player opportunities for discovery? Do I tell them everything, or let them try things out and see what happens?

As stated before, make sure you are capturing your prototypes. Regularly push to your assignment repo and include your various prototypes. We look forward to seeing how you came to build your final level!

## Playtesting (Until end)
In the remaining time, swap around with other students and play each other's games. Pay careful attention to how other players move about your level - are they progressing the way you planned? Are any hidden sections or alternative routes being ignored? Does the level seem to nicely guide the player through each section with room for exploration?

Consider having your playtester use a controller.

## Next Week
Next week will be your final week on the level design task before submission. We will be spending class wrapping up our work, getting some last-minute feedback, and polishing our documentation. See you then!