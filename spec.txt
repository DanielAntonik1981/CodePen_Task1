1. The idea is that I hire several contractors to try this project out - so any changes to the XML need to be propagated to all contractors in order for their work to be compatible.
 
If I get 5 animations I should be able to run all 5 on identically-formatted XML (in fact that's what the next/prev buttons & URL are for!). 

Having said that: if you find the XML format has problems then I don't have a problem updating it - I put it together quickly and don't pretend it's perfect.

Let's say, the sooner you make changes to it the better, because I'll just update the 'spec' before other contractors start.

2. The idea is that the XML I provide is generic and describes the images & text for the group... and that animations (like the one you're about to create) make creative use of that information and present it in an interesting way.

 Let's call that XML file the "Team" XML file. You will need to save animation / texture / font / etc information somewhere and an XML file would be perfect. I would prefer to have the Team XML file remain pristine, so that it can be referenced by other animations.

 So, it makes sense to have a second XML file, call it the "Presentation" XML, which is read by your page to determine how your animation will present the images/text described in the Team XML.

 Your animation will be completely different from the next one, so you're free to write whatever XML you like into your Presentation XML file - it won't conflict with others.

3. It's very important that the animation plays on mobile and desktop. Flash ain't gonna cut it.

 I should be able to demo the animation on iOS, Android, PC or Mac. To be precise I hope that users working with: a modern iPod/iPad/iPhone, a modern android phone/tablet, a Mac running Safari/Chrome or a PC running Firefox/Edge/IE/Chrome.

 I don't expect you to test all these platforms but I will be encountering people on any of them and would hope that the animation is smooth & correct on all of them.

 BTW if you prefer some other animation library like pixi or threejs or whatever, that's fine with me.

 I tried out pixi the other day and was disappointed when my animation looked awesome on a PC but unbearably sluggish on my Nexus 5. So I'm open to suggestions.

4. The resolution of the images is not important - e.g. if you choose to downsize them then that's absolutely fine so long as they look nice.

 And you can assume that the team member images all have the same dimensions, and that the cropping was done so that they can be laid out easily.

 I provided them at full res in the expectation that you would preprocess them to perform well in playback situations. Do whatever you like to them.

5. Team images can be laid out in all sorts of ways... google "team composite" and look at the image results for inspiration. PILES of layout ideas.

 The players don't have to be evenly spaced, they can be at angles, you can feature one player more than the others... whatever you like.

6. Don't feel that you need to present the team as a fixed group. Feel welcome to play with any style you like - carousel, filmstrip, deck of cards... whatever. That's the point of doing this project the way I am (5 contractors in parallel) - I'm looking for unique ideas / visual flair in addition to code. So just put yourself in the role of a parent of one of the kids on the team and ask yourself: "how would I like to see my kid's team presented?". 

Have fun!