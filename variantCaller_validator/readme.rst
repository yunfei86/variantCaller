Validate Variant Caller
=============================

1. create truth file.
-------------
1) Latest truth file locate at "/results/plugins/validateVariantCaller/files/"
2) They are SNP and indel separated, while validator takes merged truth file, therefore we need to merge them (cat file1.bed file2.bed > comb.bed)
3) Before merging, find needed SNP and indel truth files at "https://iontorrent.jira.com/wiki/display/TS/TVC+Regression+Test+-+Reference+Page"


2. command.
-------------
-  Set truth file
    $ #germline data takes one truth file
    $ TRUTH_FILES="-t ${MAJOR_TRUTH_FILE}"
    $ #Somatic data takes two truth files
    $ TRUTH_FILES="-t ${MAJOR_TRUTH_FILE} -T ${MINOR_TRUTH_FILE}"

-  Start Validator
    $ variantValidator_multi 
    $ -i "${VARIANT}" 
    $ -F "${VARIANT_filtered}" 
    $ -b ${INPUT_BAM} 
    $ -r ${REF_FILE} 
    $ ${TRUTH_FILES} 
    $ -o ${OUT_FOLDER

- tmp
    $ perl  robust_peak_pair_stats.pl -h
    $ Options: -i <path1>     path to the folder with index files [accepted index file extensions, idx, tab]. 
    $          -d <path2>     path to the folder with S_*.gff and O_* files.   
    $          -g             organism, sg07=>yeast, mm09=>MouseV9, mm08=>MouseV8, hg18=>human18, hg19=>human19, dm03=>Drosophila
    $          -s            size of genome[optional] In case of other genomes, set -g as NA and -s as the size of genome (see ex. below)
