# NFVPlacement

The workload is used for experiments with NFV placement.

In the experiment we create 10 instances. Each instance is used to evaluate the performance of the proposed solution.

In each instance, there are some workflow description, a substrate network, a performance model and a resource capability description.

Each workflow is described with a file of 4 numbers. The first number is a ID for each workflow. The second number describes the number of vertices in the workflow. The third number is the Fan-in and the fourth number is the Fan-out. 

The description substrate network is drawn from the Topology Zoo.

The performance model is used to model how will a network function performs on different network nodes.

The resource capability describes the limits of the resources of each node in the substrate network.
