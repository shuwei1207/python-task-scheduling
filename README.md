# python-task-scheduling

Tasks 1,2,…,m and Jobs 1,2,…,n are to be processed on a single machine (So, we have m+n positions on the machine)
• Task is characterized by processing time ti.
• Job jis characterized by processing time pj and weight wj.
• For task i, Ji is the set of jobs that can start only when task jis finished.
• For job j, Tj is the set of tasks that must precede the start of job j.
• The supporting relation is presented as a bi-partite graph.
• At any time, the machine can perform at most one task or one job.
• A schedule is feasible if the precedence constraints are observed.
• The problem is to determine a schedule.
