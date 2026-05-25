# nabi_primary_transcript
some adjust make the script adapt to more situations

## Intro
The original script only work for zip files, in this changed script, you can give it a dir which contains the gff file and protein fasta file.

## Quick start
### For zip file
Run:
python ncbi_primary_transcripts.py --zip_file 1
### For dir
Run:
python ncbi_primary_transcripts.py --input dir/to/your/files
** the output file will present in primary_transcripts dir and named by the dir name that yo insert, in the example, the out put filename will be "files"
