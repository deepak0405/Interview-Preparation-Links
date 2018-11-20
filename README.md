# Interview Preparation

### 1. Machine Learning
- **Cheat Sheet** : [Cheat Sheets for AI, Neural Networks, Machine Learning, Deep Learning & Big Data](https://becominghuman.ai/cheat-sheets-for-ai-neural-networks-machine-learning-deep-learning-big-data-678c51b4b463) 
- **Time Series** : [Window Method and stuff](https://machinelearningmastery.com/backtest-machine-learning-models-time-series-forecasting/)
- **Data Science** : [Questions with answers](https://github.com/kojino/120-Data-Science-Interview-Questions)
- **Neural Network** : [Mathematics behind nn](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.161.3556&rep=rep1&type=pdf&fbclid=IwAR2uCJKpn9ihNYRu7wjA4L0Ztslj480UzGlC5mS7ZxQhAPuu3QWz7lAV6fs)

### 2. Data Structure
- **Interval and Segment Trees** : [Interval,Segment,Range and Priority Search Tree](http://www.iis.sinica.edu.tw/~dtlee/dtlee/CRCbook_chapter18.pdf)

### 3. Company Questions
- **Company wise questions** : [Interview-Questions](https://github.com/rishabh115/Interview-Questions)

### 4. Computer Vision Awesome Links !!!
- **3D reconstruction from multiple Images** : [3d reconstruction](http://cvgl.stanford.edu/teaching/cs231a_winter1415/prev/projects/CS231a-FinalReport-sgmccann.pdf)

### 5. OS questions:
- **System and user level thread** : 
  1. [Stack overflow link1](https://stackoverflow.com/questions/14791278/threads-why-must-all-user-threads-be-mapped-to-a-kernel-thread)
  2. [Stack Overflow link2](https://stackoverflow.com/questions/15983872/difference-between-user-level-and-kernel-supported-threads/15984127#15984127)

I am still confused, but here is the summary of the answers:
1. User level thread is for user space code and kernel level thread is for kernel space code.
2. Kernel level thread is heavy weight as compared to user level due to permissions and security.
3. To execute some specific tasks involving kernel code (eg. system call) we map user level thread to the kernel level thread.
4. Linux kernel schedules a task, a task can be single threaded process, thread in a multi threaded process or kernel tasks. Clone() system call is used for creating task.

- **Environment Variables** : [ variables like $#, $!...](https://superuser.com/questions/247127/what-is-and-in-linux/247131)
- **OS Cheat Sheet** : [Dinasour Book](http://codex.cs.yale.edu/avi/os-book/OS10/study-guide/Study-Guide.pdf)
- **Mutex v/s Binary Sempahore** : [Discussion Link](http://gauss.ececs.uc.edu/Courses/c4003/extra/difference-between-semaphore-and-mutex.html)
- **I/O** : [Small tutorial](https://www.tutorialspoint.com/operating_system/os_io_hardware.htm)
### 6. Networks
- **TCP**:
  1. [Flow Control](https://www.brianstorti.com/tcp-flow-control/)
  2. [Everything about TCP](https://www.ictshore.com/free-ccna-course/transmission-control-protocol-advanced/)
