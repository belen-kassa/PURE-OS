# PURE-OS


                           DOCUMENTATION DESCRIPTION


INSTALLATION PROCESS

This document provides a step-by-step guide for installing PureOS using Oracle VM VirtualBox. It includes all the essential procedures, from downloading the ISO file to completing the virtual machine setup and finishing the operating system installation. The instructions are designed for users who want to explore PureOS in a virtual environment for learning, privacy-focused computing, or development purposes.

The process walks through setting up the virtual machine with recommended settings such as memory allocation, storage space, and system type. Screenshots and descriptions are used to make each step easier to follow and avoid common setup errors. This guide is especially useful for students and beginners who are working with virtual systems for the first time and want a simple and effective way to get started with PureOS.

SYSTEM CALL

The nice() system call in PureOS (a Debian-based Linux system) is used to adjust the priority of a process during execution. It helps control how much CPU time a process gets by modifying its niceness value. A higher niceness means lower priority, allowing other processes to take more CPU, while a lower value gives the process higher priority.

This system call is useful for managing performance in multitasking environments. For example, background processes can be assigned higher niceness to reduce their impact on active tasks. It is defined in the <unistd.h> header and can be used both in C programming and from the terminal using the nice command.

Since PureOS supports standard Linux kernel calls, the nice() function works the same way as in other Linux distributions. This feature allows users to optimize system behavior, especially in resource-limited environments like virtual machines.
