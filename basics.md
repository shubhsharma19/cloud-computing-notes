## ☁ Cloud Foundations - Basics

## Definition

Cloud computing refers to the delivery of on-demand computing resources, such as servers, storage, applications, and services, over the internet. Basically, the servers that are accessed over the Internet, and the software and databases that run on those servers. These servers are located all over the world. 

In Cloud computing, massive scalable IT-related capabilities are provided as a "service" using the internet to multiple customers.

## What is Infrastructure? 🏭
Infrastructure means the physical and virtual components that support an organization's IT systems and processes. It includes the hardware, software, networks, and facilities necessary for an organization to operate and communicate.

Examples of physical infrastructure include Hardware, Networks, and Data servers.

**Software infrastructure** includes operating systems, middleware, databases, and applications.

**Virtual infrastructure** refers to the use of virtualization technologies such as VMWare or Virtual box etc. to create multiple virtual instances of operating systems or applications on a single physical machine. This can help organizations optimize their hardware utilization, improve their application deployment speed, and simplify their IT management.

## What do businesses worry about when it comes to Infrastructure? 
- Service Availability (24*7)
- Maintaining the service
- Unpredictable growth of users (from 100 to 100Million or more)
- Data center management (management is essential to ensure that the IT infrastructure is running smoothly and securely)
- Elasticity (easily scale up or down its computing resources in response to changing demand)
- Redundancy
- Infrastructure Refresh
- Security

## Reasons why cloud is better than Classical approach 
- Turns Capital Expenditure into Operational Expenditure. (CapEx is typically a one-time, up-front expenditure to purchase or secure tangible resources, OpEx is spending money on services or products over time. Renting a convention center, leasing a company vehicle, or signing up for cloud services are all examples of OpEx)
- Businesses can quickly and easily scale their computing resources up or down as needed to meet changes in demand also called Elasticity.
- Cloud providers invest heavily in the reliability and availability of their infrastructure, which means businesses can benefit from a high level of uptime and availability for their IT systems.
- higher security 

## Services provided by Cloud
- **IaaS**: Infrastructure as a Service provides users with an Infrastructure to use such as virtualized computing, hardware, servers and storage as a service on the internet. Users are responsible for configuring and managing their virtual machines and operating systems that run on the cloud infrastructure.
- **PaaS**: Platform as a Service provides sets of services and workflows that specifically target developers, who can use shared tools, processes, and APIs to accelerate the development, testing, and deployment of applications including a Runtime environment, Operating system and Middleware as well.
- **SaaS**: Software as a service (or SaaS) is a service provided by Cloud providers delivering applications over the Internet. Instead of installing and maintaining software, you simply access it via the Internet.

## Types of Cloud Deployment model
- **Public**: Open to all to store and access information on the Internet. It makes resources such as applications and storage available to the general public.
- **Private**: Internal or corporate cloud is another name for a private cloud. Organizations use it to construct and operate their own data centers, either internally or through a third party.
- **Hybrid**: Hybrid Cloud = Private cloud + Public cloud
- **Community**: To share information between an organization and a particular community, a group of various organizations can access systems and services through a community cloud.

## Scalability 
- Ability to adjust resources to meet demand. If you suddenly business experience peak traffic and your systems are overwhelmed, the ability to scale means you can add more resources to better handle the increased demand.
- The other benefit of scalability is that you aren't overpaying for services. Because the cloud is a consumption-based model, you only pay for what you use. If demand drops off, you can reduce your resources and thereby reduce your costs.

## Types of Scalability 
- **Vertical**: Scaling up and down to add more or remove CPUs or RAM to the virtual machine.
- **Horizontal**: Adding more instances of machine or it can be defined as spreading out the resources and increasing the utilization by diving the processing power into several smaller units of servers. This is a better approach when it comes to utilization of computing power.

## Services provided by Cloud 
![services](https://user-images.githubusercontent.com/69891912/221429278-439286f4-a6eb-4038-be09-2eb709682514.png)

- **IaaS**: Infrastructure as a Service the cloud provides **the hardware, network connectivity (to the internet), physical security** and also maintains all these things as well. User is responsible for everything else such as operating system, configuration, maintenance of OS, network configuration; database and storage configuration and so on. Basically you are renting the hardware in a cloud datacenter, but what you do with that hardware is up to you. There are some Scenarios where IaaS makes sense such as when you’re standing up cloud resources similar to your on-prem datacenter, and then simply moving the things running on-prem to running on the IaaS infrastructure also called lift-and-shift migration

- **PaaS:** Sits in the middle of IaaS(Infra) and SaaS(Complete deployed solution). In PaaS providers maintain what IaaS provides + **OS, middleware, development tools as well**. It is well suited to provide a complete development environment without the headache of maintaining all the development infrastructure. In other words it provides a framework that developers can build upon to develop or customize cloud-based applications.

- **SaaS:** Most complete service that includes everything that is provided by IaaS and PaaS + everything else to make this fully functional application. With SaaS, you’re essentially renting or using a fully developed application. Email, financial software, messaging applications, and connectivity software are all common examples of a SaaS implementation. You’re only responsible for the **data** that you put into the system, **the devices** that you allow to connect to the system, and the **users** that have access.
