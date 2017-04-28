# Jungle
notepad
top

top 可以简单的查询Cpu的基本使用情况

Usage: top[ -m max_procs ] [ -n iterations ] [ -d delay ] [ -s sort_column ] [ -t ] [ -h]

   -m num  Maximum number of processes to display.

   -n num  Updates to show before exiting.

   -d num  Seconds to wait between updates.

   -s col  Column to sort by (cpu，vss，rss，thr).

   -t      Show threads instead of processes.

   -h      Display this help screen.

注意的是top的CPU% 是按全部CPU 来计算的，如果以单线程来计算，比如当时有开启4个核心，那么最多吃到25%。 

个人常见的操作方式如:  top -t -m 5 -n 2
