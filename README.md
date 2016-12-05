Flow Network
==============

React Component for an animated Flow Network Directed Graph using WebGL Particles

I haven't published this experimental component yet, but see [here](http://joewood.github.io) for a demo.  This component was 
created while looking to visualize activity across large scale workflow systems. It was repurposed to help visualize network data flow 
across Apache Kafka and RabbitMQ message bus systems.

Scope
-----

React Component that visualizes data flow (or activity) through a Graph:

* Forced Based Layout of Graph data structure
* WebGL Particle based animation of data flow, variable flow
* Layout hints, such as starting position, pinned nodes
* Relative node locking of position (lock horizontal or vertical position relative to another node) - great for alignment
* Labels for nodes
* Dynamic data structure and data flow rate

Still To Do
-----------

* Publish component
* Add a better editor for the demo page
* Custom Node renderer, including support for queue sizes
* More paramaters for data flow, particle colors, variation
* Drag support to edit hints for the demo page 
* Pan and Zoom
* React-Native support using OpenGL/DirectX bindings

