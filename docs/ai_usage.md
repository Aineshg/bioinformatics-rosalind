Tool/model & version: GPT-5 Mini , Claude , Gemini

What I asked for: Python code to compute GC-content from FASTA strings

Snippet of prompt(s): “Given at most 10 DNA strings in FASTA format… Return the ID with highest GC-content.”
1. RNA Transcription

Snippet of prompt: “Given a DNA string t of length at most 1000 nt, return the transcribed RNA string by replacing all 'T' with 'U'.”

2. Protein Translation

Snippet of prompt: “Given an RNA string s of length at most 10 kbp, return the protein string encoded by s using the standard RNA codon table.”

3. Word Count in a String

Snippet of prompt: “Given a string s, return the number of occurrences of each word in s, where words are separated by spaces. Words are case-sensitive.”

What I changed before committing: Adjusted code to handle multi-line FASTA input and calculate GC% correctly

How I verified correctness: Tested with Rosalind sample dataset, output matched expected result
