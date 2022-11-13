This is a phenomenal library. I love the fact that it has zero dependencies. Some of the other similar ones rely on React etc.

I think the _dashboard_ is becoming an extremely common and versatile application paradigm which has led to a multitude of libraries that each provide _some_ of the toolset needed to make them. In fact, I believe that all modern data science IDEs are essentially already dashboards or, in the case of VS Code, a set of plugins to turn a code editor into a dashboard.

Consider the following images of RStudio, Spyder, Matlab, and VS Code:


The basis of these applications are a grid of _panels_ which may further contain sub-panels or tabs. Generally, these panels have header bars and can be placed within the application window with some amount of freedom. Likewise for the sub-panels and tabs. In most cases these can be minimized, maximized, closed, dragged and dropped, and even popped-out and re-docked.

These panels can contain many different widget types such as editors, data tables, file explorers, command terminals, plots, help documentation, and others. There are great widget libraries that can be used for these. But for the basic dashboard/IDE functionality, I haven't found a single library with all the needed features/properties.

It's not as of one can take the pop-out+dock function from one panel or grid library and use it in a different one.

Here is a grid I put together of various libraries and which of the key properties they have or not.

