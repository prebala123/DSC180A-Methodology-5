# DSC180A-Methodology-5

Name: Pranav Rebala <br>
Email: prebala@ucsd.edu <br>

Section: Graph ML for Chip Profiling <br>
Section Number: B12 <br>
Mentor: Lindsey Kostas

<b> 1. What is the most interesting topic covered in your domain this quarter? </b>

The most interesting topic we learned about is what features need to be balanced in order to make the best possible chip. For example we want to put all the cells as close as possible to decrease the wire length to make the chip as fast as possible. However we also can't put cells too close together because congestion means that area is using too much power, and could damage the board. It is very interesting how in industry companies have to optimize for multiple things at once, and that tradeoffs have to be made to have a functioning chip. I also liked learning about what happens when the chip is not optimized for congestion. For example the new Intel chips burned themselves out because they put the cells too close together. This example really shows the importance of this field and why it is so important to get the chip design right so we can catch errors before making physical boards.

<b> 2. Describe a potential investigation you would like to pursue for your Quarter 2 Project. </b>

A potential project would be coming up with better ways to partition graphs for analysis. Since chips have so many cells, it is impossible to fit everything in memory at once for analysis since it would take too many resources. People have already come up with some ways to partition the graph so they can load one subgraph at a time, and then run the congestion modeling algorithms on each subgraph separately. This has some issues when it comes to the interactions between subgraphs, and it is hard to know if you are cutting off edges that are important. Since chip graphs have a lot of important long range connections since some cells affect cells very far away, it becomes hard to choose subgraphs that keep all of the important properties of the whole graph. An interesting project is looking more into ways to partition the graph using some other methods like virtual nodes for example. Introducing new nodes by aggregating other nodes could help lower the graph size and make partitions easier. The partitioning problem seems like it would be very helpful for the field and would make for a good project topic.

<b> 3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project? </b>

A potential change I might make is to spend more time on exploratory analysis for the data. Our data contains many different chips of all different sizes each one has many different graph properties to analyze like distribution of node degrees for example. I have spent most of the time looking at the smaller graphs to try to understand the format of the data and what the properties of the chip are. I haven't analyzed the more complex graphs yet since there is still so much more to explore with the first chips. I know our quarter is pretty short but I would still like to spend more time on exploration to know the data better before doing the modeling.

<b> 4. What other techniques would you be interested in using in your project? </b>

A technique I would be interested in is using the NetworkX graph drawing feature to visualize the graphs better. I think learning how to visualize the chips in an intuitive way would be very useful for understanding the data and also explaining it to someone else who doesn't understand the domain. It would also be good to have better pictures of the chips to put on our website at the end since it would better explain our work. Since we are already using NetworkX for some of the analysis, it would be good to learn the graph plotting features as well.
