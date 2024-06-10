# Virtualisation and Cloud Computing

## Course Overview
- **Course Structure**: Includes lectures and practical sessions conducted weekly.

## Objectives
- Understand virtualization principles.
- Manipulate virtualization concepts using practical tools.
- Discover cloud computing and its applications.
- Learn about cloud security concepts.

## Part 1: Virtualization

### 1. Definition and Principles
- **Virtualization**: Running multiple systems on a single physical machine, giving the illusion that each system is operating on a separate machine.
- **Key Concepts**:
  - **Architecture**: Comprises hardware layer (physical server), virtualization layer (hypervisor), and virtual machines.
  - **Forms of Virtualization**: Hardware, presentation, and application virtualization.
  - **Types**: Full virtualization, paravirtualization, and hardware-assisted virtualization.

### 2. Benefits and Drawbacks
- **Advantages**:
  - Improved hardware utilization
  - Enhanced flexibility and scalability
  - Resource sharing
- **Disadvantages**:
  - Complexity in management
  - Potential performance overhead
  - Security risks

### 3. Types of Virtualization
- **Hardware Virtualization**: Multiple environments on one physical system.
- **Presentation Virtualization**: Centralized application execution with remote display.
- **Application Virtualization**: Distributing applications without disrupting the underlying system.

### 4. Virtualization Components
- **Hypervisor**: The software layer enabling virtualization, managing the hardware resources, and ensuring isolation between virtual machines.
  - **Types of Hypervisors**: Type 1 (bare-metal) and Type 2 (hosted).
- **Virtual Machines (VMs)**: Encapsulated environments running on top of the hypervisor.

### 5. Network and Storage Virtualization
- **Network Virtualization**: Dividing a physical network into multiple logical networks.
  - **Benefits**: Reduced broadcast traffic, increased security, and flexibility.
- **Storage Virtualization**: Abstracting physical storage into virtual storage devices.
  - **Formats**: VHD (Microsoft), VDI (Oracle), VMDK (VMWare).

## Part 2: Cloud Computing Security

### 1. Introduction to Cloud Computing
- **Definition**: Delivery of computing services over the internet, providing on-demand access to resources like servers, storage, and applications.
- **Characteristics**: On-demand self-service, broad network access, resource pooling, rapid elasticity, and measured service.

### 2. Cloud Service Models
- **IaaS (Infrastructure as a Service)**: Provides virtualized physical resources.
  - **Examples**: OpenStack, Eucalyptus, OpenNebula.
- **PaaS (Platform as a Service)**: Offers platforms for application development and deployment.
  - **Examples**: Google App Engine, Microsoft Azure.
- **SaaS (Software as a Service)**: Delivers software applications over the internet.
  - **Examples**: Google Workspace, Salesforce.

### 3. Cloud Deployment Models
- **Public Cloud**: Services provided over the internet, shared among multiple users.
  - **Advantages**: Flexibility, cost-efficiency.
  - **Disadvantages**: Security concerns.
- **Private Cloud**: Dedicated infrastructure for a single organization.
  - **Advantages**: Enhanced security and control.
  - **Disadvantages**: Higher costs.
- **Hybrid Cloud**: Combination of public and private clouds, offering greater flexibility.
- **Community Cloud**: Shared infrastructure for a specific community or group.

### 4. Cloud Security Paradigms
- **Confidentiality**: Ensuring that data is accessible only to authorized users.
  - **Techniques**: Encryption, VPNs.
- **Integrity**: Ensuring data is not altered in an unauthorized manner.
  - **Techniques**: Checksums, digital signatures.
- **Availability**: Ensuring data and services are available when needed.
  - **Techniques**: Redundancy, failover mechanisms.

### 5. Cloud Security Challenges and Solutions
- **Common Threats**:
  - **Data Breaches**: Unauthorized access to data.
  - **Account Hijacking**: Unauthorized access to user accounts.
  - **DoS and DDoS Attacks**: Overloading resources to deny service to legitimate users.
  - **Malware Injections**: Introducing malicious software into cloud services.
- **Security Solutions**:
  - **Intrusion Detection Systems (IDS)**: Monitoring and detecting suspicious activities.
  - **Firewalls**: Controlling incoming and outgoing network traffic.
  - **Honeypots**: Decoy systems to detect and analyze attacks.

### Practical Sessions
- **Activities**:
  - Installation and configuration of virtualization platforms (ESXi, vSphere, KVM).
  - Setting up IaaS cloud environments.
  - Implementing security measures in cloud solutions.

