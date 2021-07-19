# Relapsing-fever

Test STAR:

GenomeGenerate:

STAR --runThreadN 20 --runMode genomeGenerate --genomeDir /home/xt85/STARpractise --genomeFastaFiles /home/xt85/STARpractise/Homo_sapiens.GRCh38.dna.primary_assembly.fa --sjdbGTFfile /home/xt85/STARpractise/Homo_sapiens.GRCh38.104.gtf


kallisto quant -i /home/xt85/Relapsing_fever/Rawdata/GenomeDir/index -o output -b 100 Bc1ql3_3_013_180_S7_L001_R1_001.fastq.gz Bc1ql3_3_013_180_S7_L001_R2_001.fastq.gz
