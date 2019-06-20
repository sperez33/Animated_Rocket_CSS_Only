# RSI_Challenge_StephPerez
A challenge given to me during my internship with RSI
June 19.2019 - 9:48a - uploaded test file to GitHub

June 19.2019 - 10.25a - Real file uploaded. Icons from FontAwesome were inserted via using classes and 
linking to the external CSS page to bring the icons into the page. At this stage, they're showing up 
like black icons.

June 19.2019 - 10.37a - Worked on adding some style to the page. Made a grey background and gave the body 
a foundation for the rest of the page. I also went ahead and centered the icons with the class .scene to 
ensure their location.

June 19.2019 - 10:53a - added lines 12-19 in RocketFuel.css to create a simple circle in the center of the 
screen where the icons will eventually show themselves. width, height, background, border, border-radius and 
overflow where all added under .scene {} 

June 19.2019 - 11:09a - in the RocketFuel.css file I added the block that controls .scene:before{} section 
which causes half the circle to become shaded and darker than the other half.

June 19.2019 - 11:30a - Adding in .fa-rocket {} to get the rocket at the center of the circle, changing its 
angle, color and size. for the font size, it's important to add !important after the size. Any lines that 
say animation will be used later when the animation code is written, for now they're just place holders so 
I don't forget.

June 20.2019 - 9:20a - Added a CSS block for .cloud and .cloud1-3 to ensure they show up within the blue circle. 
In addition, I added the first @keyframe to make the rocket actually move up and using translate and rotate within
transform withn a percentage.

June 20.2019 - 9:29a - added the @keyframes for animateCloud using translateY within transform within a percentage.
I also added a z-index to .cloud2 to give it depth and make it appear as if the rocket is flying in front of it as 
it "passes by".