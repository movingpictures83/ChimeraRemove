# ChimeraRemove
# Language: R
# Input: RDS
# Output: PREFIX
# Tested with: PluMA 1.1, R 4.0.0
# dada2_1.18.0

Remove chimeras from a set of sequences.

The plugin takes as input an R object of merged sequences, as a list.

It will output the same sequences with all chimeras removed, and also as a table of sequences, using the user-specified prefix:
prefix.merger1.rds: Merged sequences
prefix.seqtab.rds: Sequence table
