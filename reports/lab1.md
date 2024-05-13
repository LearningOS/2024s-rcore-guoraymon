# 编程作业
1. 在 TaskControlBlock 结构体中新增 syscall_times 和 start_time 两个字段，syscall_times 用于记录任务的 syscall 次数，start_time 用于记录任务第一次 Running 的时间。
2. 在 TaskManager 中的 run_first_task 和 run_next_task 方法更新 TaskControlBlock 的 start_time，新增 syscall_times 方法，更新当前任务的 syscall_times。
3. 在 syscall 新增 TaskControlBlock.syscall_times 的调用。
4. sys_task_info 中取到当前任务的 TaskControlBlock，取到相关数据后赋值到 TaskInfo 即可。

# 简答作业
todo：下次一定补

# 荣誉准则
1. 在完成本次实验的过程（含此前学习的过程）中，我曾分别与 以下各位 就（与本次实验相关的）以下方面做过交流，还在代码中对应的位置以注释形式记录了具体的交流对象及内容：

无

2. 此外，我也参考了 以下资料 ，还在代码中对应的位置以注释形式记录了具体的参考来源及内容：

无

3. 我独立完成了本次实验除以上方面之外的所有工作，包括代码与文档。 我清楚地知道，从以上方面获得的信息在一定程度上降低了实验难度，可能会影响起评分。

4. 我从未使用过他人的代码，不管是原封不动地复制，还是经过了某些等价转换。 我未曾也不会向他人（含此后各届同学）复制或公开我的实验代码，我有义务妥善保管好它们。 我提交至本实验的评测系统的代码，均无意于破坏或妨碍任何计算机系统的正常运转。 我清楚地知道，以上情况均为本课程纪律所禁止，若违反，对应的实验成绩将按“-100”分计。

