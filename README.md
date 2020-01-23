# santosh-notes


SOFTWARE ARCHITECTURE

Software architecture refers to the fundamental structures of a software system and the discipline of creating such structures and systems. Each structure comprises software elements, relations among them, and properties of both elements and relations.

Software Architecture

Monolithic Architecture Service Oriented Architecture (Micro services) Service Based Architecture (5G) A Monolithic architecture is the traditional unified model for the design of a software program. Monolithic means composed all in one piece.In a tightly-coupled architecture, each component and its associated components must be present in order for code to be executed or compiled.

      USER INTERFACE   -------> LOGIC ------> DATA INTERFACE  -------> DATEBASE 

Service-oriented architecture (SOA) is a style of software design where services are provided to the other components by application components, through a communication protocol over a network. The basic principles of service-oriented architecture are independent of vendors, products and technologies.

Service-Based Architecture (SBA), whereby the control plane functionality and common data repositories of a 5G network are delivered by way of a set of interconnected Network Functions (NFs), each with authorization to access each other's services

How to deploy websites

Purchase a Domain Name (If you are new you need to do is register a domain name.)

After building the Website/Project its time for deployment. Generally we are using Cloud Service for hosting the website on the Server. Examples of cloud services include online data storage and backup solutions, Web-based e-mail services, hosted office suites and document collaboration services, database processing, managed technical support services and more. With help of Cloud Service we get the fixed IP address (Public IP address) and another services which is important for website. IP Address ---> 1.Private IP address 2.Public IP address

*Note :-Local host /127.0.0.1.( Private IP address)

Cloud Service Provider Amazon Web Services(AWS), Microsoft Azure , Digital Ocean, IBM Cloud, Rackspace, Go Daddy etc;

CI/CD( Continous Integration Continous Deployment)

A CI/CD pipeline helps you to automate step in your software delivery process,such as initialing code builds,running automated tests,and deploying to a production enviiroment.Automated pipelines remove manaul errors,provide standardized development feedback loops and enable fast product iterations.

CI,short for Continous Integration, is a software development practice in which all developers merge code changes in a central repository multiple times a day. CD stand for Continous Integration adds the practice os=f automating the entire software release process. With CI, each change in code trigger an automated build and test sequences foe the given code. CD includes infrastructure provisioning and deployment ,which may be manual ansd consist of multiple stages. What's important is that all these processes are fully automated with each run fully logged and visible to the entire team .

DevOps -(Development + Operations). is how modren developers are builing great products by using new methods of Continuous Integration,Continuous Delivery,(CI/CD) and Continuous Deployment.Most teams have automated processes to check in code and deploy to new environment.

Operating System (OS)

An operating system is the primary software that manages all the hardware and other software on a computer. The operating system, also known as an Operating System interfaces with the computer’s hardware and provides services that applications can use.

An operating system is the core set of software on a device that keeps everything together. Operating systems communicate with the device’s hardware. They handle everything from your keyboard and mice to the Wi-Fi radio, storage devices, and display. In other words, an operating system handles input and output devices. Operating systems use device drivers written by hardware creators to communicate with their devices. UNIX LINUX WINDOWS etc, UNIX

Unix is a portable,multitasking,multiuser,time-sharing operting system (OS) originally developed in 1969 by a group of employees at AT&T.Unix was first programmed in assembly language but was reprogrammed in C in 1973.Unix has been ported to more machine families than any other operating system.

Developer -Ken Thompson, Dennis Ritchie and others. Written in :C, Assembly language

LINUX

Linux is a family of open source Unix-like operating systems based on the Linux kernel, an operating system kernel first released on 1991, by Linus Torvalds.Linux is typically packaged in a Linux distribution. Linux was originally developed for personal computers based on the Intel x86 architecture, but has since been ported to more platforms than any other operating system.Linux is a freely distributable version of Unix.

Developer- Linus Torvalds Written in :C, Assembly language ,

