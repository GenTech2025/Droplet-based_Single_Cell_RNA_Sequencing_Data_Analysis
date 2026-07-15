```bash
mkdir -p fastqc_results
fastqc -t 2 -o ../results/fastqc_results/ *.fastq.gz
```

```bash
multiqc -o ../results/multiqc_results ../results/fastqc_results
```