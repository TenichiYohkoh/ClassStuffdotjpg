**The Final Jelly**

For this project/piece I wanted to use just about every bit of everything I learned in programming up to this point while doing my absolute best to be a way more efficient and avoid spaghetti code as much as I possibly can. At the same time the goal of this project is very similar to the goal of my previous project flower. To create a passive “game” that has an active element that the person experiencing the piece may elect to use or not. 
With that I would say about 90% of the code I used in this project aside from the method to procedurally generate the fish came and a few other things from previous projects I’ve worked on or have been involved with. IE movement, array splice etc. The First Challenge STAYING ORGANIZED!! And being efficient. (At Least i think I was efficient?)![chrome_2021-06-09_14-34-04.png]({{site.baseurl}}/chrome_2021-06-09_14-34-04.png)![chrome_2021-06-09_14-35-44.png]({{site.baseurl}}/chrome_2021-06-09_14-35-44.png)


The method i used to play the youtube video sound for background track may however have been rather inefficient its basically opening an embedded video with 0 size to play the video once you hit spacebar. Kinda just wanted to have the tech for later honestly tech for this came from: [https://editor.p5js.org/Zipexpo/sketches/Ue0gG-r6l](Source) one Zipexo thanks to them for that!

The next challenge was the procedural generation. LORT : [https://www.youtube.com/watch?v=HIfYoVfsu7U](Yipes Scream) me reacting to … the task of this. Just yipes screams… so put simply i used random and constraints and then created a kind of hit box which would delete the fish if it went below "window height" (that efficiency) and add a fish randomly generates above, again based on window height alongside movement up, as well as determine its size and colour. also to keep it efficient there's a fairly hard limit on how many objects can be on screen at once. Additionally the probability of seeing a fish or seaweed or a whale changes based on the jelly fish’s  position within the sea. Balls of light become almost non existent as you go up further while whales start appearing. ![chrome_2021-06-09_17-05-34.png]({{site.baseurl}}/chrome_2021-06-09_17-05-34.png)

After that it was mostly all gravy, the most of the tech on the charged movement came from professor Mckay in physical computing... he helped me make a golf ball being hit into a cup game....
![chrome_2021-06-09_17-34-54.png]({{site.baseurl}}/chrome_2021-06-09_17-34-54.png)


The tech for states came from the cat example you gave in class and the questions I asked about states basically being true false statements but simpler. ![chrome_2021-06-09_16-52-55.png]({{site.baseurl}}/chrome_2021-06-09_16-52-55.png)


My method to get the background to change was by using "lerp" function which lets the color migrate from a start color to an end color which was then set to change based on position of player within the sketch. I realized I had used lerp for my flower game to get a gradatiion that changed based on time of day, in this case the gradation changes based on height. ![chrome_2021-06-09_23-17-32.png]({{site.baseurl}}/chrome_2021-06-09_23-17-32.png)


Something i may consider adding is to have an additional state where the jelly fish slowly travels upwards without pressing anything.
![chrome_2021-06-09_23-18-48.png]({{site.baseurl}}/chrome_2021-06-09_23-18-48.png)
