#Flags at the beginning of every job to submit to TSCC.
Fill in -N [name], -e [stderr file] -o [stdout file]

```
#!/bin/bash
#PBS -q hotel
#PBS -N 
#PBS -V
#PBS -e 
#PBS -o 
#PBS -l nodes=1:ppn=8
#PBS -l walltime=0:10:00
```

#submit a job to TSCC
```
qsub [file]
```

#check job status
```
qstat -u ucsd-train18
```
alias was set up on the profile
```
qme
```
