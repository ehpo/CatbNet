# CatbNet

Tools for comparing and analyzing the topology of biological networks

## Getting Started
is able to compute most important network topological features, from node-based measures such as: different centralities to whole network-based measures such as: network density, diameter, for analytical and comparative purposes. 
You can use this tool either by download python source code, or its windows binary .exe file.
This tool is created using python 2.7

### Prerequisites

If you are interested in using python source code, consider installing packages:
Networkx  version 1.9.1
Numpy
Matplotlib
Pandas
Scipy
PyQt4

## Loading Data

In CatbNet there is the opportunity to laod data from .gml, .graphml, .net and .el network data formats.
In the case of loading .el (edge list) networks you should consider that:
	- Each line must demonstrate a node or an edge
	- Data must be tab seperated
	- In weighted networks, each edge line must have three values in a line
	- Nodes and Edges are seprated by #nodes and #edges keywords

```
example:

#nodes
a
b
c
#edges
a	b	1.45
a	c	2.6
```

### Considerations

In the case you want to compare network groups, you should check option 'network files are classified in groups'




### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
