This is the implementation of Block Nested Loop Join in PostgreSQL-12.0
by 彭恺欣 SID:21307140077 from Fudan University.

Check the PDF report for more detail.

## Source Code

Replace these files in the source codes of PostgreSQL-12.0:
src/backend/utils/misc/guc.c
src/include/postmaster/bg_worker.h
src/backend/include/nodes/execnodes.h
src/backend/executor/execProcnode.c

## Instructions

Set block size of BLNJ in PostgreSQL:
```bash
SET blnj_block_size = $BLOCKSIZE$;
```

If the query timing information is needed, turn it on with:
```bash
\timing
```




