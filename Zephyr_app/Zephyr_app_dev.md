# Zephyr RTOS: Application development

	The previous blog considered general issues related to Zephyr RTOS. This part moves further and deals with application development process in more detail. 

	Being the Linux Foundation project Zephyr naturally inherits its best development features and tools:

    • established infrastructure for existing platforms compilation with simple extension tools

    • powerful drivers development tool based on device tree structure approach

    • flexible and orthogonal configuration

    • easy IDE and Python integration, powerful command line tool

    • POSIX compatible API

It is also worth mentioning that:

    • Since Zephyr supports very large number of boards it naturally uses cmake software building tool which is intrinsically cross-platform and compiler independent

    • Zephyr uses its own command line tool called west. This meta-tool provides a multiple repository management system, makes configuration simpler and apart from its own built-in commands it also allows adding custom commands. This makes west quite flexible and powerful. West is used for building, flashing and debugging applications. However, it is not obligatory for Zephyr development

    • Zephyr extensively uses Python 3 and its package manager for installing and running scripts used to compile, build, and run applications.
