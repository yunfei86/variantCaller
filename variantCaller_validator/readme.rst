Validate Variant Caller
=============================

1. prerequisites. - NO need anymore
-------------
1) bamtools - "https://github.com/pezmaster31/bamtools/wiki/Building-and-installing"
2) cmake


2. create truth file.
-------------
1) Latest truth file locate at "/results/plugins/validateVariantCaller/files/"
2) They are SNP and indel separated, while validator takes merged truth file, therefore we need to merge them (cat file1.bed file2.bed > comb.bed)
3) Before merging, find needed SNP and indel truth files at "https://iontorrent.jira.com/wiki/display/TS/TVC+Regression+Test+-+Reference+Page"


3. command.
-------------


-  Set truth file::

    $ #germline data takes one truth file
    $ TRUTH_FILES="-t ${MAJOR_TRUTH_FILE}"
    $ #Somatic data takes two truth files
    $ TRUTH_FILES="-t ${MAJOR_TRUTH_FILE} -T ${MINOR_TRUTH_FILE}"


-  Import bamtools library::

    $ BAM_TOOLS=./bamtools
    $ export LD_LIBRARY_PATH=${BAM_TOOLS}


-  Start Validator::

    $ variantValidator_multi 
    $ -i "${VARIANT}" 
    $ -F "${VARIANT_filtered}" 
    $ -b ${INPUT_BAM} 
    $ -r ${REF_FILE} 
    $ ${TRUTH_FILES} 
    $ -o ${OUT_FOLDER
    
    
    
4. Install required library for CentOS.
-------------

Error msg::
    /home/liy15/test/variantCaller/variantCaller_validator/variantValidator_multi \
    >    -i "${OUT_FOLDER}/${OUT_NAME}.vcf" \
    >    -F "${OUT_FOLDER}/${OUT_NAME}_filtered.vcf" \
    >    -b ${INPUT_BAM} \
    >    -r ${REF_FILE} \
    >    ${TRUTH_FILES} \
    >    -o ${OUT_FOLDER}
    /home/liy15/test/variantCaller/variantCaller_validator/variantValidator_multi: /usr/lib64/libstdc++.so.6: version `GLIBCXX_3.4.11' not found (required by /home/liy15/test/variantCaller/variantCaller_validator/variantValidator_multi)
    /home/liy15/test/variantCaller/variantCaller_validator/variantValidator_multi: /usr/lib64/libstdc++.so.6: version `GLIBCXX_3.4.9' not found (required by /home/liy15/test/variantCaller/variantCaller_validator/variantValidator_multi)
    /home/liy15/test/variantCaller/variantCaller_validator/variantValidator_multi: /lib64/libc.so.6: version `GLIBC_2.7' not found (required by /home/liy15/test/variantCaller/variantCaller_validator/bamtools/libbamtools.so.2.2.2)
    /home/liy15/test/variantCaller/variantCaller_validator/variantValidator_multi: /usr/lib64/libstdc++.so.6: version `GLIBCXX_3.4.11' not found (required by /home/liy15/test/variantCaller/variantCaller_validator/bamtools/libbamtools.so.2.2.2)
    /home/liy15/test/variantCaller/variantCaller_validator/variantValidator_multi: /usr/lib64/libstdc++.so.6: version `GLIBCXX_3.4.9' not found (required by /home/liy15/test/variantCaller/variantCaller_validator/bamtools/libbamtools.so.2.2.2)
    
Solution:
1) /lib64/libc.so.6 - http://blog.csdn.net/iomato/article/details/8462768
2) /usr/lib64/libstdc++.so.6 - http://stackoverflow.com/questions/7150409/libstdc-glibcxx-version-errors
