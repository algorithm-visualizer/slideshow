Learning algorithms from text and static images is quite boring.

For that, there have been many great websites that view animations of various algorithms.

However, for us being coders, nothing can be more comprehensible than visualizing the actual working code.

So here we introduce Algorithm Visualizer.

Algorithm Visualizer is an interactive online platform that visualizes algorithms from code.

It offers visualization tools in various languages including JavaScript, Java, and C++.

The UI of Algorithm Visualizer consists of 4 sections: toolbar, sidebar, viewer, and editor.

The toolbar contains a user's profile and buttons for controlling visualization.

A user can also save algorithms to GitHub Gist or share them on Facebook here.

The sidebar shows a set of public algorithms, which others have contributed, in addition to a user's scratch papers.

The viewer is where the actual visualization happens.

It also views descriptions of algorithms.

Lastly, the editor lets a user write down their own algorithms to be visualized.

Algorithm Visualizer is an open source project on GitHub.

The project is composed of 3 repositories named algorithms, tracers, and algorithm-visualizer.

"algorithms" repository contains public algorithms shown on the sidebar.

"tracers" repository contains visualization libraries written in each supported language.

"algorithm-visualizer" repository contains the front-end written in React.js and the back-end written in Node.js.

When the back-end compiles and runs code, the visualization library emits a change log.

The back-end then passes the change log on to the front-end, and the front-end interprets and renders it step by step

Visit algorithm-visualizer.org and be a part of our community.
