Validate Variant Caller
=============================

1. create truth file. 
-------------
1) Latest truth file locate at "/results/plugins/validateVariantCaller/files/"
2) They are SNP and indel separated, while validator takes merged truth file, therefore we need to merge them (cat file1.bed file2.bed > comb.bed)
3) Before merging, find needed SNP and indel truth files at "https://iontorrent.jira.com/wiki/display/TS/TVC+Regression+Test+-+Reference+Page"


2. command.
-------------
1) Set truth file
#germline data takes one truth file
    TRUTH_FILES="-t ${MAJOR_TRUTH_FILE}"
#Somatic data takes two truth files
    TRUTH_FILES="-t ${MAJOR_TRUTH_FILE} -T ${MINOR_TRUTH_FILE}"

2) Start Validator
    variantValidator_multi \
    -i "${VARIANT}" \
    -F "${VARIANT_filtered}" \
    -b ${INPUT_BAM} \
    -r ${REF_FILE} \
    ${TRUTH_FILES} \
    -o ${OUT_FOLDER
