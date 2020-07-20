Creates merge request by current branch, last commit message uses as MR title, squash commits enabled by default\
Usage: mr [-m] [-s] assignee_id\
Examples:\
mr          opens mr into devel, assignee_id=198 (by default)\
mr -m 234   opens mr into master, assignee_id=234\
mr -s 234   opens mr into devel, squash disabled
