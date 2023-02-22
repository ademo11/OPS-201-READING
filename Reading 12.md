# Importance of Virtualization in the Amazon EC2 Cloud
# In this post, I have selected the Amazon EC2 cloud service as a good use case to illustrate the importance of cloud virtualization in IaaS cloud service model.

# What is Virtualization?
# According to Tech Target (2017), the “Virtualization is the creation of a virtual, rather than actual, version of something.” (Virtualization, 2017).
# The concept of virtualization goes back to 1960s, but it was popularized by VMWare in 1999 when it was introduced to cheap Intel® hardware, which allowed anyone to virtualize a traditional computer with all its resources. The same model eventually extended from desktops and servers to also cover the network, storage, data devices, as well applications (through app virtualization – software encapsulation from the underlying operating system).
# Virtualization and the Amazon IaaS Cloud Service Model
 # The Amazon IaaS cloud service model is characterized by delivering virtualized computer infrastructure in the form of a service. A good example of the virtualization of Amazon AWS services is Amazon Elastic Compute Cloud (EC2), which is essentially an IaaS service that provides virtual servers based on the Xen hypervisor. 
 # The diagram in Figure 2 shows the architecture of EC2 host virtualization. The diagram also shows the crucial role that hypervisor in virtualization itself. It acts as a virtual machine manager that sits on top of the host system where all of the customer virtual machines run. “The relationship of the hypervisor to the host operating system and to the virtual machine is one of the key distinguishing characteristics of the different virtualization systems.” (Amies, Sluiman, and Tong, 2017).

# nother critical part of the entire process of virtualization in Amazon EC2 is Amazon Machine Image (AMI), which is also a virtual appliance. However, AMI is mainly responsible for creating on-demand virtual machines within the Amazon Elastic Compute Cloud. The diagram (Figure 3) is an illustration of the importance of Amazon AMI in the process of VM creation in Amazon EC2 and also shows how it generates the various EC2 instances on demand.

# To tie all the knots, the diagram in Figure 4 demonstrates the high-level architecture of Amazon EC2 and the relation of EC2 instances to availability zones in various regions. We can also see how EC2 instances use the storage through either Ephemeral (temporary) or Elastic Block Storage snapshots stored in Amazon S3; and observe how CloudWatch monitors AWS cloud resources and how EC2 web traffic is load balanced as well as how it passes trough various security rules.

# Inconclusion
  # “In summary, cloud computing leverages virtualization technology to achieve the goal of providing computing resources as a utility.” (Zhang, Cheng, and Boutaba, 2010)

Refrences
<https://www.joe0.com/2017/06/11/importance-of-virtualization-in-the-amazon-ec2-cloud/>  