# Containerization vs Virtualization

### Containerization: 
Containerization involves encapsulating an application in a container with its own operating environment. Containers use the same host operating system (OS) repeatedly. 

### Virtualization:
A virtual machine is a copy of a complete server basically it has its own OS which means the replication of binaries, drivers, or libraries between different VMs running on same server.

### VIRTUALIZATION

Advantages

1.	Virtualization allows you to run an entire guest operating system in a virtual machine (VM) on a host operating system giving you the ability to maximize your hardware.

2.	If you have enough resources on your host operating system (OS), you can operate multiple VMs each running a full OS on a single piece of hardware.

3.	Virtualization is all about efficiency, effectively taking a physical machine and converting it into a piece of software, allowing you to manage your infrastructure more effectively.

4.	Virtualization simplifies maintenance and recovery and reduces your technology infrastructure cost of ownership significantly.

Disadvantages

1.	High cost of implementation. Hardware and software are required at some point and that means devices must either be developed, manufactured, or purchased for implementation.

2.	Not every application or server is going to work within an environment of virtualization. 

3.	It creates a scalability issue because many entities share the same resources, growth creates lag within a virtualization network.

4.	With virtualization, you lose full control because several links must work together to perform the same task. 

5.	It costs users time over the long run when compared to local systems because there are extra steps that must be followed to generate the desired result.

### CONTAINERIZATION

Advantages:

1.	Containerization gives you the ability to package components and run them on a single guest OS. This architecture takes the hardware maximization efficiency introduced by virtualization to a higher level.

2.	By leveraging the power of containers, you can run many more apps on a single host as you do not have the additional overhead of multiple operating systems and their dependencies.

3.	Because each container is a standalone application that houses the app, its relevant libraries, and sources, containerized apps offer simpler and easier portability.

4.	Increased development velocity as a contained environment possesses every dependency needed by the application.

Disadvantages

1.	Containers utilize process-level isolation, if a user or application within it has elevated privileges, a malicious actor can leverage this to compromise the host system.

2.	If any vulnerability exists in one of the dependencies you use to create your container, it places your app at risk.

3.	The layered architecture of most container solutions leads to greater complexity creating a high maintenance overhead

4.	As an abstraction layer exists between them and the underlying infrastructure, high-performance apps may struggle when containerized.

5.	When containers shutdown, the process erases the data inside it. Unless you put a solution in place to save your data, you will lose any app-related information.

6.	Graphical applications also do not work well in containers because the engines do not include a standard GUI
