# kmer_count
This repository contains script for analyzing correctness of plasmid assembly.

find_assembly_techno.py - Identifies the sequencing/assembly technology used for plasmid assembly
python find_assembly_techno.py <input_genbank_file> <output_file>

plasmid_kmer_median.pl - Calculates k-mer median of plasmids
perl plasmid_kmer_median.pl <fasta_file> <output_file>
