# ont-merge

This script is designed to merge fastq files from an ONT sequencing run. It consolidates files based on their barcodes, placing them into a unified directory called "merged".

This is coming from a need to make sure I can track all of my diagnostic sequencing data and reducing one more step of navigating to directories to do this. Anything that I can let a computer do will make our auditors much happier because we are no longer having to be human scanners.

Feel free to send me a message to suggest any changes or ideas to streamline this process of tracking sequencing data for diagnostics.

It seems like merging .fast5 files for research might be of a similar code structure, but for now this is only for cat-ing .fastq.gz files.
