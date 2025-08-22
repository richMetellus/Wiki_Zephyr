#####################################
What is Zephyr [OS|Project]
#####################################


The Zephyr Project [ref:]

* was originally developed for the Virtuoso RTOS, intended for DSP processor
* started in Feb 2016, now name Zephyr
* this is now A Linux Foundation Project.
* Has many collaborators from many Industries, NXP is one of the early founders.

The Zephyr OS

* The Zephyr project includes Zephyr RTOS, an open-source real-time operating system (RTOS) 
   designed for resource-constrained embedded systems and IoT devices.

* Zephyr RTOS is an extremely flexible system with a tiny core primarily 
  designed to ensure energy efficiency,which corresponds to its development concept. 

* Its core is tickless by default, meaning that Zephyr software is an **event-driven system**. 
  However, you can change this since this OS is highly configurable

    * Event-driven means that the scheduler will be called not just once in a 
      certain period of time (like in FreeRTOS), but only for specific events 
      that change the state of the thread (also known as "tasks"), which are 
      referred to as rescheduling points.

* Zephyr offers a lot of OS Services that greatly simplifies the development of 
  many implementations not directly related to the main functionality of 
  the RTOS.

* Zephyr use Kconfig and devicetree as its configurations system (just like Linux)

*****************************************************
Zephyr Vs FreeRTOS: Which One should you chose?
*****************************************************

.. card::  Oleksandr Zozulia Advice From the Blog

   More often than not, the choice of a real-time operating system is based on 
   the already-selected hardware, cloud platform, development environment, and 
   developer's experience. I would recommend learning and using FreeRTOS if you've 
   just started to learn the concept of RTOS. However, if you take on a task to 
   develop a low-power solution or embedded software for a low-memory controller, 
   or you simply want to try using something other than FreeRTOS, turn your 
   attention to the Zephyr Project.

**********************
Flavors of Zephyr
**********************


Flavors of Zephyr:

* Zephyr Project
  
    * vanilla zephyr project supported by the Linux foundation

* nRF Connect with nRF Connect SDK

    * Still zephyr but it tastes a bit like Nordic
    * a fork of Zephyr

***************************
Presentations on Zephyr
***************************

I collected a bunch of useful presentation I found on Zephyr. The most important
ones I will try to list them and create a notes summary on them.

* the presentation slides are located on my school onedrive.

