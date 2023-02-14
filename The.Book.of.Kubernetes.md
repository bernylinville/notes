Containers ensure that software runs reliably no matter where it’s deployed, and Kubernetes lets you manage all of your containers from a single control plane.

The biggest advantage of a Kubernetes cluster is that it hides the work of running containers across multiple hosts behind an abstraction layer.

cloud native
At its heart, the cloud is an abstraction. We talked about abstractions in the introduction, so you know that abstractions are essential to computing, but we also need a deep understanding of our abstractions to use them properly. In the case of the cloud, the provider is abstracting away the real physical processors, memory, storage, and networking, allowing cloud users to simply declare a need for these resources and have them provisioned on demand. To have a “cloud native” application, then, we need an application that can take advantage of that abstraction. As much as possible, the application shouldn’t be tied to a specific host or a specific network layout, because we don’t want to constrain our flexibility in how application components are divided among hosts.
