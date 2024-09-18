
# key_words

# 1.**COMPUTING**
* CPU(CENTRAL PROCESSING UNIT)->The CPU, or Central Processing Unit, is often referred to as the "brain" of a computer. It's the primary component responsible for executing instructions from programs and managing the operations of the computer.
  
* GPU(GRAPHIC PROCESSING UNIT)->The GPU, or Graphics Processing Unit, is a specialized processor designed to accelerate the rendering of images and video. It’s optimized for handling the complex calculations required for graphics rendering, making it crucial for visual output in computers, gaming consoles, and mobile devices.
  
* DPU(DATA PROCESSING UNIT)->A DPU, or Data Processing Unit, is a specialized processor designed to handle data-centric tasks efficiently. It focuses on managing and processing large volumes of data, often in the context of network, storage, and data center operations. 
  
* TPU(TENSOR PROCESSING UNIT)->A TPU, or Tensor Processing Unit, is a type of specialized hardware designed by Google specifically for accelerating machine learning and artificial intelligence (AI) workloads. TPUs are optimized for processing tensors, which are multidimensional arrays used extensively in machine learning models.

# 2.**operating system**

An operating system (OS) is the software that manages a computer's hardware and software resources and provides common services for computer programs.
It's essentially the backbone of a computer system, enabling users to interact with the hardware and run applications.

