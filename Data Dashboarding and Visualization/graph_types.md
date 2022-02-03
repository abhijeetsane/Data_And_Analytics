# Data Dashboarding and Visualization

## Types of Graphs

- **D3** [https://d3js.org/]
  - **Animation**
    - **Animated Treemap**
    - Change in set of data points over a period of time represented using square tree map.
    - It constitutes of stable layout with changing node values.

    - **Temporal force-directed graph**
    - Helps to visualize a spherical temporal network which changes over time wherein each node and link has a start and end specifying its existence.
    - Used to create Social network visualization using a force-directed graph drawing algorithm.
  
    - **Connected Scatterplot**
    - Similar to a line plot which shows a trend in data over intervals of time except that individual observation are highlighted. This makes it easier to visualize where the breaks in the curve are present.
    - Depicts the type of relationship between two quantitative variables.
  
    - **The wealth and health of nations**
    - Represents the evolution of data points over a period of time using a chart with bubble animation.
    - Uses bisection and linear interpolation to fill in missing data points where the network is sparse.
  
    - **Scatterplot Tour**
    - Scatterplot Tour is used to observe relationships between variables of a set of data with an animated tour using zoom transitions. The tour zooms in on each cluster’s bounding box in succession before zooming back out to the overview.
    - To improve rendering performance, the circles are drawn as zero-length strokes with round caps.

    - **Bar chart Race**
    - Bar Chart Race is a great and highly visual way to display data changing over time in the form of an animated bar chart. It's a very comprehensible representation of time-based changes in data.
    - This animation iterates over each of the keyframes, delegating updates to each of the chart components and awaiting the transition’s end. Linear easing enures the animation runs at constant speed.

    - **Stacked-to-Grouped Bars**
    - Grouped and Stacked barplot display a numeric value for several entities, organized in groups and subgroups. It also adds a sequenced transition for a normalized stacked bar chart, which shows the values for each column as a percentage rather than absolute numbers.
    - Moreover this animation can preserve object constancy, allowing the reader to follow the data across views.

    - **Streamgraph transitions**
    - A streamgraph is a type of stacked area chart. It represents the evolution of a numerical variable for several groups. Areas are usually displayed around a central axis, and edges are rounded to give a flowing shape.
    - It creates a transition effect while plotting with different modes like Expanding, Wiggle and Silhouette.

    - **Smooth Zooming**
    - This type demonstrates to implement smooth pan-and-zoom transitions between two views. It also allows freeform zooming.
    - Allows to perform operations such as transform, translate, scale, filter and many more.

    - **Zoom to bounding box**
    - This type demonstrates how to compute a suitable translate and scale to zoom to the bounding box of a particular feature.
    - It uses zoom transitions to smoothly interpolate between different views and also allows you to freely pan and zoom.

    - **Orthographic to Equirectangular**
    - Represents how to interpolate smoothly between orthographic and equirectangular projections by blending their raw projection functions.
    - Plots a three dimensional graph like sphere to a two dimensional plane graph.
  
    - **World Tour**
    - This animation interpolate a path along great arcs, and spherical linear interpolation to rotate the orthographic projection.
    - It bounces from one specified two-element array point to another using intermediate values that interpolate along the great arc that passes between these points.

    - **Walmart's growth**
    - Shows the expansion of particular entity over a period of time with a series of points by populating the graph.
  
    - **Hierarchical Bar Chart**
    - The bar chart visualizes hierarchical data wherein each bar represents a package in a software hierarchy, whose length encodes the number of lines of code in package's source files. Clicking on a bar dives into that specific package, while clicking on the background will bubble back up to the parent.

    - **Zoomable Treemap**
    - Treemaps recursively partition space into rectangles according to each node’s associated value. Also, allows several treemap tiling methods.
    - This type of animation supports zooming, i.e. you can click any cell to zoom in, or the top to zoom out.  

    - **Zoomable Circle Packing**
    - Circular packing or circular treemap allows to visualize a hierarchic organization where each node of the tree is represented as a circle and its sub-nodes are represented as circles inside of it.
    - It's not as space-efficient as a Treemap, as there's a lot of empty space within the circles. Despite this, Circle Packing actually reveals hierarchal structure better than a Treemap.

    - **Collapsible Tree**
    - The tree layout produces tidy node-link diagrams of trees wherein a tree layout can be used to organize software classes in a package hierarchy.
    - While using this animation, by clicking on the parent nodes you can expand or collapse the tree structure.

    - **Zoomable Icicle**
    - The Icicle chart is a graphical representation of the stack trace responsible for creating a selected object set. It is commonly used to visualize software packages and file systems.
    - This animation supports a node to zoom in, or the left column to zoom out.
  
    - **Zoomable Sunburst**
    - The Sunburst Diagram is used to visualize hierarchy through a series of rings, that are sliced for each category node. Each ring corresponds to a level in the hierarchy, with the central circle representing the root node and the hierarchy moving outwards from it.
    - Rings are sliced up and divided based on their hierarchical relationship to the parent slice. The angle of each slice is either divided equally under its parent node or can be made proportional to a value.

    - **Sortable bar chart**
    - This variation of a simple bar chart adds sorting with staggered delay and translucency to improve readability during the transition.
    - For object constancy, bars are keyed by name, making it possible to follow changes in value and order across transitions.

    - **Icelandic Population by Age**
  