# BPE-Implementation-with-Multilingual-Support
This project contains a Byte Pair Encoding (BPE) implementation along with scripts for training and building a vocabulary across multiple languages. The focus is on providing language processing capabilities in English, Lithuanian, French, Italian, and Latin

Files:

1. bpe.py:

This script contains the implementation of the BPE algorithm, which tokenizes text and builds vocabulary for the specified dataset. It includes functionality for passing file paths as command-line arguments.

2. languages.txt:
A text file listing the supported languages for the project:
English
Lithuanian
French
Italian
Latin​(languages).

3. main.py:

This script drives the main execution of the BPE algorithm, handling data preprocessing and invoking the BPE tokenizer.

Instructions:

To Train BPE: Run the BPE script with the following command:

python3 bpe.py --train "<path_to_text_file>"