GNU-(GNU stands for GNU's Not UNIX. It is a UNIX like computer operating system, but unlike UNIX, it is free software and contains no UNIX code. It is pronounced as guh-noo. Sometimes, it is also written as GNU General Public License.)

Note:- Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development. Its current maintainer since 2005 is Junio Hamano. Its goals include speed, data integrity, and support for distributed, non-linear workflows. The purpose of Git is to manage a project, or a set of files, as they change over time. Git stores this information in a data structure called a repository.

Why use Linux ?

Linux makes very efficient use of the system's resources.This allows them to install Linux even on old hardware, thus helping in optimal use of all the hardware resources. Linux runs on a range of hardware

High stability: The Linux system is very stable and is not prone to crashes. The Linux OS runs exactly as fast as it did when first installed, even after several years.

Free: Linux is completely free and users do not need to pay for anything. All the basic software required by a typical user and even an advanced user are available.

Open source: The most important aspect of Linux is that its source code is available as it falls under the Free and Open Source Software.The developer community benefits from this as its members have the freedom to view and modify the source code.

WINDOWS Windows OS, computer operating system developed by Microsoft Corporation to run personal computers. Featuring the first graphical user interface (GUI) for IBM-compatible PCs, the Windows OS soon dominated the PC market.

Microsoft Windows. Operating system designed and produced by Microsoft Corporation. Similar to other operating systems, Windows makes a computer system user-friendly by providing a graphical display and organizing information so that it can be easily accessed.

KERNEL Kernel is a computer program that is the core of a computer's operating system, with complete control over everything in the system. The kernel give interactions between hardware and software components.

Written in :C, Assembly language

DATE : 20/01/2019

BARE METAL:- Bare metal is a computer system without a base operating system (OS) or installed applications. It is a computer's hardware assembly, structure and components that is installed with either the firmware or basic input/output system (BIOS) software utility or no software at all.

Hypervisor:- A hypervisor, also known as a virtual machine monitor, is a process that creates and runs virtual machines (VMs). A hypervisor allows one host computer to support multiple guest VMs by virtually sharing its resources, like memory and processing. Type 1 hypervisor : A Type 1 hypervisor runs directly on the host machine's physical hardware, and it's referred to as a bare-metal hypervisor; it doesn't have to load an underlying OS first. Type 2 hypervisors : A Type 2 hypervisor is typically installed on top of an existing OS, and it's called a hosted hypervisor because it relies on the host machine's pre-existing OS to manage calls to CPU, memory, storage and network resources.

Virtual Machine :- Virtual machines are software computers that provide the same functionality as physical computers. Like physical computers, they run applications and an operating system. However, virtual machines are computer files that run on a physical computer and behave like a physical computer. In other words, virtual machines behave as separate computer systems.

Onion Routing :- Onion routing is a technique for anonymous communication over a computer network. In an onion network, messages are encapsulated in layers of encryption, analogous to layers of an onion. There is a large set of precautionary measures and best practices to make web browsing safer and more secure for users.

Page Rank Algorithm :- The PageRank algorithm outputs a probability distribution used to represent the likelihood that a person randomly clicking on links will arrive at any particular page. PageRank can be calculated for collections of documents of any size. It is assumed in several research papers that the distribution is evenly divided among all documents in the collection at the beginning of the computational process. The PageRank computations require several passes, called “iterations”, through the collection to adjust approximate PageRank values to more closely reflect the theoretical true value.

Namespace :- A namespace is a group of related elements that each have a unique name or identifier. There are several different types of namespaces, and each one has a specific syntax used to define the corresponding elements. Each element within a namespace has a "local name" that serves as a unique identifier.

DataStore :- A datastore is a repository for storing, managing and distributing data sets on an enterprise level. It is a broad term that incorporates all types of data that is produced, stored and used by an organization. A datastore may include data from end user database applications, files or documents, or the random data property of an organization or an information system. Datastore data may be structured, unstructured or in another electronic format.

Docker :- Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package. Docker is a tool that is designed to benefit both developers and system administrators, making it a part of many DevOps (developers + operations) toolchains. Docker brings security to applications running in a shared environment, but containers by themselves are not an alternative to taking proper security measures.

Blockchain :- it is a distributed ledger where the saved digital records are distributed across all participating nodes in the network. Each node maintains an updated copy of the ledger.a blockchain is a chain of blocks, containing time-stamped digital records. Initially described by a group of researchers in 1991, this technique was intended to timestamp digital records so that no one could backdate or tamper them. Block

Every block comprises of-

Data
Hash of the block
Hash of the previous block

The data recorded in a block depends on the blockchain type. For example, Bitcoin Blockchain saves the details about a transaction such as a receiver, sender and number of coins. A hash of the block is similar to a fingerprint(always unique) that provides identification to the block and its contents. Once a block is created, a hash gets generated. Hash value gets changed with every change in the block. Therefore, hash values help in detecting the changes made to blocks. Containing a hash of the previous block means every block is linked to each other and creates a chain of blocks, known as “Blockchain.” Once the data has been recorded or added in a blockchain, it becomes difficult to change it.
