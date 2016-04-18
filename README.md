# Scientific Workflow Diagrams

## Outline
Elixir workflows could help present easy to understand navigations of scientific workflows capable of integrating training, tools, resources, datasets and much more.

There are many existing workflows people have used to visualize and therefore simplify the complicated mesh of processes needed to perform life science experiments. Some [examples](/examples.md) of which can be found here.

This working group attempts to unify various elixir development teams to create a workflow editor that can allow scientists to easily create simple diagrams for complicated workflows and interconnect the many resources elixir collects. It will be based off existing work

## Existing work
An example of an early edition that direly needs a re-implementation can be found on [the old Training Portal; TeSS](http://tess-old.elixir-uk.org) 

https://github.com/ElixirUK/ckanext-tess/tree/master/ckanext/tess/public
(See all files of cytoscape\*.js and workflow\* pattern)

We're using the Cytoscape JS package (unless someone has any better ideas).

sample_flowcharts_for_biotools.zip includes examples of flowcharts in graphviz, used by Jacques van-Helden for training.  Would be nice to have something like this for navigation in bio.tools (or at least more inspiration).

## Plan of Work 

a) Bring cytoscape version up to current stable version

b) Separate anything that needs to be made customizable by the sites that will use the workflows editor (the pop up workflow modal)

c) Improve the style of the editor