![image alt](https://github.com/shub1504/Keywords/blob/54baf75a6351d4282daaa21013b2efa2bc4eb9b6/os.jpeg)

* **CISC**->CISC, or Complex Instruction Set Computer, is a type of computer architecture that aims to provide a rich set of instructions for executing a wide variety of tasks directly in hardware.

* **RISC**->RISC, or Reduced Instruction Set Computer, is a type of computer architecture that focuses on a simplified set of instructions compared to CISC (Complex Instruction Set Computer) architectures. The RISC approach emphasizes efficiency and speed by using a smaller, more streamlined set of instructions.

* **RISC-V**-> is an open standard instruction set architecture (ISA) based on the principles of Reduced Instruction Set Computer (RISC) design.

* **KERNAL**->The term "kernel" refers to the core component of an operating system (OS) that manages system resources and enables communication between hardware and software.

* **LINUX**->Linux is a widely-used open-source operating system kernel that serves as the foundation for many operating systems, commonly referred to as Linux distributions or distros.

# 3.**NETWORK**
A network is a system that connects multiple devices, allowing them to communicate with each other and share resources.

**TYPES OF NETWORK**
* **LOCAL AREA NETWORK(LAN)**-> A network that connects devices within a limited area, such as a home, office, or campus. LANs are typically used to share resources like printers and files and to facilitate communication between devices.

*  **PERSONAL AREA NETWORK(PAN)**->A small-scale network, often used for connecting devices within a personal workspace or home. Bluetooth and Wi-Fi networks are examples of PANs.

*   **METROPOLITIAN AREA NETWORK(MAN)**->A network that covers a city or a large campus. MANs are often used by municipalities or large organizations to connect multiple buildings or sites within a city.

*   **WIDE AREA NETWORK(WAN)**->A network that covers a city or a large campus. MANs are often used by municipalities or large organizations to connect multiple buildings or sites within a city.

*   **VIRTUAL PRIVATE NETWORK(VPN)**->A network that uses encryption and other techniques to provide secure access to a private network over a public network, like the Internet. VPNs are used to protect sensitive data and allow remote users to access resources securely.

# 4.OSIMODEL(7 LAYERS)->
The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and standardize the functions of a network system into seven distinct layers.

**1. PHYSICAL LAYER->** Deals with the physical aspects of network communication. It involves the transmission and reception of raw binary data (0s and 1s) over physical media such as cables, fibers, or radio waves.

**2. DATA LINK LAYER->** Handles node-to-node data transfer and manages error detection and correction from the Physical layer. It ensures that data packets are correctly formatted for transmission and that errors during transmission are detected and corrected.

**3. NETWORK LAYER->** Manages data routing, forwarding, and addressing across multiple networks. It determines the best path for data to travel from the source to the destination.

**4. TRANSPORT LAYER->**Ensures reliable data transfer between devices. It manages data flow control, error recovery, and retransmission.

**5. SESSION LAYER->** Manages and controls the sessions between applications. It establishes, maintains, and terminates connections.

**6. PRESENTATION LAYER->**Translates, encrypts, and compresses data for the application layer. It ensures that data is presented in a format that the application layer can understand.

**7. APPLICATION LAYER->**Provides network services directly to end-user applications. It is the closest layer to the end user and interacts with software applications. 

# 5.CLOUD COMPUTING 
Cloud computing is a model for delivering computing resources and services over the internet, allowing users to access and manage resources like servers, storage, databases, networking, software, and more, on-demand.

# 6.DOMAIN NAME SERVER(DNS)->
The Domain Name System (DNS) is a hierarchical system used to translate human-friendly domain names  into IP addresses that computers use to identify each other on the network. Essentially, DNS acts like the internet’s phone book, converting names into numbers so that computers can locate each other and communicate.

# 7.IP ADDRESS->
An IP address (Internet Protocol address) is a unique numerical label assigned to each device connected to a network that uses the Internet Protocol for communication. It serves two primary functions:
  * **1. IPv4 (Internet Protocol version 4)**
    Consists of four sets of numbers separated by dots, where each set is a number between 0 and 255. IPv4 addresses are the most widely used but are limited in number, which has led to exhaustion of available addresses.

* **IPv6 (Internet Protocol version 6)**
  Uses a 128-bit address, represented as eight groups of four hexadecimal digits separated by colons. IPv6 addresses provide a vastly larger address space than IPv4, addressing the issue of address exhaustion.

* **PUBLIC IP**
  An IP address that is globally unique and routable on the internet. It identifies a device or network that can be accessed over the internet.

* **PRIVATE IP**
  An IP address used within a private network that is not routable on the internet. It is used to identify devices within a local network.

# 8.HYPERVISER
A hypervisor is a type of virtualization software that allows multiple virtual machines (VMs) to run on a single physical host. It provides an abstraction layer between the hardware and the virtual machines, enabling efficient resource allocation and management.

**TYPES OF HYPERVISOR**
1. Type 1 Hypervisor (Bare-Metal):Runs directly on the physical hardware of the host machine. It does not require an underlying operating system.
2. Type 2 Hypervisor (Hosted): Runs on top of a conventional operating system (the host OS) and relies on the host OS for hardware access.

# 9.VIRTUAL MACHINE->
A virtual machine (VM) is a software-based emulation of a physical computer. It runs an operating system and applications just like a physical computer but does so within a virtualized environment created by a hypervisor. 

# 10.GENERAL DATA PROTECTION REGULATION->
It is a comprehensive data protection law in the European Union (EU). It sets out to protect the privacy and personal data of individuals within the EU and the European Economic Area (EEA)0. 

# 11.DNS(Domain Name System)
DNS stands for Domain Name System. It functions like a phone book for the internet, translating human-friendly domain names (like www.example.com) into IP addresses (like 192.0.2.1) that computers use to identify each other on the network.
Here's a simple breakdown of how DNS works:

1.Request: When you type a web address into your browser, a DNS request is made to find the corresponding IP address for that domain name.
2.Resolution: The DNS system then looks up the IP address associated with that domain name. This process involves several steps:

   Recursive Resolver: : Your request first goes to a DNS resolver, which is often provided by your ISP. This resolver tries to find the IP address for the domain name.
  Root Name Servers: If the resolver doesn't have the address cached, it queries one of the root name servers, which point to the appropriate top-level domain (TLD) name servers.
  
  TLD Name Servers: The TLD servers then direct the resolver to the authoritative name servers for the specific domain.
  Authoritative Name Servers: These servers have the actual IP address for the domain and respond to the resolver with this information.

  # 15.VPN(Virtual Private Network)
  A VPN, or Virtual Private Network, is a service that creates a secure, encrypted connection over aless secure network, such as the internet. It allows you to access the internet as if you were connected to a private network, providing privacy and security. Here's how it works and why you might use it:
 
  1.Encryption:When you connect to a VPN, your internet traffic is encrypted, meaning that the data you send and receive is scrambled and unreadable to anyone who might intercept it. This helps protect your data from hackers, especially on public Wi-Fi networks.

  2.IP Masking: A VPN hides your real IP address and replaces it with one from the VPN server. This can make it harder for websites, advertisers, and other parties to track your online activities and identify your location.

  3.Secure Access: VPNs provide secure access to your network resources, which can be useful for businesses allowing remote employees to connect to internal systems securely.

  # 16.FRONTEND,BACKEND AND API(Application Programming Interface)
  In web development, the terms frontend, backend, and API refer to different aspects of building and   managing applications. Here’s a breakdown of each:

   # FRONTEND:
       Frontend refers to the client-side of a web application. It encompasses everything that users interact with directly in their web browsers. This includes:
            -Design and Layout: The visual aspects of a website or application, including the layout,colors, fonts, and images.
            -User Interface (UI): The components that users interact with, such as buttons, forms, and navigation menus.
            -Technologies: Frontend development primarily involves languages and frameworks like HTML (Hypertext Markup Language), CSS (Cascading Style Sheets), and JavaScript. Frameworks and libraries like React, Angular, and Vue.js are commonly used to build interactive and dynamic user interfaces.

 # BACKEND:
      Backend refers to the server-side of a web application. It involves everything that happens on the server and is responsible for managing and processing data. Key aspects include:
                 --Server: The hardware or software that provides services, resources, or data to other computers over a network.
                 --Database: Where data is stored, retrieved, and managed. Common databases include MySQL, PostgreSQL, and MongoDB.
                 --Server-Side Logic: The code that runs on the server, handling requests from the frontend, processing data, and sending responses. This includes server-side languages like Python, Ruby, Java, PHP, and Node.js.
                 --Authentication: Managing user login, registration, and security.
API.

# API:
    API stands for Application Programming Interface. It is a set of rules and protocols that allows different software applications to communicate with each other. APIs can be used to:

        --Connect Frontend and Backend: APIs often serve as the bridge between the frontend (client-side) and backend (server-side). For instance, when you submit a form on a website, the frontend sends a request to the backend via an API, which processes the request and sends back a response.
        --Access External Services: APIs enable applications to interact with third-party services or data sources. For example, a weather app might use an API to fetch weather data from an external weather service.
        --Standardize Communication: APIs provide a standardized way for different software components or systems to interact, regardless of their underlying technology.

  REST (Representational State Transfer)and GraphQL are common API design styles. REST APIs use HTTP requests to interact with resources, while GraphQL allows clients to request specific data and aggregate results from multiple sources.


 # NIC (Network Interface Card)

    NIC stands for Network Interface Card. It's a hardware component that allows a computer or other devices to connect to a network. Here’s a quick rundown:
     -- Function: NICs facilitate communication between a computer and a network. They handle the process of sending and receiving data packets over the network, making it possible for the device to access network resources, such as the internet or shared files.   

  #TYPES:
   --Wired NICs:These connect via Ethernet cables and are typically used in local area networks (LANs). They are often built into the motherboard of a computer but can also be installed as a separate expansion card.

   --Wireless NICs: These connect via Wi-Fi and allow devices to connect to wireless networks. They are commonly found in laptops and some desktop computers, and can also be installed as a separate card or USB adapter.

   --Components: A NIC typically includes a network port (like an Ethernet port for wired connections), and sometimes LEDs that indicate network activity and connection status. Inside, it has a chip that handles data transmission and reception.

   --Configuration: NICs usually come with drivers that need to be installed on the computer. These drivers allow the operating system to communicate with the NIC and configure it correctly.

   --Speed: NICs come in various speeds, such as 10/100/1000 Mbps (Gigabit Ethernet) for wired connections, and support various Wi-Fi standards for wireless connections (e.g., 802.11n, 802.11ac, or the newer 802.11ax).

# INTERNET PACKET
    An Internet packet, often just called a "packet," is a small unit of data transmitted over a network. When you send or receive information over the Internet, it is broken down into packets to ensure efficient and reliable delivery. Here’s a breakdown of what an Internet packet typically involves:

# Components of an Internet Packet:

   1.Header:

       --Source IP Address: The address of the device that is sending the packet.
       --Destination IP Address: The address of the device that is receiving the packet.
       --Sequence Number: This helps in reassembling the packets in the correct order, as packets can arrive out of sequence.
       --Protocol Information: Specifies the protocol being used, such as TCP (Transmission Control Protocol) or UDP (User Datagram Protocol).
       --Checksum: A value used for error-checking to ensure the data hasn’t been corrupted during transmission.

   2.Payload:
          This is the actual data being transmitted, such as part of an email, a webpage, or a file. It’s the content that the packet carries from the sender to the receiver.


# AWS (Amazon Web Service):
    Amazon Web Services (AWS) is a comprehensive and widely adopted cloud computing platform provided by Amazon. It offers a broad range of cloud services, including computing power, storage options, and databases, among others, all delivered over the internet. AWS allows individuals and organizations to use these resources on a pay-as-you-go basis, which means you only pay for what you use.

# CORE SERVICES:
     1.Compute Services:
          --Amazon EC2 (Elastic Compute Cloud):
               Provides resizable virtual servers (instances) that can be used for a variety of applications.
          --AWS Lambda: Allows you to run code in response to events without provisioning or managing servers (serverless computing).
          --Amazon ECS (Elastic Container Service) and EKS (Elastic Kubernetes Service):
          Manage containerized applications using Docker and Kubernetes.

     2.Storage Services:
          --Amazon S3 (Simple Storage Service):
               Scalable object storage for storing and retrieving any amount of data.
          --Amazon EBS (Elastic Block Store): Provides block-level storage volumes for use with EC2 instances.
          --Amazon Glacier: Low-cost cloud storage service for data archiving and long-term backup.

     3.Database Services:
         --Amazon RDS (Relational Database Service): Managed relational database service supporting multiple database engines (MySQL, PostgreSQL, MariaDB, Oracle, and SQL Server).
         --Amazon DynamoDB: Managed NoSQL database service designed for high-performance and scalability.
         --Amazon Redshift: Data warehouse service designed for big data analytics.

     4.Networking Services:
        --Amazon VPC (Virtual Private Cloud): Enables you to create a private network within the AWS cloud.
        --Amazon Route 53: Scalable DNS and domain name registration service.
        --AWS Direct Connect: Provides a dedicated network connection from your premises to AWS.

     5.Security and Identity:
          --AWS IAM (Identity and Access Management): Manages access to AWS services and resources securely.
          --AWS KMS (Key Management Service): Manages cryptographic keys for your applications and data.
         
          
   
       

   
    
         
