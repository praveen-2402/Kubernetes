---------------------------
What is Kubernetes ? 
----------------------------
Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation. It has a large, rapidly growing ecosystem. Kubernetes services, support, and tools are widely available.
The name Kubernetes originates from Greek, meaning helmsman or pilot. Google open-sourced the Kubernetes project in 2014. Kubernetes combines over 15 years of Google's experience running production workloads at scale with best-of-breed ideas and practices from the community
ORIGIN

------------------------------
Container deployment era: 
-------------------------------
Containers are similar to VMs, but they have relaxed isolation properties to share the Operating System (OS) among the applications. Therefore, containers are considered lightweight. Similar to a VM, a container has its own filesystem, CPU, memory, process space, and more. As they are decoupled from the underlying infrastructure, they are portable across clouds and OS distributions.
Containers have become popular because they provide extra benefits, such as:
•	Agile application creation and deployment: increased ease and efficiency of container image creation compared to VM image use.
•	Continuous development, integration, and deployment: provides for reliable and frequent container image build and deployment with quick and easy rollbacks (due to image immutability).
•	Dev and Ops separation of concerns: create application container images at build/release time rather than deployment time, thereby decoupling applications from infrastructure.
•	Observability not only surfaces OS-level information and metrics, but also application health and other signals.
•	Environmental consistency across development, testing, and production: Runs the same on a laptop as it does in the cloud.
•	Cloud and OS distribution portability: Runs on Ubuntu, RHEL, CoreOS, on-premises, on major public clouds, and anywhere else.
•	Application-centric management: Raises the level of abstraction from running an OS on virtual hardware to running an application on an OS using logical resources.
•	Loosely coupled, distributed, elastic, liberated micro-services: applications are broken into smaller, independent pieces and can be deployed and managed dynamically – not a monolithic stack running on one big single-purpose machine.
•	Resource isolation: predictable application performance.
•	Resource utilization: high efficiency and density.

-----------------------------
Additional points discussed
------------------------------

* why you need Kubernetes and what it can do
* what Kubernetes provides you
* Kubernetes Components
* PODS
* what is a replica and why do we need a replication controller. & ReplicaSet
* Deployments
* NAMESPACES
