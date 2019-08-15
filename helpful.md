Here's a list of helpful resources that you might find useful. I'll be expanding this list as the semester goes on and I have more such links:


* **[Full MIT Open Course on Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/)** - Much of this course builds code to solve Linear Algebra style equations so this might be worth taking some time to gain a basic understanding of.
* **[Numerical Methods Web Materials](http://mathforcollege.com/nm/topics/)** - Site with a lot of great videos/textbook like materials on Numerical Methods, which is where I'll pull from but great if you want more info. Look especially at the topics on errors.
* **[Jetson Nano Cluster Tutorial](https://github.com/csuchico-csci551/JetsonCluster)** - Tutorial and Ansible scripts for setting up a small scale cluster with NVIDIA Jetson Nano boards. 
* **[Compute Instances Scripts](https://github.com/csuchico-csci551/compute-instances)** - Ansible scripts modified from the [Using Ansible with Google Video](https://www.youtube.com/watch?v=FF-HfP_OHpU) that will spin up a compute instance, run hello world code, and then spin the cluster down.
  * You could modify these scripts to change the type of compute instance and to run your code if you desire.
  * **Use at your own risk** - I'll have limited GCP credits for you to use this semester, which you may also wish to use for your final project in this class too. I am not confident in how these scripts handle failures so make sure you know how to manually bring down your compute instance on your own when finished so you don't use more credits than you need.
* **[Slurm on GCP Scripts](https://github.com/csuchico-csci551/slurm-gcp)** - Code adapted from a Google Tutorial to run a HPC Slurm Instance on GCP.
  * You could modify these scripts to change the type of instances used in the cluster nodes.
  * There is an experimental python script to start the cluster, wait for it to be fully up and running, then run a hello world MPI program, get the results, and then destroy the cluster automatically. It is not fully implemented and some of the edge cases such as failures/etc aren't fully functional at this point so similar to the single instance scripts, **use at your own risk** and know how to bring the cluster down manually to prevent losing all your GCP credits.
