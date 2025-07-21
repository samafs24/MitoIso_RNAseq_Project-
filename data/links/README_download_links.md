# External Data Downloads for This Project

This file lists all large or external data files required for this project, along with direct download commands using `wget` or `curl`.

---

1. GENCODE v47 GTF annotation file

- Filename: gencode.v47.annotation.gtf
- Download:

Using wget:
wget https://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_47/gencode.v47.annotation.gtf.gz

Using curl:
curl -O https://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_47/gencode.v47.annotation.gtf.gz

---

2. GTEx v10 Transcript Expected Counts

- Filename: GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt
- Download:

Using wget:
wget https://storage.googleapis.com/adult-gtex/bulk-gex/v10/rna-seq/GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt.gz

Using curl:
curl -O https://storage.googleapis.com/adult-gtex/bulk-gex/v10/rna-seq/GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt.gz

---

3. GTEx v10 Transcript TPMs

- Filename: GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt
- Download:

Using wget:
wget https://storage.googleapis.com/adult-gtex/bulk-gex/v10/rna-seq/GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt.gz

Using curl:
curl -O https://storage.googleapis.com/adult-gtex/bulk-gex/v10/rna-seq/GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt.gz

---

4. ClinVar Variant Summary (latest release)

- Filename: variant_summary.txt
- Download:

Using wget:
wget https://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/variant_summary.txt.gz

Using curl:
curl -O https://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/variant_summary.txt.gz

---

5. GENCODE GRCh38 Primary Assembly Genome FASTA

- Filename: GRCh38.primary_assembly.genome.fa
- Download:

Using wget:
wget https://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_47/GRCh38.primary_assembly.genome.fa.gz

Using curl:
curl -O https://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_47/GRCh38.primary_assembly.genome.fa.gz

---

# Then unzip

gunzip gencode.v47.annotation.gtf.gz
gunzip GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt.gz
gunzip GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt.gz
gunzip GRCh38.primary_assembly.genome.fa.gz
gunzip variant_summary.txt.gz


# Move to the data directory:

mv gencode.v47.annotation.gtf data/
mv GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt data/
mv GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt data/
mv GRCh38.primary_assembly.genome.fa data/
mv variant_summary.txt data/

