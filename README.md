Download Link: https://assignmentchef.com/product/solved-csci-2275-assignment-9-people-in-graphville
<br>
You are the mayor of Graphville. You have a list of all the people in your town. You also know the relation between them, basically if they know each other. You need to increase the community interaction between your constituents. Now before you do that you need to know a lot of other details like if two people know each other directly or through a friend or in any other way, also how many groups are there in your town.




<strong>What your program needs to do:</strong>




<strong>Build a graph.</strong> There is a file on canvas called people.txt that contains the names of people and with them the names of people they know similar to an adjacency list. When the user starts the program, read in the file and build a graph where every person is a vertex, and there is an edge for every person they know.




For this assignment, you are building the graph and implementing functionalities given in the menu.




<strong>Use a command-line argument to handle the filename.</strong>




<strong>Display a menu.</strong> Once the graph is built, your program should display a menu with the following options:




<ol>

 <li><strong>Print list of people and their acquaintances </strong></li>

 <li><strong>Print distance between 2 people </strong></li>

 <li><strong>Print people who are ‘n’ hops away </strong></li>

 <li><strong>Quit </strong></li>

</ol>




<strong>Menu Items and their functionality:</strong>

<ol>

 <li><strong>Print list of people.</strong> If the user selects this option, the vertices and adjacent vertices should be displayed.</li>

 <li><strong>Print distance between 2 people</strong> This option takes two vertices as user inputs and prints the shortest distance between them. Use Dijkstra’s algorithm.</li>

 <li><strong>Print people who are ‘n’ hops away</strong>: Print people who at ‘n’ hop from the starting person which you will take as input. <strong>IGNORE THE WEIGHTS FOR THIS ONE.</strong> If you draw out the graph you will observe That if the starting person is Tang then Tessa, Simon and Simon will be at hops 2 and John and Timothy are at hops 3. Please note that if a vertex is reachable in 2 hops and 3 hops then you only consider that vertex at 2 hops.</li>

</ol>




<strong>Project Proposal: </strong>




Write a 1-page proposal describing the project you would like to work on for the course. You have the freedom to use any language (Preferably C++, C, Java, Python, JavaScript) and could choose whatever topic you want.




Just some broad categories you can think about projects are:

<ol>

 <li>Combining multiple data structure with a use case</li>

 <li>Implementing a data structure not taught in class and is something difficult</li>

 <li>Benchmarking performance of various data structures for various operations</li>

 <li>Anything under the sun and the stars which can use data structures</li>

</ol>





