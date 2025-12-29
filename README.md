23CS302PC303 
HIGH PERFORMANCE COMPUTING	L	R	P	C
	3	0	4	5
Course type	Program Core	Pre-requisite	NA

UNIT I: Foundations of High Performance Computing
1.	HPC - Serial vs. Parallel vs. High Throughput, Flynn's Taxonomy. Need of Parallelism, Moore's Law, Power Wall.-Dr.K.Deepa
2.	HPC Architectures: Shared Memory -SMP, NUMA, Distributed Memory -Clusters, Hybrid Systems, Accelerators -GPUs. Memory Hierarchies, Interconnects - Latency/Bandwidth-Dr.N.Sharmila Banu
3.	Parallel Programming Models: Shared Memory -Threads, Distributed Memory -Message Passing, Accelerator Programming. Dr.Rahul Mishra
4.	Principles of Parallel Algorithm Design: Decomposition -Task/Data, Mapping, Communication, Synchronization, Load Balancing.-Mrs.G.Neelima
5.	Performance Metrics and Analysis Introduction: Speedup, Efficiency, Scalability -Strong/Weak, Amdahl's Law, Gustafson's Law. Profiling Concepts.-Dr.Manike Chiranjeevi
6.	HPC Environment and Tools: Accessing Clusters, Linux Command Line Essentials for HPC, Schedulers -e.g., Slurm, Compilers -GCC, LLVM, Vendor and Optimization Flags.-Dr.Sumit K Singh

UNIT II: Shared Memory Programming with OpenMP
7.	OpenMP: Architecture, Execution Model, Constructs -parallel, for, sections.-Dr.Sajal Mondal
8.	Work-sharing Constructs: Loop scheduling -static, dynamic, guided, single, master.-Dr.Deepak Tripathi
9.	Data Environment: shared, private, firstprivate, lastprivate, reduction. Data Races and False Sharing.-Dr.Hitesh Vijay Kumar
10.	Synchronization: critical, atomic, barrier, ordered, locks.Dr.M.Suresh Kumar
11.	Tasking with OpenMP: task, taskwait, taskgroup. Dependencies. Recursive Parallelism.-Dr.S.Jamlaiah
12.	NUMA Architectures and OpenMP: Affinity, Memory Placement -first touch, Bandwidth Considerations. STREAM Benchmark analysis.-Dr.Raman Kothuri
13.	Vectorization with OpenMP SIMD: simd directive, declare simd, Alignment, Array Notation-Dr.Durgesh Nandan
14.	OpenMP Performance Analysis and Optimization: Identifying overheads, load imbalance, synchronization costs. Using profilers -e.g., gprof, perf, vendor tools for OpenMP.-Dr.K.Deepa

UNIT III: Distributed Memory Programming with MPI
15.	MPI: Architecture, Communicators, Ranks, Processes, Initialization/Finalization, Send/Receive.-Dr.N.Sharmila Banu
16.	Point-to-Point Communication I: Blocking Send/Receive -MPI_Send, MPI_Recv, Buffering, Deadlock avoidance. -Dr.Rahul Mishra  
17.	Non-blocking Send/Receive -MPI_Isend, MPI_Irecv, Completion -MPI_Wait, MPI_Test, Communication Modes -Standard, Buffered, Synchronous, Ready. Overlapping Communication/Computation.-   Mrs.G.Neelima
18.	Collective Communication I: Overview, Broadcast, Scatter, Gather.-Dr.Manike Chiranjeevi   
19.	Reduction Operations -MPI_Reduce, MPI_Allreduce, Scan -MPI_Scan.-Dr.Sumit K Singh  
20.	Barrier -MPI_Barrier, Scatter/Gather Variants -MPI_Allgather, MPI_Alltoall. Non-blocking Collectives  -Dr.Sajal Mondal 
21.	MPI Derived Datatypes: MPI_Type_vector, MPI_Type_contiguous, MPI_Type_struct. Non-contiguous data transfer.-Dr.Deepak Tripathi  
22.	MPI Process Topologies: Cartesian and Graph Topologies.-Dr.Hitesh Vijay Kumar   
23.	MPI Performance Analysis and Optimization: Communication overhead, Latency/Bandwidth impact, Load balancing strategies. Using profilers -e.g., TAU, Scalasca, vendor tools for MPI.-Dr.M.Suresh Kumar   
24.	Hybrid MPI+OpenMP Programming: Models and Implementation.-Dr.S.Jamlaiah

