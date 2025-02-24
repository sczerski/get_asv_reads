# get_asv_reads
Function to pull out all of the reads that make up an ASV produced from the DADA2 pipeline

This is not actually a function yet, but you can use it easily. This took me a while to figure out how to do this, but it was necessary for me to 
understand the reads which composed a given ASV. I hope this makes your life a little easier!

# Required Data
Objects generated from the DADA2 pipeline. The dd2 (denoised) object and the drp (dereplicated) object.

All of the objects here (e.g. dd2, drp) are objects assigned during the DADA2 pipeline. These are the names for the objects that they used, and these are the names that I have stuck with since running the pipeline. Please change these objects to what you have named them. I don't believe any packages are required for this code, but of course you will have need to run DADA2 through the denoise step in the pipeline to successfully use this tool. Let me know if you run into any problems!!!
