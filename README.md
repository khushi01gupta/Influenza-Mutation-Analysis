# Influenza-Mutation-Analysis

Tracking the Evolution of the Flu: A 10-Year Bioinformatics Study
Why I Started This Project:
Every year, we are told to get a new flu shot, but I wanted to see the actual biological reason why. I decided to use bioinformatics to "look under the hood" of the Influenza A virus and track how its genetic code changed between 2014 and 2024.

The Investigation (Methods):
I didn't need a wet lab for this; I used the same digital tools professional scientists use:

NCBI Virus Database: I hunted through thousands of records to find two specific Hemagglutinin (HA) protein sequences from the USA—one from 2014 and one from 2024.

Clustal Omega: I used this tool to align the two sequences side-by-side to "spot the differences" in their amino acid chains.

What the Data Told Me (Results):
When you look at the alignment_results.txt file in this repo, you’ll see the virus's evolution in real-time:

The Stars (*): These represent parts of the virus that stayed exactly the same over a decade.

The Blanks: These are the mutations. Every blank space is a spot where the virus successfully changed its "disguise" to try and bypass our immune systems.

Final Thoughts:
This project helped me realize that the flu isn't just one static disease—it’s a moving target. Seeing these mutations visually makes it much easier to understand why viral surveillance and updated vaccines are so critical for public health.
