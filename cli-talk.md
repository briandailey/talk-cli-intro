== draft

* talk about the 3 principles form mcelroy
* what this means: each tool multiplies the usefulness of the others you know
* less shell, more egg


* What is the shell?
    * History of the shell (who created it)
* Why should you care about it?
    * Not just "I can get around" but mastering it.
    * The philosphy behind it
    * It's wide availability
    * Each tool multiplies the usefulness of the others you know.
    * combining tools in the shell 
    * more shell, less egg! mcilroy's bash example.
* The Basics
    * getting around
    * keyboard shortcuts
    * reusing arguments and commands
    * searching through history
* Some handy tools
    * tr
    * sort
    * wc
    * uniq
    * sed & awk
    * less & more
    * cut
    * grep & ack
    * pv
    * head, tail, cat
    * find
* pipes and filters
    * stdin, stdout, and stderr
    * why is it a pipe?
    * how buffering works
    * redirects
    * risk of failure with pipes
* meta tools
    * tmux
    * vim


Thanks to the fact that the pipeline only stores what it can process in memory,
this solution is very memory-efficient and lightweight. Processing a file of
any size would not have changed the memory usage of this solution - the
pipeline runs in effectively constant space.

http://blog.petersobot.com/pipes-and-filters
