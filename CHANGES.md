v0.0.3
======
+ fix bug when annotatign multi-sample vcf (brentp/duphold#2)
+ get sample name from bam read group info. **NOTE** that this changes the command line parameters by removing the `--sample` argument.