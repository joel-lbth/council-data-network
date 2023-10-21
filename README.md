# council-data-network
> a reference guide to council datasets by function, and the relationships between them - based on the [lginform standards lists](https://standards.esd.org.uk) connecting council functions and showing each function's services as leaf nodes (datasets)

this project's `docs` dir is published as a public [logseq graph](https://joel-lbth.github.io/council-data-network/#/graph), which is an interlinked series of files

there is also python code to convert the lginform standards into:
* a list logseq pages that link to each other making up a knowledge graph (files in the `pages` dir)
* a networkX graph and pyvis render of the edgelist, published in the `docs` dir as [data-network](https://joel-lbth.github.io/council-data-network/data-network.html)
  * there is also a function to create subgraphs and publish those, e.g.
    * [planning](https://joel-lbth.github.io/council-data-network/data-network-planning.html)
    * [building](https://joel-lbth.github.io/council-data-network/data-network-building.html)
    * [housing](https://joel-lbth.github.io/council-data-network/data-network-housing.html)
    * [waste](https://joel-lbth.github.io/council-data-network/data-network-waste.html)
    * [waste-management](https://joel-lbth.github.io/council-data-network/data-network-waste-management.html)