# Day 5 - What the cloud is

## Glossary
- **Server**: a computer that provides services to other computers
- **Data center**: a physical location where servers are placed, maintained, and operated
- **The cloud**: a global network of remote servers housed in data centers that store data, run software, and deliver computing services over the internet
- **On-premises**: IT Infrastructure that is setup and maintained on-site within a company's physical building
- **Virtual machine**: a simulated separate computer within a server
- **Hypervisor**: a program that slices computers resources and memory into smaller virtual machines
- **Instance**: a specific rented virtual machine
- **Region**: geographical region of where the server is located
- **Availability zone**: one or more separate data centers inside a region, each with its own power and network connections. A region has several, so a system spread across two keeps running if one fails
- **Latency**: the delay experienced for data to travel from one place to another
- **IaaS**: Infrastructure-as-a-service. Cloud provider provides virtual machines, plus the hardware, hypervisor and network underneath them. The client manages the operating system and everything on top of it
- **PaaS**: Platform-as-a-service. Cloud provider provides and manages the hardware, the operating system and a ready-made platform such as a database. The client only brings their own application and data
- **SaaS**: Software-as-a-service. Cloud provider provides everything including the software that the client needs
- **Shared responsibility**: Both cloud provider and the client have security responsibilities. Cloud providers are responsible for the buildings, the hardware and the hypervisor, while the client is responsible for what they put on top: their settings, their data and who is allowed access
- **Compute**: the processors and memory that run programs (in AWS, EC2)
- **Storage**: services that keep files and data (in AWS, S3)
- **Identity**: who or what is making a request, a person or a program, and the permissions that decide what they are allowed to do (in AWS, IAM)
- **Pay as you go**: no upfront purchase. Billing is metered by the hour or second, for everything that is switched on or stored, whether or not it is doing useful work
- **Infrastructure as code**: describing the servers, networks and permissions you want in plain text files, and letting a tool build exactly that. The files can be reviewed, kept in version control, and run again to build an identical copy (the main tool is Terraform)

## What I measured
- Jakarta: 3 ms
- Singapore: 165 ms
- Virginia: 253 ms
- Smaller server, per month: $ 9.636
- A computer like mine, per month: $ 655.25

## Jobs
- My way in: Cloud support engineer
- My target: Cloud engineer / cloud solutions architect
- Skills that came up most often: scripting, AWS, Linux, containers, excel, Terraform
