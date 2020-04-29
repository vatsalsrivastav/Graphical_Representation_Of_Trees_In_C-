# Graphical_Representation_Of_Trees_In_C++
Graphical representation of various tree data structures and their respective various operations like data insertion, deletion and other operations using graphics.h library of C++.

# Description
When we first start learning to code, it's common to learn arrays as the 'main data structure'. Eventually, we learn about hash tables too. If you are pursuing a Computer Science degree, you have a Data Structures class and you also learn about Linked Lists, Queues, and Stacks. Those data structures are all called 'linear' data structures because they all have a logical start and a logical end. When we start learning trees and graphs, it gets really confusing. We don't store data in a linear way. Both data structures have a specific way to store data. This post is an attempt to we better understand the Tree Data Structure and clarify any doubts about it.
Trees are well known as a non-linear Data Structure. It doesn't store data in a linear way. It organizes data in a hierarchical way. What does hierarchical way mean? Imagine a family tree with all generation relationship: grandparents, parents, children, siblings, etc. We commonly organize it in a hierarchical way.

# Configuring Codeblocks
1) Copy and paste **graphics.h** and **winbgim.h** files into the include folder of compiler directory. (If you have Code::Blocks installed in C drive of your computer, go through: Disk C >> Program Files >> CodeBlocks >> MinGW >> include. Paste these two files there).
2) Copy and paste **libbgi.a** to the lib folder of compiler directory.
3) Open Code::Blocks. Go to Settings >> Compiler >> Linker settings.
4) In that window, click the Add button under “Link libraries”. Select the libbgi.a file copied to the lib folder in step 2.
5) In right part (ie. other linker options) paste commands `-lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32`.

For any other platform, you can easily find a number of videos and tutorials to install graphics.h library on your own machine on the internet.