UNIT IV: Accelerator Programming -GPU Focus 
25.	GPU Architecture -SMs, Warps/Wavefronts, Memory Hierarchy -Global, Shared, Constant, Local, Cache, Host-Device Interaction.-Dr.Raman Kothuri   
25.	CUDA C/C++: Kernel Launch Syntax, Thread Hierarchy -Grid, Block, Thread-Dr.Durgesh Nandan  
26.	CUDA Memory Management: Device Memory Allocation -cudaMalloc, cudaFree, Host-Device Transfers -cudaMemcpy, Unified Memory.-Dr.K.Deepa   
27.	Shared Memory for Data Reuse, Synchronization -__syncthreads-. Matrix Multiplication-Dr.N.Sharmila Banu
28.	Portable GPU Programming: OpenMP Offloading - -target, teams distribute parallel for simd, map clause.  -Dr.Rahul Mishra 
29.	OpenMP Offloading II: Data Mapping Deep Dive, Asynchronous Operations -nowait, Tasking on GPUs. -Mrs.G.Neelima  
26.	SYCL -Optional, based on faculty expertise/interest: Concepts, Syntax, Comparison with CUDA/OpenMP Offload.-Dr.Manike Chiranjeevi  
30.	Occupancy, Memory Bandwidth, Coalescing, Divergence. Using GPU profilers -e.g., Nsight Compute/Systems, vendor tools.-  Dr.Sumit K Singh 

UNIT V: Advanced Topics and Applications
33.	Roofline Model Deep Dive, Advanced Loop Optimizations -Tiling, Fusion, Communication Optimization Techniques. -Dr.Sajal Mondal 
34.	Parallel I/O: Concepts, Parallel File Systems Overview -e.g., Lustre, MPI-IO.-Dr.Deepak Tripathi
35.	Cloud HPC Offerings -AWS/Azure/GCP Overview, Virtual Clusters, Cost Models-Dr.M.Suresh Kumar 
36.	Containerization: Docker and Singularity/Apptainer, Reproducibility, Dependency Management-Dr.S.Jamlaiah

Labs
1.	Accessing HPC Cluster and Job Submission -Dr.Durgesh Nandan
2.	Serial Performance Baseline and Profiling-Dr.SriRaman Kothuri 
3.	OpenMP: Parallel Loops -Dr.M.Suresh Kumar
4.	OpenMP Loop Scheduling and Synchronization -Dr.Deepak Tripathi
5.	OpenMP Tasking: Recursive Algorithm -Dr.Sumit K singh
6.	NUMA Effects and Bandwidth Measurement -Dr.Manike Chiranjeevi
7.	OpenMP SIMD Vectorization -Dr.Rahul Mishra
8.	OpenMP Performance Analysis and Hotspot Detection-Mrs.G.Neelima 
9.	MPI: Hello World and Send/Receive-Dr.N.Sharmila Banu 
10.	MPI Point-to-Point: Blocking Communication Patterns -Dr.Jamalaiah
11.	MPI Point-to-Point: Non-Blocking Communication -Overlap -Dr.K.Deepa
12.	MPI Collectives: Broadcast, Scatter, Gather-Dr.Sajal Mondal
13.	MPI Collectives: Reduction and Scan -Dr.Hitesh Kumar
14.	MPI Derived Datatypes -Dr.Sriraman Kothuri
15.	Hybrid MPI+OpenMP Programming -Dr.Durgesh Nandan
16.	MPI Performance Analysis and Profiling -Dr.M.Suresh Kumar
17.	CUDA/OpenMP Offload: Vector Addition-Dr.Sumit K Singh 
18.	CUDA/OpenMP Offload: Host-Device Data Transfer -Dr.Deepak Tripathi
19.	CUDA Shared Memory / OpenMP Offload Optimization-Dr.Sajal Mondal
20.	GPU Performance Analysis -Dr.G.Neelima
21.	Performance Modeling: Roofline Analysis-Dr.K.Deepa 
22.	Parallel I/O Introduction -Dr.N.Sharmila Banu
23.	Cloud HPC -Dr.Manike Chiranjeevi
24.	Containerization for HPC-Dr.Hitesh Kumar
