# Packer

Packer is a VM image creation tool. It lets you automate the process of image creation on various on-premise and cloud solutions. If you are setting up an immutable infrastructure model using VM’s packer is a good choice.

## Why use Packer

* Packer, has super fast infrastructure deployment. Which allows images to launch completely, provisioned and configured in seconds, rather than several minutes or hours

* Multi-provider portability. Because Packer creates identical images for multiple platforms, you can run production in AWS, staging/QA in a private cloud like OpenStack, and development in desktop virtualization solutions such as VMware or VirtualBox. Each environment is running an identical machine image, giving ultimate portability.

* Improved stability. Packer installs and configures all the software for a machine at the time the image is built. If there are bugs in these scripts, they'll be caught early, rather than several minutes after a machine is launched.


## Configuration

Packer configuration templates are written in JSON format.
A template has the following three main parts.
1. Variables – Where you define custom variables.
2. Builders – Where you mention all the required AMI parameters.
3. Provisioners – Where you can integrate a shell script, ansible play or a chef cookbook for configuring a required application in the AMI (amazon machine image).

---

An Amazon Machine Image (AMI) is a special type of virtual appliance that is used to create a virtual machine within the Amazon Elastic Compute Cloud ("EC2"). It serves as the basic unit of deployment for services delivered using EC2

---
