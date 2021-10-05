# **Saving the State of a Virtual Machine**

Course: DevOps

Mod: Week 1

Topic: Saving the State of a Virtual Machine

Amount of time: 1.5 hours

Author: Thomas Fowler

## **Lesson Objectives**

* Understand what it means to preserve the state of a
virtual machine.

* Describe the process of saving state of a virtual machine
in VirtualBox.

--------------------------------------------

### **Overview**

There are two three types of methods to shut down a virtual
machine. Two of three methods are relatively
straightforward, the ACPI Shutdown and Power Off methods.
Both of these methods do not preserve any state of the
virtual machine and when the VM is resumed, it is as if
the virtual machine was rebooted via restart or some other
conventional method.

The only option when shutting down a virtual machine that
preserves state is the "Save the Machine State" method.
This method is analogous to suspending a physical machine
like a desktop or laptop computer.

--------------------------------------------

### **Saving the Virtual Machine State**

When shutting down the virtual machine with the "Save the
Machine State" method the virtual machine suspends its
activity and makes catalogs open applications and other
various VM state-related details. Upon resuming operation
the VM resotres its applications and their respective
states, prior to the VM's suspension.
