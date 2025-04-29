# cop4530-project-3-solved
**TO GET THIS SOLUTION VISIT:** [COP4530 Project 3 Solved](https://www.ankitcodinghub.com/product/cop4530-project-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110107&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP4530  Project 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1 Overview

In this project, you will implement topological sorting in a directed acyclic graph. In addition, your implementation will:

represent the graph as an adjacency matrix

always choose the vertex with the lowest ID when given a choice (e.g., when iterating through the neighbors of a vertex and when selecting a vertex to start) throw an exception if it encounters a cycle

I have provided you with a driver and a preliminary header file for the project. The provided header is just to get you started–you are allowed to change it however you like; however, your solution must be compatible with the provided driver file. You are strongly encouraged to add more data members and member functions to the class defined in the header.

2 Submitted code

You should submit a zip archive containing two files: digraph.h and digraph.cpp, which define and implement a DigraphMatrix class. This class must have a constructor that accepts a string (or const string&amp;), and it must have a function topologicalSort that accepts no parameters and returns a vector of integers. The constructor must be able to construct the graph based on the name of an input file to read. (See section 3 for a description of the graph file format.) Moreover, it must represent the corresponding graph using an adjacency matrix.

The topologicalSort function should return the vertices of the vertices of the graph, in topologically sorted order if the directed graph does not contain a cycle. If the directed graph does contain a cycle, though, topologicalSort should throw an exception. The type of exception it throws (and its what function) are not important, but it must be an std::exception object or one that inherits from std::exception.

3 Input file

The input graph is described in edge list format. The first line of the file has the number of vertices and edges of the graph, separated by a space (n and m, respectively).

The following m lines have two nonnegative integers each. These integers, u and v, will be in the range 0 to n− 1, and they represent the endpoints of an edge in the graph. Specifically, they represent an edge from u to v.

4 Example 1

Consider running the topological sorting algorithm described in class on the graph below:

We start at the unexplored vertex with the lowest ID, vertex 0. We mark 0 discovered and consider its undiscovered (outgoing) neighbors. Its only neighbor is 1, so we recurse on 1 and mark it as discovered. The undiscovered neighbors of 1 are 2, 4, and 7. Since we should consider neighbors in sorted orde, we recurse on 2 and mark it discovered. The undiscovered neighbors of 2 are 5 and 7, so we recurse on 5 and mark it discovered. The only neighbor of 5 is 7, so we recurse on 7 and mark it discovered.

Vertex 7 has no outgoing neighbors, so we mark it explored and add it to our output array (7). When we return to 5, it has no other neighbors, so we mark it explored and add it to the array (7, 5). Returning to 2, we see that 7 has already been explored, so we mark 2 explored and add it to the array (7, 5, 2). Returning to 1, the next neighbor of 1 is 4, which we have not visited yet, so we recurse on 4 and mark it discovered. The only undiscovered neighbor of 4 is 3, so we recurse on 3 and mark it discovered. The neighbors of 3 are 2 and 7, both of which are explored, so we mark 3 as explored and add it to the array (7, 5, 2, 3). Returning back to 4, we’ve explored both of its neighbors, so we mark 4 explored and add it to the array (7, 5, 2, 3, 4). When we return to 1, we see that the last neighbor is 7, which is explored, so we mark 1 explored and add it to the array (7, 5, 2, 3, 4, 1). We return to 0, but its only neighbor was 1, so we mark it explored and add to the array (7, 5, 2, 3, 4, 1, 0).

5 Example 2

Consider running the topological sorting algorithm described in class on the graph below:

We start with vertex 0 and mark it discovered. The only neighbor of 0 is 1, so we recurse on 1 and mark it discovered. The neighbors of 1 are 4 and 7, so we recurse on 4 and mark it discovered. Vertex 4 has no outgoing neighbors, so we mark it explored, add it to the list (4), and return to 1. Vertex 1 continues to its neighbor 7, which we mark as discovered. Vertex 7 has no outgoing neighbors, so we mark it explored and add it to the list (4, 7). When we return to 1, we have explored all outgoing neighbors, so we mark 1 explored and add it to the list (4, 7, 1). We then return to 0, which has no other neighbors, so we mark 0 explored and add it to the list (4, 7, 1, 0). The next unexplored vertex is 2, so we start there and mark it discovered. Vertex 2 has no neighbors, so we mark it explored and add it to the list (4, 7, 1, 0, 2). The next unexplored vertex is 3, so we start there and mark it discovered. The only undiscovered neighbor of 3 is 6, so we recurse on 6 and discover it. Vertex 6 has no undiscovered neighbors, so we explore it, return, and explore 3 (4, 7, 1, 0, 2, 6, 3). Since we have not yet discovered vertex 5, we explore it, and as 4 has already been explored, we mark 5 explored and add it to the list (4, 7, 1, 0, 2, 6, 3, 5). Reversing this list yield the final answer (5, 3, 6, 2, 0, 1, 7, 4).

6 Example 3

We will trace the topological sorting algorithm on the graph below:

We start at 0 and mark it discovered. The only neighbor of 0 is 1, so we mark it discovered. Vertex 1 has no outgoing neighbors, so we mark it explored, add it to the list (1), and return to 0. Since 0 has no other neighbors, we mark it explored and add it to the list (1, 0). We then start again at 2. After marking 2 as discovered, we see that its only neighbor, 1, has been marked explored, so we mark 2 explored and add it to the list (1, 0, 2). We continue on to vertex 3. We mark 3 as discovered, and since it has no neighbors, we mark it explored and add it to the list (1, 0, 2, 3). When we continue to 4, we mark it as discovered and continue on to 5. We mark vertex 5 discovered and continue to vertex 6, which we mark as discovered and continue to vertex 7. At vertex 7, we see that vertex 5 is a neighbor, which creates a cycle (5, 6, 7, 5). At this point, your code should throw an exception.

7 Grading

The development environment used in class is VS Code (https://code.visualstudio.com/ download). This IDE includes useful features like syntax highlighting and an integrated terminal window that you can use to invoke a compiler.

Windows users can download MinGW (https://sourceforge.net/projects/mingw-w64) to use g++, though you will need to add the MinGW bin directory to the Windows path in order for the terminal to recognize the command g++ (or gdb or any of the other tools provided by MinGW).

8 Important note
