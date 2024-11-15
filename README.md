# File-Compressor
The File Compressor project is a utility tool built entirely in C++ to compress text files. It aims to minimize storage requirements and optimize file transmission by encoding data efficiently.

1. Data Compression Algorithm:

Implements Huffman Coding, a popular lossless data compression algorithm, to reduce file size without losing any information.
Binary trees are used to generate prefix codes based on character frequencies.

2. File Handling:

Reads plain text files as input and processes them into a compressed binary format.
Supports decompression, allowing users to restore the original file from the compressed data.

3. User Interface:

Command-line interface for specifying input files, choosing compression or decompression modes, and viewing output.
Displays compression ratio and file size savings after processing.

4. Applications:

Reducing storage for archival text data.
Optimizing file transfer over networks.
