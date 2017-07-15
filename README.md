# DDgenerator

This project has 2 parts, the depth-first recursive directory mapper in python, and the visualization in d3.js    
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <code>dfs.py</code> Constructs the JSON file associated with the dendrogram  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <code>index.js</code> Constructs the visualization on index.html  

# Usage
1. Execute: <code>python dfs.py /path/to/directory</code> to generate output in  <code>\<dirpath\>/TREE_OUTPUT/\<dirname\>.json</code>
2. Change line 1 of index.js to the outputted data path
3. Start a localhost and view index.html

# Key Features
Visualizing any directory(currently in a simple manner), on Windows or Linux. With the git option enabled, clicking a file within the tree renders all commit data across all branches for the file. 


