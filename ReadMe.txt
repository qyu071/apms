Usage:APMS.exe [options]

An efficient algorithm for solving q-pms problem.


[options]

-f f: input-file path

-L L:  motif length

-d d:  maximum number of mismatches between a motif and its instance
  
-q q:  proportion of the input sequences containing motif instances

-g g:  the probability of mutation at each location


examples: APMS.exe -f I:\motif_data\zfx.txt -L 13 -q 0.5 -g 0.5 -d 4


The results will showed in an automatically created file  "result.txt" .