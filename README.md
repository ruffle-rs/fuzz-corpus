# Ruffle Fuzzing Corpus

This repository stores the seed corpus for Ruffle fuzz tests.

## Structure

The first directory is the name of the corpus.
Usually it's the same as the fuzz target name, as having a separate corpus for each target is optimal.

Inside the directory the structure is arbitrary, blobs should be scanned recursively.
