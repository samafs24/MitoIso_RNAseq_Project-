# External Data Downloads for This Project

This file lists all large or external data files required for this project, along with direct download commands using `wget` or `curl`.

These files are not stored in the repository due to their size or licensing.

---

1. 🔹 GENCODE v47 GTF annotation file

- 📄 Filename: gencode.v47.annotation.gtf
- 📥 Download:

Using wget:
wget https://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_47/gencode.v47.annotation.gtf.gz

Using curl:
curl -O https://ftp.ebi.ac.uk/pub/databases/gencode/Gencode_human/release_47/gencode.v47.annotation.gtf.gz

Then unzip:
gunzip gencode.v47.annotation.gtf.gz

Move to the data directory:
mv gencode.v47.annotation.gtf data/

---

2. 🔹 GTEx v10 Transcript Expected Counts

- 📄 Filename: GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt
- 📥 Download:

Using wget:
wget https://storage.googleapis.com/adult-gtex/bulk-gex/v10/rna-seq/GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt.gz

Using curl:
curl -O https://storage.googleapis.com/adult-gtex/bulk-gex/v10/rna-seq/GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt.gz

Then unzip:
gunzip GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt.gz

Move to the data directory:
mv GTEx_Analysis_v10_RSEMv1.3.3_transcripts_expected_count.txt data/

---

3. 🔹 GTEx v10 Transcript TPMs

- 📄 Filename: GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt
- 📥 Download:

Using wget:
wget https://storage.googleapis.com/adult-gtex/bulk-gex/v10/rna-seq/GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt.gz

Using curl:
curl -O https://storage.googleapis.com/adult-gtex/bulk-gex/v10/rna-seq/GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt.gz

Then unzip:
gunzip GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt.gz

Move to the data directory:
mv GTEx_Analysis_v10_RSEMv1.3.3_transcripts_tpm.txt data/

---

4. 🔹 ClinVar Variant Summary (latest release)

- 📄 Filename: variant_summary.txt
- 📥 Download:

Using wget:
wget https://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/variant_summary.txt.gz

Using curl:
curl -O https://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/variant_summary.txt.gz

Then unzip:
gunzip variant_summary.txt.gz

Move to the data directory:
mv variant_summary.txt data/

