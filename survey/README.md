# Survey
## The deployer’s problem: Configuring application servers for performance and reliability. (ICSE '03) Mukund Raghavachari, Darrell Reimer, Robert D. Johnson.
This paper is the first work that focus on this problem. It outlines the problems facing the deployer of applications, and presents a trivail methodology that can assist the programmer with the task of configuring application servers, and presents two case studies that validate the usefulness of the methodology. 

## Online response time optimization of apache web server. (IWQoS '03) Xue Liu, Lui Sha, Yixin Diao, Steven Froehlich, Joseph L. Hellerstein, Sujay Parekh
This paper uses a fuzzy control based hill-climbing algorithm to online optimize response time of a web server.It's performance metrice is response time and tuning parameter is MaxClinet and uses static workload and dynamic workload to compare the result.

## A smart hill-climbing algorithm for application server configuration.(WWW '04) Bowei Xi, Zhen Liu, Mukund Raghavachari
This work is the improvement of the hill-climbing algorithm with importance sampling and Latin Hypercube Sampling. The performance is also the response time but the tuning parameter is increased to four parameters: The maximum number of threads in the Web Container thread pool, the maximum number of threads in the EJB Container thread pool, the maxi mum number of connections to the database in the Data Source Connection Pool, the maximum size of the Java Virtual Machine (JVM) on which WebSphere runs. And, this work mimics a production system for an on-line brokerage application.

## Automatic Performance Tuning for J2EE Application Server Systems.(WISE '05) Yan Zhang, Wei Qu, Anna Liu
This work uses a online tuning agent based on fuzzy control to reconfigure the application sever according to system variations. The performance metric and tuning parameter is the same with second paper 

## Automatic configuration of internet services(EuroSys '07) Wei Zheng, Ricardo Bianchini, Thu D. Nguyen
This paper uses a CART algorithm to generate the parameter dependency graph through a three tier web system, which explicitly represented relationship between configurable parameters. It considers two perfomance metrics: throughput and performance, and over ten kinds of tuning parameters. Howerver, it only mimics the experiment and apparent cannot be applied to real environment.

## Optimizing System Configurations Quickly by Guessing at the Performance.(SIGMETRICS '07) Takayuki Osogami, Sei Kato
This paper proposes an algorithm, which refers to as Quick Optimization via Guessing (QOG), that quickly selects one of nearly best configurations with high probability. This is a probability method and only consider throughput as the performance metric. The tuning parameters are MaxClients, ThreadPoolMax, HeapMax, PSCacheSize.

## A Reinforcement Learning Approach to Online Web Systems Auto-configuration.(IPDPS '09) Xiangping Bu, Jia Rao, Cheng-Zhong Xu
This paper firstly proposes a reinforcement learning approach, namely RAC, towards automatic configurations of multi-tier web systems in VM-based dynamic environment. It uses a multi-tier web system running TPC-W benchmark. The significance is the using of reinforcement learning.


##Transfer Learning for Performance Modeling of Configurable Systems: An Exploratory Analysis. (ASE '17) Pooyan Jamshidi, Norbert Siegmund, Miguel Velez, Christian Ka ̈stner Akshay Patel, Yuvraj Agarwal
This paper is an empirical study to shed light on when it is beneficial to apply transfer learning in configurable system. It focus on four popular software systems: 
\begin{itemize}
\item[1.]
\item[2.] 
\end{itemize}

