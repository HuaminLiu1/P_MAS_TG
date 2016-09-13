P-MAS-TG
========

Planner for Multiple Agent System with Temporal Goals 

-----
Description
-----
this package contains implementation for plan synthesis algorithms given a finite transition system (as the agent motion model) and a Linear temporal logic formula (as the agent task). It outputs the static plan as a sequence of agent motion and action, required to fulfill the task. 

-----
Features
-----
* Action model can be muted if only motion is concerned
* Soft specification is optional
* NetworkX for the graph structure
* Static or on-the-fly construction of the product automaton
* Stand-alone planner


<p align="center">  
  <img src="https://github.com/MengGuo/Planner_LTL_ROS/blob/master/src/figures/indep.png" width="800"/>
</p>

<p align="center">  
  <img src="https://github.com/MengGuo/Planner_LTL_ROS/blob/master/src/figures/multi.jpg" width="800"/>
</p>


----
Usage
----
* install python packages like networkx, ply
* ltlba_32 and ltlba_64 are executable files complied under Unix. For other OS, please visit http://www.lsv.ens-cachan.fr/%7Egastin/ltl2ba/download.php