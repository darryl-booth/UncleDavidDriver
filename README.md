# UncleDavidDriver
Mini game driving truck/fifth wheel through a winding road.

Platform: Single-file web apps: HTML + HTMX + Alpine + sql.js; host on GitHub Pages/Netlify.

Game screen appears in black with an orange frame.
Game generates a winding road with smooth turns to the left and right beginning at a Home icon and ending at a campesite icon.

At the beginning of the path, a simple icon from above appers to be truck pulling a fifthwheel with the trailer following the truck at the toe location.

Along the bottom middle of the screen is the top 1/2 of a steering wheel with texture such that is is evident when the wheel is turned to the left or the right.

The controls are a simple touch-screen (on mobile) or touchpad (on laptop) where the user makes circle motions to turn the steering wheel. Make a circle clockwise, the steering wheel and the truck turns to the right along the road. Make a cicle counter-clockwise, the steering goes to the left.

The icon of the truck and its trailer advances along the road slowly at first. Each completed level, advancing the speed by 10%, making the task more difficult.

As long as the truck stays on the road, it continues to the campsite (finish). If the truck veers from the road, then the game is over and the final level and score are displayed. Also make a snarky comment about the players bad driving.

If the truck advances to the finish, then a congratulatory meessage is displayed and a new level is drawn and started.