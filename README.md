## DiphtoDocker

Docker container for the [dipthOscan](https://bigsdb.pasteur.fr/news/diphtOscan/) tool 

# Requirements
You just need Docker installed in your computer.

# Running DiphtoDocker
Gather all the fasta files from *Corynebacterium spp* that you want to analyze in a folder. Open a terminal in the folder and run the following command:   
<code>docker run -it --rm -v $(pwd):/Data ghcr.io/garcia-nacho/diphtoscan</code>   

