
[root@61 ~]# curl -d '{"args":["free","-m"]}' 10.10.10.61:8000    

{"returncode": 0, "stderr": "", "stdout": "             total       used       free     shared    buffers     cached\nMem:          1006        646        359          0        127        262\n-/+ buffers/cache:        256        750\nSwap:         1023          0       1023\n"}
