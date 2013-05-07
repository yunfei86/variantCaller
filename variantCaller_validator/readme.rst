Last login: Mon May  6 16:03:23 on ttys010
liy15@yunfei [16:45:28]
~ $ ls
Applications   Google Drive   Public         code_svn       test.sh
Desktop        Library        VMs            git            tools
Documents      Movies         VirtualBox VMs igv
Downloads      Music          bin            lib
Dropbox        Pictures       code           test
liy15@yunfei [16:45:40]
~ $ fanta
Linux fanta 2.6.32-21-server #32-Ubuntu SMP Fri Apr 16 09:17:34 UTC 2010 x86_64 GNU/Linux
Ubuntu 10.04.4 LTS

Welcome to the Ubuntu Server!
 * Documentation:  http://www.ubuntu.com/server/doc

43 packages can be updated.
35 updates are security updates.

Last login: Mon May  6 15:44:49 2013 from 10.45.17.234
ionadmin@fanta:~$ ls
R  small_variants.vcf
ionadmin@fanta:~$ exit
logout
Connection to 167.116.6.194 closed.
liy15@yunfei [16:45:49]
~ $ jagger
liy15@167.116.6.155's password: 
Last login: Fri May  3 13:57:06 2013 from 10.43.64.73
Rocks 5.4.3 (Viper)
Profile built 23:06 10-Oct-2012

Kickstarted 17:02 10-Oct-2012
[liy15@jagger ~]$ ls
bio  framework    go  testme
[liy15@jagger ~]$ cd ../iruser/
[liy15@jagger iruser]$ ls
1
167.116.6.182
3d5b73f8013d5bb284a80107_NA12892_Mother_27f4861b3d5b73f8013d5bb2844d00a4_2
7_mar.sql
activemq-data
amazon
analysistable
anant
archive
a.tsv
autoIRInstall16.sh
bio
CPD_test.vcf
createdon
csmanager
cytoBand.txt
davidp
dayu
dump14Ash.sql
Fan
find:
foobar~
GDS_rajesh
hg19_alias.tab
hg19_v12.genome
install
IonReporterManager16Installation.log
IR1.6Installer
KeplerData
liy15
missing_header.sql
nami
notallowed
notnull
notnull~
notnulldate
notnulldate~
null
null~
nulldate
nulldate~
nullname
Pras
property.txt
R_2013_02_17_12_04_23_user_F5--214--R32962
refGene.txt
s27f4861b3ccf9437013ccf9afc4e0032_27f4861b3ccf9414013ccf9c26de0003.tsv
Shiva
Sonal
sources16_0122_IR16.tgz
sources16_0213_IR16.tgz
sources16_0227_IR16.tgz
sources16_0318_IR16.tgz
sources16_0417_IR16.tgz
src.txt
srikanth
test
tmp
TS
Vidya
vivien
work
[liy15@jagger iruser]$ cd csmanager
[liy15@jagger csmanager]$ ls
cmpath
[liy15@jagger csmanager]$ ./cmpath 
CaseManager Environment is set ..
[liy15@jagger csmanager]$ ls
cmpath
[liy15@jagger csmanager]$ pwd
/home/iruser/csmanager
[liy15@jagger csmanager]$ more cmpath 
cd /gs1/VV/results1/RegressionDriver/CaseManager/tools
. ./caseManagerPath
[liy15@jagger csmanager]$ cd /gs1/VV/results1/RegressionDriver/CaseManager/tools
[liy15@jagger tools]$ ls
#00_toolsIndex.txt#		   cmgetNextNightlyBuild2.5.CTS			       fetchLogs					       printStringencyTable.pl
00_toolsIndex.txt		   cmgetNextNightlyBuildForNightlyLoop		       ff						       pwdClean
01_template_tool_validate.pl	   cmgoto					       fieldAverage.sh					       pwdThis
03_maintainanceScratch.txt	   cmgotobioscope				       fileContent_validate2.pl				       QC_protocol_resultValidationScript.pl
2				   cmgotoPluginXmlDir				       fileContent_validate_jose2011.bak.pl		       qcValidation_IR.pl
3rdParty			   cmhaveLatestBuild				       fileContent_validate.pl				       qv_ascii2int.pl
abdig				   cminput					       fileContent_validate.pl.containsRecursiveChecks	       qv_int2ascii.pl
addSuffixToLinkAndOriginal	   cmisServerRunning				       fileContent_validate.pl.jose.bak.beforeRecursiveChange  random_sequence_picker.pl
[alignment is not primary,	   cmjmoap					       fileContent_validate.pl.suspicious		       [read fails quality check],
AllRecordsIsPrimary.pl		   cmlogCheckEndBuild01				       findAFreePort.pl					       [read is paired,
AlnLenCalc.jar			   cmlogCheckEndVm01				       findAverageQvForUnmappedBeads.pl			       [read is PCR or optical duplicate],
a.txt				   cmlogCheckStartBuild01			       findException.sh					       [read is unmapped],
backup_dirContent_validate.pl	   cmlogCheckStartVm01				       [first read in pair],				       readme.txt
backup.extractTagsForMerge.pl	   cmlogWatchBuild01				       fragmentMapping.rrs				       readSplittingCheck.pl
backup.mergeSortTags.pl		   cmlogWatchvm01				       fvi						       readsSplitter.sh
bam2sam				   cmmapreadsPerf				       fview						       referenceBaseCount
bamHeaderValidator.sh		   cmmatchFindAllLinksTo			       generateReadmeInFolder.pl			       referenceProperties
bamToContigs.sh			   cmnightly					       getBeadDensity.pl				       renameRPMResults.sh
bamToCsfasta.jar		   cmpluginProperties				       getCigarString.sh				       repointLinkFromTo
bamtosff_blocks.pl		   cmpQVinSam.pl				       GetConsensusCoverage.jar				       Reseq_Compare13v20.pl
BamToXSQ.sh			   cmps						       getCountOfBeadsWithAverageQvGreaterThan.pl	       [reverse strand,
bamvalidation.jar		   cmqstat					       getFileProperties				       robustintersection.verbose
bam_validation_log		   cmrebaselineThisCase				       getFormattedTimeDiff				       runLogScratch.sh
bamValidationTool_SOLiD_ION.jar    cmreference					       getFromBuildMachine.sh				       runLscopeAnalysis.pl
bamValidator			   cmremoveFromPath				       getFromVMBuildMachine.sh				       runLscope.pl
bamValidator.cpp		   cmreports					       getGffPositionErrors.pl				       sam2bam
bamValidatorREADME		   cmresults					       getHostIP					       sam2bam.out
barcodeExtractPreTestInfo.sh	   cmroot					       getInstrumentsFromDiscoLog			       samFieldSorter.pl
barcodeInputIntegrityCheck	   cmroot.bak					       getLocalScore.pl					       sampling_csfasta_by_panel
barcodeOutputIntegrityCheck	   cmroot.era2					       getLogs.sh					       sampling_csfasta_by_panel.c
bedValidator			   cmrootLatestNightly				       getPatternCounts.pl				       sampling_csfasta_by_ratio
bgExec.sh			   cmrunning					       getPositionErrorFreqInCycle.pl			       sampling_csfasta_by_ratio.c
bioscope.conf			   cmsan4.sh					       getProgressiveThroughputsFromLog.pl		       samtools
bioscopeConfigUpdater		   cmsan_nohup					       getQvByTag.pl					       scanBarcodeXml.pl
biowrap				   cmsan.sh					       getRecordsByBeadId.pl				       schemeCheck.pl
biowrap10			   cmshowLatestGoodBuild			       getSelectiveBeadsFromUnmappedBAM.pl		       scratch.txt
biowrap10.5			   cmstatus					       getStableMapReadsBuild				       scriptsTC
biowrap11			   cmsuites					       getStringency.pl					       secondary_analysis
biowrap12.before_f_optionchange    cmsvnRemove.sh				       getSubRefByIndex.pl				       Secondary_Common_Testing_Scripts
biowrap14			   cmtools					       getUnmappedBAMFromMappedBAM.pl			       [second read in pair],
block_uploader_simulator.pl	   cmusage					       gff2bam.sh					       selectQvForGivenMaFile
calulateModuleTime.pl		   cnv_affected_genes_validation.pl		       gffToBam						       separateContigs.pl
caseManagerPath			   cnvPvalCheck.pl				       gff_utils					       serverSideLogs
caseManager.pm			   cnvReportedSegments1.pl			       graphGen.pl					       setNightlyTestBuild
caseManager.pm.jose.backup	   cnvReportedSegments_old.pl			       hideLastLines					       sff2fastq
caseManagerSystemRequirements.sh   cnvReportedSegments.pl			       images						       SFF_Extract
caseManagerUtilities.pm		   cnvReportedSeg_sneha.pl			       imap_fasta2match.pl				       sff_info
caseManagerWa.pm		   CNV_validateSeqments_vcf.pl			       instrumentDataScan_1				       sfr2_nohup
caseManagerWa.pm.bak		   color_to_base_seq.pl				       instrumentDataScanBeadCount			       sfr2.sh
caseManagerWa.pm.bak.jose	   columnsToKeyValuePair.pl			       instrumentDataScanFocalMapMedian			       sfr_nohup
cf				   compareFiles.sh				       instrumentDataScanFocalMapMedianLocal		       sfr.sh
changeExtensions.sh		   ComparisonOfWorkflowRuns			       javascripts					       shortTermTools
checkFailOutput.pl		   compUniqPrimaryVsAllAlignmnets.pl		       jblock						       showCommanLineOption.pl
checkMultiAnchorFromLog.pl	   concurrent_run_launcher.sh			       jcompile.sh					       showstats.py
checkNumOfIterations.pl		   concurrent_run_monitor_new.pl		       jingValidate_CIGAR_length_Frag_LMP.pl		       simulateContigs.pl
checkPassOutput.pl		   concurrent_run_monitor.pl			       jpblock						       smallIndelPathUpdate.sh
checkUnKilledBioscopeProcesses.sh  concurrent_workflows_launcher.pl		       jrun.sh						       sortByBeadIDs.sh
classifyMaByHits.pl		   convert_color_to_base_seq.pl			       jtools						       splitFastaToContigs.pl
CleanScratch			   convertToCoordsLatest			       killPBSJobs.sh					       split_var2snp_indels_mnv_vcf.py
cm1autoStart			   countBaseErrors.pl				       killServer.pl					       src
cm1autoStart_nohup		   countPattern.sh				       largeIndelPathUpdate.sh				       ssh-keyPush
cm2autoStart			   coverageResultValidator.jar			       launchAnalysises.pl				       ssh-keyPush.old
cm2autoStart_nohup		   cphere					       launchClients.pl					       subtractMappedReads.pl
cm2backup			   cpthere					       launchServer.pl					       tempTools1
cm2baseline			   createMergedBam.sh				       ldir						       tertiary_analysis
cm2cases			   createNupdateCases.sh			       ldirs						       test
cm2completelyStopANightlyTest	   createSqf.pl					       lfile						       testCaseCreationAndUpdation.pl
cm2goto				   createWorkflowTestCases.pl			       lfiles						       testCaseCreationAndUpdation_tmap.pl
cm2input			   csfastaToXSQ					       lib						       timeParser
cm2makeNewSuite			   csfasta_validation.pl			       library_xsq					       Time_Reporter.pm
cm2nightly			   csmanager					       linesFrom					       tmapbam
cm2results			   csmgr					       listFilesAndContents				       Tmap_TS_IR_Parity.sh
cm2status			   csmgrLocation				       ListScratch					       todays
cm2suites			   DatasetColorEncoding.sh			       localmapCounts.sh				       todaysTime
cm3baseline			   decode_All_XSQ_Index_reads_to_ColorQuality.pl       localVsProgressive.sh				       toolData
cm3bugs				   decode_All_XSQ_Index_reads_to_ColorQuality.sh       log						       toolData_era2
cm3bugsFrag			   decode_All_XSQreads_to_BaseQuality.pl	       log_extract.sh					       toolData_era3
cm3cases			   decode_All_XSQreads_to_BaseQuality.sh	       logScratchExtract.sh				       toolData_era5
cm3input			   decode_All_XSQreads_to_ColorQuality_ASCII.pl        logScratch.sh					       trimReadLength.pl
cm3makeNewSuite			   decode_All_XSQreads_to_ColorQuality_ASCII.sh        maConsolidator.sh				       updateCoronaVersionFile
cm3results			   decode_All_XSQreads_to_ColorQuality_barcoded.sh     MainTemplateXSQ.java				       updateFrameWork.sh
cm3suites			   decode_All_XSQreads_to_ColorQuality.sh	       maintenance					       updateJars.sh
cm4baseline			   decodeColorCallQV.pl				       mappedBeadCount.sh				       updateMe.sh
cm4bugs				   decode_samflags.pl				       [mapped in proper pair,				       update_testcases.pl
cm4cases			   decode_Start_End_XSQreads_to_ColorQuality.sh        mappingValidator					       upload.sh
cm4input			   decode_XSQreads_to_ColorQuality.pl		       matchAndLinkTestInputsAutomatically		       ValidateBAM.jar
cm4makeNewSuite			   deleteOldArchieve.py				       matchGatherCheck.pl				       Validate_CIGAR_length_Frag_LMP.pl
cm4results			   deleteOldBioscope.py				       matchingCounts.sh				       Validate_CIGAR_length_PE.pl
cm4suites			   deleteOldCorona.py				       matchingStatistics.sh				       Validate_Indels_in_CIGAR.pl
cm5baseline			   deleteOldLifescope.py			       matchKnownTestInput				       validate_reads_in_csfasta_BCXSQ_Frag.sh
cm5bugs				   derby.log					       matchKnownTestInput2				       validate_reads_in_csfasta_XSQ_Frag.sh
cm5cases			   devLicenses					       matchThroughputCheck.pl				       validate_reads_in_csfasta_XSQ_LMP_PE.sh
cm5input			   dicerBackup					       [mate is reverse,				       validate_reads_in_fastq_XSQ_Frag.sh
cm5makeNewSuite			   DiffBam.jar					       [mate is unmapped],				       validate_reads_in_fastq_XSQ_LMP_PE.sh
cm5results			   diffGFF					       matesReportGatherCheck.pl			       validateRoc.pl
cm5suites			   diffKeyValueFiles.jose.pl			       mc						       ValidateRunMetada_fastq_XSQ.sh
cmabortOff			   diffKeyValueFiles.pl				       mergeSortTags.pl					       ValidateRunMetada.sh
cmabortOn			   diffMatch					       missingTagIDCheck.pl.bak1			       validateTiTvRatio.pl
cmarchive			   diffSingleRead				       missingTagIDExtract.pl				       VariantsReported.pl
cmarchive.Orig			   diffSingleRead.bak				       moduleTimings.pl					       vcf2gvcf_v2.py
cmautoStart			   diffWoComment				       monitoredRun					       VcfStats
cmautoStart_nohup		   dirContent_validate5.pl			       monitorNodes					       verifyScheme
cmbackup			   dirContent_validate.pl			       monitorTimeOnly					       verifyStep
cmbaseline			   dirContent_validate.pl.backup.beforesamFieldSorter  mqv2ma.pl					       ViewStatus
cmbuildFlags			   duHere					       mqvFiltering.pl					       waitForAPID
cmbuildlist			   dvi						       mvthere						       waitForPbsJobComplete.pl
cmbuildlistvm			   encodeSequence.pl				       mytestcheckin					       waitForPBSSession
cmbuildMachine			   encodeSequence.pl~				       nightlyTestAutomationScripts			       waitForPBSStatus
cmcases				   EnrichmentValidationTool.jar			       NumReadsPassed.sh				       whatsinvv
cmcompletelyStopANightlyTest	   Error.txt					       outdated_scripts					       whichBioscope
cmCopyToBugs			   examine_beadBoundariesOfMaToBamSplits.sh	       pairingCategory_validate.pl			       which_workflow.pl
cmdataStorage			   examineLogsForDuration.sh			       pairing.dat_validate.pl				       workflow_mon.pl
cmfr_nohup			   extract_all_groups.sh			       parseOutput.pl					       workflow_runner_custom.sh
cmfr.sh				   extractBeadCounts				       parse_test_V1_F3.stats.txt.pl			       workflow_runner.sh
cmgetBuildCoreTool		   extract_main_info_fastq_converted_XSQ.sh	       perfDataAverage.pl				       workflows_launcher.pl
cmgetCorrectedLink		   extract_main_info_XSQ.sh			       perfHtmlGen.pl					       workflows_suite_updater.pl
cmgetLatestBuild		   extractQVFileSubSet.pl			       perfLogParser.pl					       workflow_stats.pl
cmgetLatestBuild2.0		   extractReadsFromMappedSam.pl			       perfMakeCharts.pl				       WT_Alignments.pl
cmgetLatestBuild2.1		   extractTagsForMerge1.pl			       picard						       WT_Compare13v20.pl
cmgetLatestBuildCP		   extractTagsForMerge.pl			       picard-tools-1.08				       wtCountResultValidator.jar
cmgetLatestNightlyBuild		   extract_XSQ_ids_barcoded.sh			       pipelineModuleTimingsFromLogs.sh			       xsqconvert
cmgetLatestNightlyBuild2.0	   extract_XSQ_Index_read_ids.sh		       pluginXmlFix.sh					       XSQConverter
cmgetLatestNightlyBuild2.1	   extract_XSQ_read_ids_csfasta_format.sh	       pluginXmlFix.sh.dir				       XSQ_read_extract.pl
cmgetNextNightlyBuild		   extract_XSQ_read_ids.sh			       positionErrorsGatherCheck.pl			       XSQ_Split_by_Panel.sh
cmgetNextNightlyBuild2.1	   FastqCIGAR.jar				       prepareResumeData.sh				       XSQ_Tools_for_New_ECC.tar.gz
cmgetNextNightlyBuild2.5	   fcat						       print_bam_header.jar
[liy15@jagger tools]$ mkdir variantCaller_validator
[liy15@jagger tools]$ cd variantCaller_validator/
[liy15@jagger variantCaller_validator]$ ls
[liy15@jagger variantCaller_validator]$ pwd
/gs1/VV/results1/RegressionDriver/CaseManager/tools/variantCaller_validator
[liy15@jagger variantCaller_validator]$ ls
[liy15@jagger variantCaller_validator]$ cat > readme.txt

1. create truth file. 
    1) Latest truth file locate at "/results/plugins/validateVariantCaller/files/"
    2) They are SNP and indel separated, while validator takes merged truth file, therefore we need to merge them (cat file1.bed file2.bed > comb.bed)
    3) Before merging, find needed SNP and indel truth files at "https://iontorrent.jira.com/wiki/display/TS/TVC+Regression+Test+-+Reference+Page"


2. command.
    #germline data takes one truth file
    TRUTH_FILES="-t ${MAJOR_TRUTH_FILE}"
    #Somatic data takes two truth files
    TRUTH_FILES="-t ${MAJOR_TRUTH_FILE} -T ${MINOR_TRUTH_FILE}"

    # Start Validator
    variantValidator_multi \
    -i "${VARIANT}" \
    -F "${VARIANT_filtered}" \
    -b ${INPUT_BAM} \
    -r ${REF_FILE} \
    ${TRUTH_FILES} \
    -o ${OUT_FOLDER
[liy15@jagger variantCaller_validator]$ pwd
/gs1/VV/results1/RegressionDriver/CaseManager/tools/variantCaller_validator
[liy15@jagger variantCaller_validator]$ ls
readme.txt  variantValidator_multi
[liy15@jagger variantCaller_validator]$ ls -lh
total 32K
-rw-rw-r-- 1 liy15 users  793 May  6  2013 readme.txt
-rwxr-xr-x 1 liy15 users 110K May  6  2013 variantValidator_multi
[liy15@jagger variantCaller_validator]$ cd ..
[liy15@jagger tools]$ ls
#00_toolsIndex.txt#		   cmgetNextNightlyBuild2.5.CTS			       fetchLogs					       printStringencyTable.pl
00_toolsIndex.txt		   cmgetNextNightlyBuildForNightlyLoop		       ff						       pwdClean
01_template_tool_validate.pl	   cmgoto					       fieldAverage.sh					       pwdThis
03_maintainanceScratch.txt	   cmgotobioscope				       fileContent_validate2.pl				       QC_protocol_resultValidationScript.pl
2				   cmgotoPluginXmlDir				       fileContent_validate_jose2011.bak.pl		       qcValidation_IR.pl
3rdParty			   cmhaveLatestBuild				       fileContent_validate.pl				       qv_ascii2int.pl
abdig				   cminput					       fileContent_validate.pl.containsRecursiveChecks	       qv_int2ascii.pl
addSuffixToLinkAndOriginal	   cmisServerRunning				       fileContent_validate.pl.jose.bak.beforeRecursiveChange  random_sequence_picker.pl
[alignment is not primary,	   cmjmoap					       fileContent_validate.pl.suspicious		       [read fails quality check],
AllRecordsIsPrimary.pl		   cmlogCheckEndBuild01				       findAFreePort.pl					       [read is paired,
AlnLenCalc.jar			   cmlogCheckEndVm01				       findAverageQvForUnmappedBeads.pl			       [read is PCR or optical duplicate],
a.txt				   cmlogCheckStartBuild01			       findException.sh					       [read is unmapped],
backup_dirContent_validate.pl	   cmlogCheckStartVm01				       [first read in pair],				       readme.txt
backup.extractTagsForMerge.pl	   cmlogWatchBuild01				       fragmentMapping.rrs				       readSplittingCheck.pl
backup.mergeSortTags.pl		   cmlogWatchvm01				       fvi						       readsSplitter.sh
bam2sam				   cmmapreadsPerf				       fview						       referenceBaseCount
bamHeaderValidator.sh		   cmmatchFindAllLinksTo			       generateReadmeInFolder.pl			       referenceProperties
bamToContigs.sh			   cmnightly					       getBeadDensity.pl				       renameRPMResults.sh
bamToCsfasta.jar		   cmpluginProperties				       getCigarString.sh				       repointLinkFromTo
bamtosff_blocks.pl		   cmpQVinSam.pl				       GetConsensusCoverage.jar				       Reseq_Compare13v20.pl
BamToXSQ.sh			   cmps						       getCountOfBeadsWithAverageQvGreaterThan.pl	       [reverse strand,
bamvalidation.jar		   cmqstat					       getFileProperties				       robustintersection.verbose
bam_validation_log		   cmrebaselineThisCase				       getFormattedTimeDiff				       runLogScratch.sh
bamValidationTool_SOLiD_ION.jar    cmreference					       getFromBuildMachine.sh				       runLscopeAnalysis.pl
bamValidator			   cmremoveFromPath				       getFromVMBuildMachine.sh				       runLscope.pl
bamValidator.cpp		   cmreports					       getGffPositionErrors.pl				       sam2bam
bamValidatorREADME		   cmresults					       getHostIP					       sam2bam.out
barcodeExtractPreTestInfo.sh	   cmroot					       getInstrumentsFromDiscoLog			       samFieldSorter.pl
barcodeInputIntegrityCheck	   cmroot.bak					       getLocalScore.pl					       sampling_csfasta_by_panel
barcodeOutputIntegrityCheck	   cmroot.era2					       getLogs.sh					       sampling_csfasta_by_panel.c
bedValidator			   cmrootLatestNightly				       getPatternCounts.pl				       sampling_csfasta_by_ratio
bgExec.sh			   cmrunning					       getPositionErrorFreqInCycle.pl			       sampling_csfasta_by_ratio.c
bioscope.conf			   cmsan4.sh					       getProgressiveThroughputsFromLog.pl		       samtools
bioscopeConfigUpdater		   cmsan_nohup					       getQvByTag.pl					       scanBarcodeXml.pl
biowrap				   cmsan.sh					       getRecordsByBeadId.pl				       schemeCheck.pl
biowrap10			   cmshowLatestGoodBuild			       getSelectiveBeadsFromUnmappedBAM.pl		       scratch.txt
biowrap10.5			   cmstatus					       getStableMapReadsBuild				       scriptsTC
biowrap11			   cmsuites					       getStringency.pl					       secondary_analysis
biowrap12.before_f_optionchange    cmsvnRemove.sh				       getSubRefByIndex.pl				       Secondary_Common_Testing_Scripts
biowrap14			   cmtools					       getUnmappedBAMFromMappedBAM.pl			       [second read in pair],
block_uploader_simulator.pl	   cmusage					       gff2bam.sh					       selectQvForGivenMaFile
calulateModuleTime.pl		   cnv_affected_genes_validation.pl		       gffToBam						       separateContigs.pl
caseManagerPath			   cnvPvalCheck.pl				       gff_utils					       serverSideLogs
caseManager.pm			   cnvReportedSegments1.pl			       graphGen.pl					       setNightlyTestBuild
caseManager.pm.jose.backup	   cnvReportedSegments_old.pl			       hideLastLines					       sff2fastq
caseManagerSystemRequirements.sh   cnvReportedSegments.pl			       images						       SFF_Extract
caseManagerUtilities.pm		   cnvReportedSeg_sneha.pl			       imap_fasta2match.pl				       sff_info
caseManagerWa.pm		   CNV_validateSeqments_vcf.pl			       instrumentDataScan_1				       sfr2_nohup
caseManagerWa.pm.bak		   color_to_base_seq.pl				       instrumentDataScanBeadCount			       sfr2.sh
caseManagerWa.pm.bak.jose	   columnsToKeyValuePair.pl			       instrumentDataScanFocalMapMedian			       sfr_nohup
cf				   compareFiles.sh				       instrumentDataScanFocalMapMedianLocal		       sfr.sh
changeExtensions.sh		   ComparisonOfWorkflowRuns			       javascripts					       shortTermTools
checkFailOutput.pl		   compUniqPrimaryVsAllAlignmnets.pl		       jblock						       showCommanLineOption.pl
checkMultiAnchorFromLog.pl	   concurrent_run_launcher.sh			       jcompile.sh					       showstats.py
checkNumOfIterations.pl		   concurrent_run_monitor_new.pl		       jingValidate_CIGAR_length_Frag_LMP.pl		       simulateContigs.pl
checkPassOutput.pl		   concurrent_run_monitor.pl			       jpblock						       smallIndelPathUpdate.sh
checkUnKilledBioscopeProcesses.sh  concurrent_workflows_launcher.pl		       jrun.sh						       sortByBeadIDs.sh
classifyMaByHits.pl		   convert_color_to_base_seq.pl			       jtools						       splitFastaToContigs.pl
CleanScratch			   convertToCoordsLatest			       killPBSJobs.sh					       split_var2snp_indels_mnv_vcf.py
cm1autoStart			   countBaseErrors.pl				       killServer.pl					       src
cm1autoStart_nohup		   countPattern.sh				       largeIndelPathUpdate.sh				       ssh-keyPush
cm2autoStart			   coverageResultValidator.jar			       launchAnalysises.pl				       ssh-keyPush.old
cm2autoStart_nohup		   cphere					       launchClients.pl					       subtractMappedReads.pl
cm2backup			   cpthere					       launchServer.pl					       tempTools1
cm2baseline			   createMergedBam.sh				       ldir						       tertiary_analysis
cm2cases			   createNupdateCases.sh			       ldirs						       test
cm2completelyStopANightlyTest	   createSqf.pl					       lfile						       testCaseCreationAndUpdation.pl
cm2goto				   createWorkflowTestCases.pl			       lfiles						       testCaseCreationAndUpdation_tmap.pl
cm2input			   csfastaToXSQ					       lib						       timeParser
cm2makeNewSuite			   csfasta_validation.pl			       library_xsq					       Time_Reporter.pm
cm2nightly			   csmanager					       linesFrom					       tmapbam
cm2results			   csmgr					       listFilesAndContents				       Tmap_TS_IR_Parity.sh
cm2status			   csmgrLocation				       ListScratch					       todays
cm2suites			   DatasetColorEncoding.sh			       localmapCounts.sh				       todaysTime
cm3baseline			   decode_All_XSQ_Index_reads_to_ColorQuality.pl       localVsProgressive.sh				       toolData
cm3bugs				   decode_All_XSQ_Index_reads_to_ColorQuality.sh       log						       toolData_era2
cm3bugsFrag			   decode_All_XSQreads_to_BaseQuality.pl	       log_extract.sh					       toolData_era3
cm3cases			   decode_All_XSQreads_to_BaseQuality.sh	       logScratchExtract.sh				       toolData_era5
cm3input			   decode_All_XSQreads_to_ColorQuality_ASCII.pl        logScratch.sh					       trimReadLength.pl
cm3makeNewSuite			   decode_All_XSQreads_to_ColorQuality_ASCII.sh        maConsolidator.sh				       updateCoronaVersionFile
cm3results			   decode_All_XSQreads_to_ColorQuality_barcoded.sh     MainTemplateXSQ.java				       updateFrameWork.sh
cm3suites			   decode_All_XSQreads_to_ColorQuality.sh	       maintenance					       updateJars.sh
cm4baseline			   decodeColorCallQV.pl				       mappedBeadCount.sh				       updateMe.sh
cm4bugs				   decode_samflags.pl				       [mapped in proper pair,				       update_testcases.pl
cm4cases			   decode_Start_End_XSQreads_to_ColorQuality.sh        mappingValidator					       upload.sh
cm4input			   decode_XSQreads_to_ColorQuality.pl		       matchAndLinkTestInputsAutomatically		       ValidateBAM.jar
cm4makeNewSuite			   deleteOldArchieve.py				       matchGatherCheck.pl				       Validate_CIGAR_length_Frag_LMP.pl
cm4results			   deleteOldBioscope.py				       matchingCounts.sh				       Validate_CIGAR_length_PE.pl
cm4suites			   deleteOldCorona.py				       matchingStatistics.sh				       Validate_Indels_in_CIGAR.pl
cm5baseline			   deleteOldLifescope.py			       matchKnownTestInput				       validate_reads_in_csfasta_BCXSQ_Frag.sh
cm5bugs				   derby.log					       matchKnownTestInput2				       validate_reads_in_csfasta_XSQ_Frag.sh
cm5cases			   devLicenses					       matchThroughputCheck.pl				       validate_reads_in_csfasta_XSQ_LMP_PE.sh
cm5input			   dicerBackup					       [mate is reverse,				       validate_reads_in_fastq_XSQ_Frag.sh
cm5makeNewSuite			   DiffBam.jar					       [mate is unmapped],				       validate_reads_in_fastq_XSQ_LMP_PE.sh
cm5results			   diffGFF					       matesReportGatherCheck.pl			       validateRoc.pl
cm5suites			   diffKeyValueFiles.jose.pl			       mc						       ValidateRunMetada_fastq_XSQ.sh
cmabortOff			   diffKeyValueFiles.pl				       mergeSortTags.pl					       ValidateRunMetada.sh
cmabortOn			   diffMatch					       missingTagIDCheck.pl.bak1			       validateTiTvRatio.pl
cmarchive			   diffSingleRead				       missingTagIDExtract.pl				       variantCaller_validator
cmarchive.Orig			   diffSingleRead.bak				       moduleTimings.pl					       VariantsReported.pl
cmautoStart			   diffWoComment				       monitoredRun					       vcf2gvcf_v2.py
cmautoStart_nohup		   dirContent_validate5.pl			       monitorNodes					       VcfStats
cmbackup			   dirContent_validate.pl			       monitorTimeOnly					       verifyScheme
cmbaseline			   dirContent_validate.pl.backup.beforesamFieldSorter  mqv2ma.pl					       verifyStep
cmbuildFlags			   duHere					       mqvFiltering.pl					       ViewStatus
cmbuildlist			   dvi						       mvthere						       waitForAPID
cmbuildlistvm			   encodeSequence.pl				       mytestcheckin					       waitForPbsJobComplete.pl
cmbuildMachine			   encodeSequence.pl~				       nightlyTestAutomationScripts			       waitForPBSSession
cmcases				   EnrichmentValidationTool.jar			       NumReadsPassed.sh				       waitForPBSStatus
cmcompletelyStopANightlyTest	   Error.txt					       outdated_scripts					       whatsinvv
cmCopyToBugs			   examine_beadBoundariesOfMaToBamSplits.sh	       pairingCategory_validate.pl			       whichBioscope
cmdataStorage			   examineLogsForDuration.sh			       pairing.dat_validate.pl				       which_workflow.pl
cmfr_nohup			   extract_all_groups.sh			       parseOutput.pl					       workflow_mon.pl
cmfr.sh				   extractBeadCounts				       parse_test_V1_F3.stats.txt.pl			       workflow_runner_custom.sh
cmgetBuildCoreTool		   extract_main_info_fastq_converted_XSQ.sh	       perfDataAverage.pl				       workflow_runner.sh
cmgetCorrectedLink		   extract_main_info_XSQ.sh			       perfHtmlGen.pl					       workflows_launcher.pl
cmgetLatestBuild		   extractQVFileSubSet.pl			       perfLogParser.pl					       workflows_suite_updater.pl
cmgetLatestBuild2.0		   extractReadsFromMappedSam.pl			       perfMakeCharts.pl				       workflow_stats.pl
cmgetLatestBuild2.1		   extractTagsForMerge1.pl			       picard						       WT_Alignments.pl
cmgetLatestBuildCP		   extractTagsForMerge.pl			       picard-tools-1.08				       WT_Compare13v20.pl
cmgetLatestNightlyBuild		   extract_XSQ_ids_barcoded.sh			       pipelineModuleTimingsFromLogs.sh			       wtCountResultValidator.jar
cmgetLatestNightlyBuild2.0	   extract_XSQ_Index_read_ids.sh		       pluginXmlFix.sh					       xsqconvert
cmgetLatestNightlyBuild2.1	   extract_XSQ_read_ids_csfasta_format.sh	       pluginXmlFix.sh.dir				       XSQConverter
cmgetNextNightlyBuild		   extract_XSQ_read_ids.sh			       positionErrorsGatherCheck.pl			       XSQ_read_extract.pl
cmgetNextNightlyBuild2.1	   FastqCIGAR.jar				       prepareResumeData.sh				       XSQ_Split_by_Panel.sh
cmgetNextNightlyBuild2.5	   fcat						       print_bam_header.jar				       XSQ_Tools_for_New_ECC.tar.gz
[liy15@jagger tools]$ chmod -R +x variantCaller_validator/
[liy15@jagger tools]$ ls -lh
total 84M
-rw-rw-r--  1 corona users  13K Aug 26  2010 #00_toolsIndex.txt#
-rw-rw-r--  1 corona users  39K Apr 16 03:48 00_toolsIndex.txt
-rwxrwxr-x  1 corona users 7.8K Feb 27  2009 01_template_tool_validate.pl
-rw-rw-r--  1 corona users   76 Feb 27  2009 03_maintainanceScratch.txt
-rw-rw-r--  1 corona users 1.3K Sep 23  2010 2
drwxrwxr-x 16 corona users  32K Feb 15  2011 3rdParty
-rwxrwxr-x  1 corona users   72 Feb 27  2009 abdig
-rwxrwxr-x  1 corona users 1.1K Feb 27  2009 addSuffixToLinkAndOriginal
-rw-rw-r--  1 corona users    0 Jun  8  2011 [alignment is not primary,
-rw-rw-r--  1 corona users  481 Jan 17  2011 AllRecordsIsPrimary.pl
-rw-rw-r--  1 iruser hdfs  876K Apr 10  2012 AlnLenCalc.jar
-rw-rw-r--  1 corona users  11K Sep 30  2010 a.txt
-rwxrwxr-x  1 corona users  12K Feb 27  2009 backup_dirContent_validate.pl
-rwxrwxr-x  1 corona users  970 Feb 27  2009 backup.extractTagsForMerge.pl
-rwxrwxr-x  1 corona users 1.2K Feb 27  2009 backup.mergeSortTags.pl
-rwxrwxr-x  1 corona users 1.8K Mar 22  2010 bam2sam
-rwxrwxr-x  1 corona users  444 Feb 15  2011 bamHeaderValidator.sh
-rwxrwxr-x  1 iruser hdfs  3.6K Apr 15 01:34 bamToContigs.sh
-rw-rw-r--  1 corona users  16M Jul 14  2011 bamToCsfasta.jar
-rwxr-xr-x  1 iruser hdfs  4.3K Jan  7 08:16 bamtosff_blocks.pl
-rw-rw-r--  1 corona users 1.4K Jul 14  2011 BamToXSQ.sh
-rw-rw-r--  1 corona users 1.5M Aug  1  2011 bamvalidation.jar
drwxr-xr-x  2 iruser hdfs   32K Apr  1 00:32 bam_validation_log
-rw-rw-r--  1 corona users 1.5M Feb 17  2012 bamValidationTool_SOLiD_ION.jar
drwxrwxr-x  4 corona users  32K Jul 29  2011 bamValidator
-rw-rw-r--  1 corona users  63K Mar  9  2011 bamValidator.cpp
-rw-rw-r--  1 corona users 2.5K Mar  7  2011 bamValidatorREADME
-rwxrwxr-x  1 corona users  394 Feb 27  2009 barcodeExtractPreTestInfo.sh
-rwxrwxr-x  1 corona users 2.4K Feb 27  2009 barcodeInputIntegrityCheck
-rwxrwxr-x  1 corona users 2.1K Feb 27  2009 barcodeOutputIntegrityCheck
drwxrwxr-x  4 corona users  32K Apr 12  2012 bedValidator
-rwxrwxr-x  1 corona users  399 Jan  7  2011 bgExec.sh
-rw-rw-r--  1 corona users 1.9K Jan 27  2011 bioscope.conf
drwxrwxr-x  3 corona users  32K Nov 16  2010 bioscopeConfigUpdater
-rwxrwxrwx  1 corona users  19K Apr 19  2011 biowrap
-rwxrwxr-x  1 corona users  18K Feb  3  2011 biowrap10
-rwxrwxr-x  1 corona users  18K Feb 10  2011 biowrap10.5
-rwxrwxr-x  1 corona users  19K Feb 10  2011 biowrap11
-rwxrwxr-x  1 corona users  19K Feb 23  2011 biowrap12.before_f_optionchange
-rwxrwxr-x  1 corona users  19K Feb 25  2011 biowrap14
-rwxrwxr-x  1 iruser hdfs  8.8K Apr 15 04:18 block_uploader_simulator.pl
-rwxr-xr-x  1 iruser hdfs  8.5K May  2 03:34 calulateModuleTime.pl
-rwxrwxr-x  1 corona users  894 Feb 25 00:32 caseManagerPath
-r--rw-r--  1 corona users  70K Jun 28  2012 caseManager.pm
-r--r--r--  1 iruser hdfs   70K Jun 28  2012 caseManager.pm.jose.backup
-rwxrwxr-x  1 corona users  328 Jan 26  2011 caseManagerSystemRequirements.sh
-rw-rw-r--  1 corona users  30K Feb 10  2011 caseManagerUtilities.pm
-rw-rw-r--  1 corona users  67K Sep 30  2010 caseManagerWa.pm
-rw-rw-r--  1 corona users  66K Sep 13  2010 caseManagerWa.pm.bak
-rw-rw-r--  1 corona users  69K Sep 30  2010 caseManagerWa.pm.bak.jose
-rwxrwxr-x  1 corona users  320 Apr  1  2010 cf
-rwxrwxr-x  1 corona users  303 Jun 18  2009 changeExtensions.sh
-rwxrwxr-x  1 corona users 2.9K Oct 16  2010 checkFailOutput.pl
-rwxrwxr-x  1 corona users 1.3K Aug  9  2010 checkMultiAnchorFromLog.pl
-rwxrwxr-x  1 corona users 1.3K Jan  4  2010 checkNumOfIterations.pl
-rwxrwxr-x  1 corona users 2.5K Oct 11  2010 checkPassOutput.pl
-rwxrwxr-x  1 corona users  696 Feb 12  2011 checkUnKilledBioscopeProcesses.sh
-rwxrwxr-x  1 corona users 6.2K Sep 24  2009 classifyMaByHits.pl
-rwxrwxr-x  1 iruser hdfs   346 May  8  2012 CleanScratch
-rwxrwxr-x  1 corona users 6.0K Jul 14  2009 cm1autoStart
-rwxrwxr-x  1 corona users  442 Jun 25  2009 cm1autoStart_nohup
-rwxrwxr-x  1 corona users 7.1K Feb 11  2010 cm2autoStart
-rwxrwxr-x  1 corona users  429 Jun 25  2009 cm2autoStart_nohup
-rwxrwxr-x  1 corona users  134 Jul 23  2009 cm2backup
-rwxrwxr-x  1 corona users   54 Jun 12  2009 cm2baseline
-rwxrwxr-x  1 corona users   43 May 12  2009 cm2cases
-rwxrwxr-x  1 corona users  424 Jan 20  2010 cm2completelyStopANightlyTest
-rwxrwxr-x  1 corona users  513 Oct 13  2010 cm2goto
-rwxrwxr-x  1 corona users   51 Jun  3  2009 cm2input
-rwxrwxr-x  1 corona users 2.7K Aug 17  2010 cm2makeNewSuite
-rwxrwxr-x  1 corona users 2.3K Feb 18  2010 cm2nightly
-rwxrwxr-x  1 corona users  174 Jul 28  2009 cm2results
-rwxrwxr-x  1 corona users  191 Jun 29  2009 cm2status
-rwxrwxr-x  1 corona users   44 May 12  2009 cm2suites
-rwxrwxr-x  1 corona users   54 Nov 19  2010 cm3baseline
-rwxrwxr-x  1 corona users   49 Jan 28  2011 cm3bugs
-rwxrwxr-x  1 corona users   65 Jan 25  2011 cm3bugsFrag
-rwxrwxr-x  1 corona users   43 Nov  3  2010 cm3cases
-rwxrwxr-x  1 corona users   51 Nov 19  2010 cm3input
-rwxrwxr-x  1 corona users 2.7K Nov 24  2010 cm3makeNewSuite
-rwxrwxr-x  1 corona users  174 Nov  3  2010 cm3results
-rwxrwxr-x  1 corona users   44 Nov  3  2010 cm3suites
-rwxrwxr-x  1 corona users   54 Aug 16  2011 cm4baseline
-rwxrwxr-x  1 corona users   49 Aug 16  2011 cm4bugs
-rwxrwxr-x  1 corona users   43 Aug 16  2011 cm4cases
-rwxrwxr-x  1 corona users   51 Aug 16  2011 cm4input
-rwxrwxr-x  1 corona users 3.5K Aug 16  2011 cm4makeNewSuite
-rwxrwxr-x  1 corona users  174 Aug 16  2011 cm4results
-rwxrwxr-x  1 corona users   44 Aug 16  2011 cm4suites
-rwxrwxr-x  1 corona users   54 Feb 27  2012 cm5baseline
-rwxrwxr-x  1 corona users   49 Feb 27  2012 cm5bugs
-rwxrwxr-x  1 corona users   43 Feb 27  2012 cm5cases
-rwxrwxr-x  1 corona users   51 Feb 27  2012 cm5input
-rwxrwxr-x  1 corona users 3.5K Feb 27  2012 cm5makeNewSuite
-rwxrwxr-x  1 corona users  174 Feb 27  2012 cm5results
-rwxrwxr-x  1 corona users   44 Feb 27  2012 cm5suites
-rwxrwxr-x  1 corona users   34 Feb 27  2009 cmabortOff
-rwxrwxr-x  1 corona users   32 Feb 27  2009 cmabortOn
-rwxrwxr-x  1 corona users 2.5K Feb 27  2009 cmarchive
-rwxrwxr-x  1 corona users  396 Feb 27  2009 cmarchive.Orig
-rwxrwxr-x  1 corona users 7.0K Oct 16  2009 cmautoStart
-rwxrwxr-x  1 corona users  440 Jun 25  2009 cmautoStart_nohup
-rwxrwxr-x  1 corona users  131 Feb 27  2009 cmbackup
-rwxrwxr-x  1 corona users   53 Feb 27  2009 cmbaseline
-rwxrwxr-x  1 corona users  243 Mar 12  2011 cmbuildFlags
-rwxrwxr-x  1 corona users  178 Jan 24  2011 cmbuildlist
-rwxrwxr-x  1 corona users   47 Feb 27  2009 cmbuildlistvm
-rwxrwxr-x  1 corona users  112 Oct 27  2010 cmbuildMachine
-rwxrwxr-x  1 corona users   11 Feb 27  2012 cmcases
-rwxrwxr-x  1 corona users  300 Jul  7  2009 cmcompletelyStopANightlyTest
-rwxrwxr-x  1 corona users  115 Jan 28  2011 cmCopyToBugs
-rwxrwxr-x  1 corona users   34 Aug 17  2009 cmdataStorage
-rwxrwxr-x  1 corona users 1.1K Feb 27  2012 cmfr_nohup
-rwxrwxr-x  1 corona users  465 Feb 27  2012 cmfr.sh
-rwxrwxr-x  1 corona users  16K Oct  7  2011 cmgetBuildCoreTool
-rwxrwxr-x  1 corona users 1.8K Feb  9  2010 cmgetCorrectedLink
-rwxrwxr-x  1 corona users   57 Oct  7  2011 cmgetLatestBuild
-rwxrwxr-x  1 corona users  223 Jan  7  2011 cmgetLatestBuild2.0
-rwxrwxr-x  1 corona users   57 Jun 20  2011 cmgetLatestBuild2.1
-rwxrwxr-x  1 corona users   57 May 31  2011 cmgetLatestBuildCP
-rwxrwxr-x  1 corona users   62 May 31  2011 cmgetLatestNightlyBuild
-rwxrwxr-x  1 corona users   62 Jan 31  2011 cmgetLatestNightlyBuild2.0
-rwxrwxr-x  1 corona users   62 Jun 20  2011 cmgetLatestNightlyBuild2.1
-rwxrwxr-x  1 corona users   84 May 31  2011 cmgetNextNightlyBuild
-rwxrwxr-x  1 corona users   84 Jun 20  2011 cmgetNextNightlyBuild2.1
-rwxrwxr-x  1 corona users   84 Jun 20  2011 cmgetNextNightlyBuild2.5
-rwxrwxr-x  1 corona users   88 Aug 26  2011 cmgetNextNightlyBuild2.5.CTS
lrwxrwxrwx  1 corona users   21 Aug 26  2011 cmgetNextNightlyBuildForNightlyLoop -> cmgetNextNightlyBuild
-rwxrwxr-x  1 corona users  360 Aug  5  2009 cmgoto
-rwxrwxr-x  1 corona users   24 Feb 12  2011 cmgotobioscope
-rwxrwxr-x  1 corona users   50 Feb 12  2011 cmgotoPluginXmlDir
-rwxrwxr-x  1 corona users  109 Feb 10  2011 cmhaveLatestBuild
-rwxrwxr-x  1 corona users   46 Feb 27  2009 cminput
-rwxrwxr-x  1 corona users  372 Feb 12  2011 cmisServerRunning
-rwxrwxr-x  1 corona users   16 Feb 27  2009 cmjmoap
-rwxrwxr-x  1 corona users  116 Feb 27  2009 cmlogCheckEndBuild01
-rwxrwxr-x  1 corona users  116 Feb 27  2009 cmlogCheckEndVm01
-rwxrwxr-x  1 corona users  113 Feb 27  2009 cmlogCheckStartBuild01
-rwxrwxr-x  1 corona users  227 Feb 27  2009 cmlogCheckStartVm01
-rwxrwxr-x  1 corona users  104 Feb 27  2009 cmlogWatchBuild01
-rwxrwxr-x  1 corona users  206 Feb 27  2009 cmlogWatchvm01
-rwxrwxr-x  1 corona users   88 Aug 17  2009 cmmapreadsPerf
-rwxrwxr-x  1 corona users  745 Jun 11  2009 cmmatchFindAllLinksTo
-rwxrwxr-x  1 corona users 1.6K Mar 28  2011 cmnightly
-rwxrwxr-x  1 corona users   51 Oct  6  2009 cmpluginProperties
-rwxrwxr-x  1 corona users 2.9K Jan 26  2010 cmpQVinSam.pl
-rwxrwxr-x  1 corona users  284 Oct  8  2009 cmps
-rwxrwxr-x  1 corona users  165 Jan 20  2010 cmqstat
-rwxrwxr-x  1 corona users 1.4K Jun 19  2009 cmrebaselineThisCase
-rwxrwxr-x  1 corona users   87 Feb 27  2009 cmreference
-rwxrwxr-x  1 corona users  321 Feb 11  2011 cmremoveFromPath
-rwxrwxr-x  1 corona users   35 Aug 17  2009 cmreports
-rwxrwxr-x  1 corona users   33 Feb 27  2012 cmresults
-rwxrwxr-x  1 corona users 2.8K Feb 15  2011 cmroot
-rwxrwxr-x  1 corona users 1.4K Aug 27  2010 cmroot.bak
-r-xrwxr-x  1 corona users 1.4K Feb 11  2011 cmroot.era2
-rwxrwxr-x  1 corona users  451 Jul 28  2009 cmrootLatestNightly
-rwxrwxr-x  1 corona users   34 Feb 27  2009 cmrunning
-rwxrwxr-x  1 corona users  494 Sep 20  2011 cmsan4.sh
-rwxrwxr-x  1 corona users 1.1K Feb 27  2012 cmsan_nohup
-rwxrwxr-x  1 corona users  494 Feb 27  2012 cmsan.sh
-rwxrwxr-x  1 corona users 1.5K Feb  5  2010 cmshowLatestGoodBuild
-rwxrwxr-x  1 corona users  205 Jan 15  2010 cmstatus
-rwxrwxr-x  1 corona users   12 Feb 27  2012 cmsuites
-rwxrwxr-x  1 corona users 1.7K Sep 29  2010 cmsvnRemove.sh
-rwxrwxr-x  1 corona users   33 Jan 10  2011 cmtools
-rwxrwxr-x  1 corona users   46 Oct 16  2009 cmusage
-rwxrwxr-x  1 iruser hdfs  8.1K Apr 17 01:25 cnv_affected_genes_validation.pl
-rwxrwxr-x  1 corona users 2.9K Jun 24  2009 cnvPvalCheck.pl
-rwxrwxr-x  1 corona users 7.8K Aug 10  2009 cnvReportedSegments1.pl
-rwxrwxr-x  1 corona users 3.6K Jun 22  2009 cnvReportedSegments_old.pl
-rwxrwxr-x  1 corona users 4.2K Jun 26  2009 cnvReportedSegments.pl
-rw-rw-r--  1 corona users 6.0K Aug 28  2009 cnvReportedSeg_sneha.pl
-rwxrwxrwx  1 iruser hdfs  3.9K Apr 15 01:22 CNV_validateSeqments_vcf.pl
-rw-rw-r--  1 corona users  631 May 24  2011 color_to_base_seq.pl
-rwxrwxr-x  1 corona users  799 Jul 21  2009 columnsToKeyValuePair.pl
-rwxrwxr-x  1 corona users  828 Feb 27  2009 compareFiles.sh
-rwxrwxr-x  1 iruser users  455 Oct  9  2012 ComparisonOfWorkflowRuns
-rw-rw-r--  1 corona users 2.3K Jan  5  2011 compUniqPrimaryVsAllAlignmnets.pl
-rwxrwxr-x  1 iruser hdfs   352 Jan  1 23:35 concurrent_run_launcher.sh
-rwxrwxr-x  1 iruser hdfs  4.3K Apr 23 02:52 concurrent_run_monitor_new.pl
-rwxrwxr-x  1 iruser hdfs  2.8K Apr 15 04:31 concurrent_run_monitor.pl
-rwxrwxr-x  1 iruser hdfs   11K Jan  3 02:19 concurrent_workflows_launcher.pl
-rw-rw-r--  1 corona users  631 Apr 26  2011 convert_color_to_base_seq.pl
-rwxrwxr-x  1 corona users 8.9K May  6  2009 convertToCoordsLatest
-rwxrwxr-x  1 corona users 4.0K Apr 20  2009 countBaseErrors.pl
-rwxrw-r--  1 corona users   80 Feb 19  2011 countPattern.sh
-rw-rw-r--  1 corona users 942K Feb 17  2012 coverageResultValidator.jar
-rwxrwxr-x  1 corona users  898 Mar  2  2009 cphere
-rwxrwxr-x  1 corona users  823 Feb 27  2009 cpthere
-rwxr-xr-x  1 iruser hdfs  2.1K Apr 29 04:17 createMergedBam.sh
-rwxrwxr-x  1 corona users   85 Jun 22  2011 createNupdateCases.sh
-rwxrwxr-x  1 corona users 1.9K Jan 15  2010 createSqf.pl
-rw-rw-r--  1 corona users  11K Jun 28  2011 createWorkflowTestCases.pl
drwxrwxr-x  3 corona users  32K Dec 10  2010 csfastaToXSQ
-rwxrwxr-x  1 corona users 3.6K Apr  5  2010 csfasta_validation.pl
drwxrwxr-x  3 corona users  32K Dec 17 00:21 csmanager
-rwxrwxr-x  1 corona users  100 Mar 18  2012 csmgr
-rwxrwxr-x  1 corona users  100 Feb 27  2009 csmgrLocation
-rw-rw-r--  1 corona users 1.2K Apr 19  2011 DatasetColorEncoding.sh
-rw-rw-r--  1 corona users  787 Feb  9  2011 decode_All_XSQ_Index_reads_to_ColorQuality.pl
-rw-rw-r--  1 corona users 1.1K Mar 22  2011 decode_All_XSQ_Index_reads_to_ColorQuality.sh
-rw-rw-r--  1 corona users 1.1K Feb  9  2011 decode_All_XSQreads_to_BaseQuality.pl
-rw-rw-r--  1 corona users 1.1K Mar 22  2011 decode_All_XSQreads_to_BaseQuality.sh
-rw-rw-r--  1 corona users  854 Feb 11  2011 decode_All_XSQreads_to_ColorQuality_ASCII.pl
-rw-rw-r--  1 corona users 1.1K Feb 23  2011 decode_All_XSQreads_to_ColorQuality_ASCII.sh
-rw-rw-r--  1 corona users 1.2K Mar 22  2011 decode_All_XSQreads_to_ColorQuality_barcoded.sh
-rw-rw-r--  1 corona users 1.2K Mar 22  2011 decode_All_XSQreads_to_ColorQuality.sh
-rw-rw-r--  1 corona users  198 Jan 16  2011 decodeColorCallQV.pl
-rwxrwxr-x  1 corona users 1.6K Dec 23  2009 decode_samflags.pl
-rw-rw-r--  1 corona users 1.2K Feb 23  2011 decode_Start_End_XSQreads_to_ColorQuality.sh
-rw-rw-r--  1 corona users  787 Jan 24  2011 decode_XSQreads_to_ColorQuality.pl
-rwxrwxr-x  1 corona users 1.1K Mar 12  2009 deleteOldArchieve.py
-rwxrwxr-x  1 corona users 1.2K Sep 10  2010 deleteOldBioscope.py
-rwxrwxr-x  1 corona users  651 Jul  1  2009 deleteOldCorona.py
-rwxrwxr-x  1 corona users 1.2K Feb 18  2011 deleteOldLifescope.py
-rw-rw-r--  1 corona users  397 Nov  3  2010 derby.log
dr-xrwxr-x  2 corona users  32K Feb  2  2011 devLicenses
drwxrwxr-x  4 corona users  32K Feb 27  2009 dicerBackup
-rw-rw-r--  1 corona users  16M Jul 15  2011 DiffBam.jar
-rwxrwxr-x  1 corona users  850 Apr 21  2009 diffGFF
-rwxrwxr-x  1 corona users  11K Jul  6  2009 diffKeyValueFiles.jose.pl
-rwxrwxr-x  1 corona users  10K Jun 30  2009 diffKeyValueFiles.pl
-rwxrwxr-x  1 corona users  822 Apr 21  2009 diffMatch
-rwxrwxr-x  1 corona users 1.3K Feb  3  2010 diffSingleRead
-rwxrwxr-x  1 corona users 1.3K Jan 25  2010 diffSingleRead.bak
-rwxrwxr-x  1 corona users  464 Feb 27  2009 diffWoComment
-rwxrwxr-x  1 corona users  27K Mar  7  2011 dirContent_validate5.pl
-rwxrwxr-x  1 corona users  28K Jul 18  2011 dirContent_validate.pl
-rwxrwxr-x  1 corona users  27K Mar  7  2011 dirContent_validate.pl.backup.beforesamFieldSorter
-rwxrwxr-x  1 corona users   27 May 14  2009 duHere
-rwxrwxr-x  1 corona users   73 Feb  1  2011 dvi
-rwxrwxr-x  1 corona users 3.3K Jan 11  2010 encodeSequence.pl
-rwxrwxr-x  1 corona users 3.3K Jan 11  2010 encodeSequence.pl~
-rw-rw-r--  1 iruser hdfs  1.5M May 15  2012 EnrichmentValidationTool.jar
-rw-rw-r--  1 corona users   32 Feb  8  2011 Error.txt
-rwxrwxr-x  1 corona users  906 Jun  8  2010 examine_beadBoundariesOfMaToBamSplits.sh
-rwxrwxr-x  1 corona users  129 Jun  2  2010 examineLogsForDuration.sh
-rw-rw-r--  1 corona users   45 Feb 23  2011 extract_all_groups.sh
drwxrwxr-x  3 corona users  32K Nov 13  2009 extractBeadCounts
-rwxrwxr-x  1 corona users 3.2K Feb 23  2011 extract_main_info_fastq_converted_XSQ.sh
-rwxrwxr-x  1 corona users 3.1K Apr 12  2011 extract_main_info_XSQ.sh
-rwxrwxr-x  1 corona users 1.1K Feb 27  2009 extractQVFileSubSet.pl
-rwxrwxr-x  1 iruser hdfs  2.3K Mar 22 07:01 extractReadsFromMappedSam.pl
-rwxrwxr-x  1 corona users 1.4K Feb 27  2009 extractTagsForMerge1.pl
-rwxrwxr-x  1 corona users 1.2K Feb 27  2009 extractTagsForMerge.pl
-rwxrwxr-x  1 corona users  607 Mar 22  2011 extract_XSQ_ids_barcoded.sh
-rw-rw-r--  1 corona users  453 Mar 22  2011 extract_XSQ_Index_read_ids.sh
-rw-rw-r--  1 corona users  489 Mar 21  2011 extract_XSQ_read_ids_csfasta_format.sh
-rw-rw-r--  1 corona users  407 Feb 23  2011 extract_XSQ_read_ids.sh
-rw-rw-r--  1 corona users  16M Jul 25  2011 FastqCIGAR.jar
-rwxrwxr-x  1 corona users   74 Feb 27  2009 fcat
-rwxrwxr-x  1 iruser hdfs   974 Jul  2  2012 fetchLogs
-rwxrwxr-x  1 corona users  128 Mar 29  2010 ff
-rwxrwxr-x  1 corona users  132 Feb 27  2009 fieldAverage.sh
-rwxrwxr-x  1 corona users  14K Dec 21  2010 fileContent_validate2.pl
-rwxrwxr-x  1 corona users  14K Jan 14  2011 fileContent_validate_jose2011.bak.pl
-rwxrwxr-x  1 corona users  15K Feb  7  2011 fileContent_validate.pl
-rwxrwxr-x  1 corona users  12K Nov 17  2010 fileContent_validate.pl.containsRecursiveChecks
-rwxrwxr-x  1 corona users 7.8K Sep  8  2009 fileContent_validate.pl.jose.bak.beforeRecursiveChange
-rwxrwxr-x  1 corona users  14K Dec 21  2010 fileContent_validate.pl.suspicious
-rwxrwxr-x  1 corona users  835 Jan 10  2011 findAFreePort.pl
-rwxrwxr-x  1 corona users 1.7K Dec 30  2009 findAverageQvForUnmappedBeads.pl
-rwxrwxr-x  1 corona users  260 Jan 27  2011 findException.sh
-rw-rw-r--  1 corona users    0 Jun  8  2011 [first read in pair],
-rw-rw-r--  1 corona users  187 Jan 19  2011 fragmentMapping.rrs
-rwxrwxr-x  1 corona users   16 Feb 27  2009 fvi
-rwxrwxr-x  1 corona users   16 Mar  6  2009 fview
-rwxrwxr-x  1 corona users  766 Feb 11  2010 generateReadmeInFolder.pl
-rwxrwxr-x  1 corona users 1.5K Feb 27  2009 getBeadDensity.pl
-rwxrw-r--  1 corona users   77 Feb 21  2011 getCigarString.sh
-rw-rw-r--  1 iruser hdfs  2.5K Jan  2 02:57 GetConsensusCoverage.jar
-rwxrwxr-x  1 corona users 1.6K Dec 30  2009 getCountOfBeadsWithAverageQvGreaterThan.pl
-rwxrwxr-x  1 corona users 2.5K Nov 22  2010 getFileProperties
-rwxrwxr-x  1 corona users  624 May 21  2009 getFormattedTimeDiff
-rwxrwxr-x  1 corona users 1.1K Feb 18  2011 getFromBuildMachine.sh
-rwxrwxr-x  1 corona users  351 Feb 27  2009 getFromVMBuildMachine.sh
-rwxrwxr-x  1 corona users 5.6K Sep 23  2009 getGffPositionErrors.pl
-rwxrwxr-x  1 corona users   97 Feb 27  2009 getHostIP
-rwxrwxr-x  1 corona users 1.2K Feb 27  2009 getInstrumentsFromDiscoLog
-rwxrwxr-x  1 corona users  331 Jun 27  2009 getLocalScore.pl
-rwxrwxrwx  1 iruser hdfs   355 Apr 16 22:30 getLogs.sh
-rwxrwxr-x  1 corona users  427 Jul 21  2009 getPatternCounts.pl
-rwxrwxr-x  1 corona users 2.9K Feb 16  2010 getPositionErrorFreqInCycle.pl
-rwxrwxrwx  1 corona users 2.9K Apr  3  2009 getProgressiveThroughputsFromLog.pl
-rwxrwxr-x  1 corona users 2.9K Aug  7  2009 getQvByTag.pl
-rwxrwxr-x  1 corona users 3.6K Feb 16  2010 getRecordsByBeadId.pl
-rwxr-xr-x  1 iruser hdfs   810 Mar 18 06:16 getSelectiveBeadsFromUnmappedBAM.pl
-rwxrwxr-x  1 corona users  263 Aug 17  2009 getStableMapReadsBuild
-rwxrwxr-x  1 corona users  798 Feb 27  2009 getStringency.pl
-rwxrwxr-x  1 corona users 6.9K Mar 19  2009 getSubRefByIndex.pl
-rwxrwxr-x  1 iruser hdfs   954 Apr  1 04:22 getUnmappedBAMFromMappedBAM.pl
-rw-rw-r--  1 corona users  524 Jun  2  2010 gff2bam.sh
drwxrwxr-x  2 corona users  32K Jun  2  2010 gffToBam
drwxrwxr-x  2 corona users  32K Feb  8  2010 gff_utils
-rwxrwxr-x  1 corona users  13K Feb 27  2009 graphGen.pl
-rwxrwxr-x  1 corona users  214 Jun 18  2009 hideLastLines
drwxrwxr-x  3 corona users  32K Feb 27  2009 images
-rwxrwxr-x  1 corona users  22K Jun 15  2009 imap_fasta2match.pl
-rwxrwxr-x  1 corona users 5.1K Feb 27  2009 instrumentDataScan_1
-rwxrwxr-x  1 corona users 5.9K Feb 27  2009 instrumentDataScanBeadCount
-rwxrwxr-x  1 corona users 5.9K Feb 27  2009 instrumentDataScanFocalMapMedian
-rwxrwxr-x  1 corona users 2.7K Feb 27  2009 instrumentDataScanFocalMapMedianLocal
drwxrwxr-x  4 corona users  32K Apr 20  2009 javascripts
-rwxrwxr-x  1 corona users  192 Feb 27  2009 jblock
-rwxrwxr-x  1 corona users  293 Feb 27  2009 jcompile.sh
-rwxrwxr-x  1 corona users  926 Mar  2  2011 jingValidate_CIGAR_length_Frag_LMP.pl
-rwxrwxr-x  1 corona users  145 Feb 27  2009 jpblock
-rwxrwxr-x  1 corona users  339 Feb 27  2009 jrun.sh
drwxrwxr-x  4 corona users  32K May 27  2009 jtools
-rwxrwxr-x  1 corona users  157 Feb 27  2009 killPBSJobs.sh
-rwxrwxr-x  1 corona users 2.3K Feb 14  2011 killServer.pl
-rwxrwxr-x  1 corona users  347 Aug 18  2009 largeIndelPathUpdate.sh
-rwxrwxr-x  1 corona users 7.7K Feb 22  2011 launchAnalysises.pl
-rwxrwxr-x  1 corona users 7.7K Feb 17  2011 launchClients.pl
-rwxrwxr-x  1 corona users 3.1K Feb 16  2011 launchServer.pl
-rwxrwxr-x  1 corona users  254 Feb 27  2009 ldir
-rwxrwxr-x  1 corona users  198 Feb 27  2009 ldirs
-rwxrwxr-x  1 corona users  155 Feb 27  2009 lfile
-rwxrwxr-x  1 corona users  155 Feb 27  2009 lfiles
drwxrwxr-x  8 corona users  32K Nov 17  2009 lib
drwxr-xr-x  2 corona users  32K Dec 16  2011 library_xsq
-rwxrwxr-x  1 corona users 1.6K Jul 21  2009 linesFrom
-rwxrwxr-x  1 corona users   40 Feb 27  2009 listFilesAndContents
-rwxr-xr-x  1 iruser hdfs   383 May  8  2012 ListScratch
-rwxrwxr-x  1 corona users  815 Jun 25  2009 localmapCounts.sh
-rwxrwxr-x  1 corona users  819 Jul 13  2009 localVsProgressive.sh
drwxrwxr-x  2 corona users  32K Sep 30  2011 log
-rw-rw-r--  1 corona users  834 Jan  5  2011 log_extract.sh
-rwxrwxr-x  1 corona users   70 Mar 11  2010 logScratchExtract.sh
-rwxrwxr-x  1 corona users  229 Mar 18  2010 logScratch.sh
-rwxrwxr-x  1 corona users  816 Jul 22  2009 maConsolidator.sh
-rw-rw-r--  1 corona users 2.3K Jun 20  2011 MainTemplateXSQ.java
drwxrwxr-x  7 corona users  32K Feb 14  2011 maintenance
-rwxrwxr-x  1 corona users  377 Feb 27  2009 mappedBeadCount.sh
-rw-rw-r--  1 corona users    0 Jun  8  2011 [mapped in proper pair,
-rwxrwxr-x  1 corona users  937 Jun 17  2009 mappingValidator
-rwxrwxr-x  1 corona users  883 Feb 27  2009 matchAndLinkTestInputsAutomatically
-rwxrwxr-x  1 corona users 6.6K Mar 11  2009 matchGatherCheck.pl
-rwxrwxr-x  1 corona users  836 Apr 16  2009 matchingCounts.sh
-rwxrwxr-x  1 corona users  861 Apr 21  2009 matchingStatistics.sh
-rwxrwxr-x  1 corona users 2.6K Feb 27  2009 matchKnownTestInput
-rwxrwxr-x  1 corona users 2.6K Jun 11  2009 matchKnownTestInput2
-rwxrwxr-x  1 corona users  11K Apr 17  2009 matchThroughputCheck.pl
-rw-rw-r--  1 corona users    0 Jun  8  2011 [mate is reverse,
-rw-rw-r--  1 corona users    0 Jun  8  2011 [mate is unmapped],
-rwxrwxr-x  1 corona users 2.2K Apr  3  2009 matesReportGatherCheck.pl
-rwxrwxr-x  1 corona users 5.1K May  7  2009 mc
-rwxrwxr-x  1 corona users 1.9K Feb 27  2009 mergeSortTags.pl
-rwxrwxr-x  1 corona users 2.0K Feb 27  2009 missingTagIDCheck.pl.bak1
-rwxrwxr-x  1 corona users 3.7K Feb 27  2009 missingTagIDExtract.pl
-rwxrwxrwx  1 iruser hdfs  5.2K Apr 15 01:44 moduleTimings.pl
-rwxrwxr-x  1 corona users 1.1K Jun  1  2009 monitoredRun
-rwxrwxr-x  1 corona users 5.9K Jun 18  2009 monitorNodes
-rwxrwxr-x  1 corona users 1.1K Jun 29  2009 monitorTimeOnly
-rwxrwxr-x  1 corona users 2.8K Sep 20  2009 mqv2ma.pl
-rwxrwxr-x  1 corona users 2.8K Oct 12  2009 mqvFiltering.pl
-rwxrwxr-x  1 corona users  816 Feb 27  2009 mvthere
-rw-rw-r--  1 corona users    5 Dec  8  2010 mytestcheckin
drwxrwxr-x  3 corona users  32K Feb 11  2011 nightlyTestAutomationScripts
-rwxrwxr-x  1 corona users 1.6K Apr 27  2011 NumReadsPassed.sh
drwxrwxr-x  5 iruser hdfs   32K Apr  1 03:06 outdated_scripts
-rwxrwxr-x  1 corona users  131 Jul 31  2009 pairingCategory_validate.pl
-rwxrwxr-x  1 corona users 1.2K Jul 27  2009 pairing.dat_validate.pl
-rwxrwxr-x  1 corona users 2.0K Oct 13  2010 parseOutput.pl
-rwxrwxr-x  1 corona users  12K Sep 16  2009 parse_test_V1_F3.stats.txt.pl
-rwxrwxr-x  1 corona users 6.5K Feb 27  2009 perfDataAverage.pl
-rwxrwxr-x  1 corona users  16K Apr  8  2009 perfHtmlGen.pl
-rwxrwxr-x  1 corona users  16K Apr  8  2009 perfLogParser.pl
-rwxrwxr-x  1 corona users  693 Feb 27  2009 perfMakeCharts.pl
drwxrwxr-x  2 corona users  32K Feb  3  2010 picard
drwxrwxr-x  2 corona users  32K Jan  5  2010 picard-tools-1.08
-rwxrwxr-x  1 corona users  129 May 21  2010 pipelineModuleTimingsFromLogs.sh
-rwxrwxr-x  1 corona users  177 Jul 24  2009 pluginXmlFix.sh
drwxrwxr-x  2 corona users  32K Sep 29  2010 pluginXmlFix.sh.dir
-rwxrwxr-x  1 corona users 4.0K Feb 27  2009 positionErrorsGatherCheck.pl
-rwxrwxr-x  1 iruser hdfs   761 Apr 18 03:56 prepareResumeData.sh
-rw-rw-r--  1 corona users  11M Jan 25  2011 print_bam_header.jar
-rwxrwxr-x  1 corona users 1.6K Feb 27  2009 printStringencyTable.pl
-rwxrwxr-x  1 corona users   14 Aug 31  2009 pwdClean
-rwxrwxr-x  1 corona users   16 Feb 27  2009 pwdThis
-rw-rw-r--  1 corona users 9.4K Dec  6  2011 QC_protocol_resultValidationScript.pl
-rwxrwxr-x  1 iruser hdfs  4.7K Apr 10  2012 qcValidation_IR.pl
-rwxrwxr-x  1 corona users  810 Jan 25  2010 qv_ascii2int.pl
-rwxrwxr-x  1 corona users  778 Jan 25  2010 qv_int2ascii.pl
-rwxrwxr-x  1 corona users 3.1K Jul 14  2009 random_sequence_picker.pl
-rw-rw-r--  1 corona users    0 Jun  8  2011 [read fails quality check],
-rw-rw-r--  1 corona users    0 Jun  8  2011 [read is paired,
-rw-rw-r--  1 corona users    0 Jun  8  2011 [read is PCR or optical duplicate],
-rw-rw-r--  1 corona users    0 Jun  8  2011 [read is unmapped],
-rw-rw-r--  1 corona users  785 Jan 21  2011 readme.txt
-rwxrwxr-x  1 corona users 1.6K Feb 27  2009 readSplittingCheck.pl
-rwxrwxr-x  1 corona users  814 Dec 17  2009 readsSplitter.sh
-rwxrwxr-x  1 corona users  176 Feb 27  2009 referenceBaseCount
-rwxrwxr-x  1 corona users  462 Mar 22  2010 referenceProperties
-rwxrwxr-x  1 corona users  228 Mar  6  2009 renameRPMResults.sh
-rwxrwxr-x  1 corona users  709 May 14  2009 repointLinkFromTo
-rw-rw-r--  1 corona users 1.6K Jan 16  2011 Reseq_Compare13v20.pl
-rw-rw-r--  1 corona users    0 Jun  8  2011 [reverse strand,
-rwxrw-r--  1 corona users 2.8K Mar 19  2009 robustintersection.verbose
-rwxrwxr-x  1 corona users  906 Feb 25  2010 runLogScratch.sh
-rwxrwxr-x  1 corona users 9.5K Feb 21  2011 runLscopeAnalysis.pl
-rwxrwxr-x  1 corona users 9.3K Feb 22  2011 runLscope.pl
-rwxrwxr-x  1 corona users 1.4K Jan 16  2010 sam2bam
-rw-rw-r--  1 corona users   91 Feb  8  2011 sam2bam.out
-rwxrwxr-x  1 corona users 1.3K Sep 24  2010 samFieldSorter.pl
-rwxrwxr-x  1 corona users 8.3K Aug 17  2009 sampling_csfasta_by_panel
-rw-rw-r--  1 corona users 1.4K Aug 17  2009 sampling_csfasta_by_panel.c
-rwxrwxr-x  1 corona users 8.2K Aug 17  2009 sampling_csfasta_by_ratio
-rw-rw-r--  1 corona users 1.1K Aug 17  2009 sampling_csfasta_by_ratio.c
-rwxr-xr-x  1 iruser hdfs  1.2M Apr 10  2012 samtools
-rwxrwxr-x  1 corona users 2.3K Feb 27  2009 scanBarcodeXml.pl
-rwxrwxr-x  1 corona users  11K Jul 23  2010 schemeCheck.pl
-rw-rw-r--  1 corona users   41 Feb 27  2009 scratch.txt
drwxrwxr-x  7 iruser hdfs   32K Apr  2 07:58 scriptsTC
drwxrwxr-x  3 iruser hdfs   32K Apr  2 07:58 secondary_analysis
drwxrwxr-x  7 corona users  32K Mar 22 06:26 Secondary_Common_Testing_Scripts
-rw-rw-r--  1 corona users    0 Jun  8  2011 [second read in pair],
-rwxrwxr-x  1 corona users  12K Mar 16  2010 selectQvForGivenMaFile
-rw-rw-r--  1 iruser hdfs  2.6K Apr 15 01:43 separateContigs.pl
lrwxrwxrwx  1 corona users   64 Jun 17  2011 serverSideLogs -> /data/results/jose/joseBuild-v2.0-r0_72866_20110204182433/server
-rwxrwxr-x  1 corona users  769 May 19  2009 setNightlyTestBuild
drwxrwxr-x  2 corona users  32K Mar 13  2012 sff2fastq
drwxrwxr-x  2 corona users  32K Mar 13  2012 SFF_Extract
-rwxr-xr-x  1 iruser hdfs   20K May 11  2012 sff_info
-rwxrwxr-x  1 corona users  825 Mar  6  2010 sfr2_nohup
-rwxrwxr-x  1 corona users  458 Jun 25  2009 sfr2.sh
-rwxrwxr-x  1 corona users  800 Feb 27  2009 sfr_nohup
-rwxrwxr-x  1 corona users  494 Sep 20  2011 sfr.sh
drwxrwxr-x  3 corona users  32K Feb 27  2009 shortTermTools
-rwxrwxr-x  1 corona users  277 Mar 12  2010 showCommanLineOption.pl
-rwxr-xr-x  1 iruser hdfs  3.8K May  7  2012 showstats.py
-rwxrwxr-x  1 corona users 2.7K Mar 10  2010 simulateContigs.pl
-rwxrwxr-x  1 corona users   26 Jul 14  2009 smallIndelPathUpdate.sh
-rwxrwxr-x  1 corona users  566 Feb 27  2009 sortByBeadIDs.sh
-rwxr-xr-x  1 iruser hdfs  3.4K Apr 14 23:21 splitFastaToContigs.pl
-rwxr-xr-x  1 zhaij1 users 1.1K Jul 25  2012 split_var2snp_indels_mnv_vcf.py
drwxrwxr-x  6 corona users  32K Mar 22  2010 src
-rwxrwxr-x  1 corona users 4.4K Feb 27  2009 ssh-keyPush
-rwxrwxr-x  1 corona users 4.3K Feb 27  2009 ssh-keyPush.old
-rwxrwxr-x  1 corona users 2.0K Feb 19  2010 subtractMappedReads.pl
drwxrwxr-x  2 corona users  32K Jan 20  2010 tempTools1
drwxr-xr-x  6 iruser hdfs   32K Apr 26 05:57 tertiary_analysis
drwxrwxr-x 28 corona users  32K Dec 29  2010 test
-rw-rw-r--  1 corona users  31K Mar 12  2012 testCaseCreationAndUpdation.pl
-rw-rw-r--  1 corona users  32K Mar 14  2012 testCaseCreationAndUpdation_tmap.pl
drwxrwxr-x  4 corona users  32K Feb 27  2009 timeParser
-rw-rw-r--  1 iruser hdfs  1.7K Apr 15 08:26 Time_Reporter.pm
drwxrwxrwx  4 iruser hdfs   32K May 30  2012 tmapbam
-rwxrwxr-x  1 iruser hdfs  3.2K Apr  2 23:47 Tmap_TS_IR_Parity.sh
-rwxrwxr-x  1 corona users   10 Feb 27  2009 todays
-rwxrwxr-x  1 corona users   18 Feb 27  2009 todaysTime
lrwxrwxrwx  1 corona users   13 Feb 27  2012 toolData -> toolData_era5
drwxrwxr-x  6 corona users  32K Feb 27  2009 toolData_era2
drwxrwxr-x  7 corona users  32K Sep 21  2011 toolData_era3
drwxrwxr-x  7 corona users  32K Dec 25 05:23 toolData_era5
-rwxrwxr-x  1 corona users 1.9K Jul 30  2009 trimReadLength.pl
-rwxrwxr-x  1 corona users 1.4K Feb 27  2009 updateCoronaVersionFile
-rwxrwxr-x  1 corona users 1013 Feb 23  2011 updateFrameWork.sh
-rwxrwxr-x  1 corona users 1.1K Apr 21  2009 updateJars.sh
-rwxrwxr-x  1 corona users  129 Feb 22  2011 updateMe.sh
-rwxrwxr-x  1 iruser hdfs  2.5K Apr  9 06:54 update_testcases.pl
-rwxrwxr-x  1 iruser hdfs   448 Apr 24 00:25 upload.sh
-rw-rw-r--  1 iruser hdfs  985K Aug 24  2012 ValidateBAM.jar
-rwxrwxr-x  1 corona users  905 Mar 10  2011 Validate_CIGAR_length_Frag_LMP.pl
-rwxrwxr-x  1 corona users 1.3K May 23  2011 Validate_CIGAR_length_PE.pl
-rwxrwxr-x  1 corona users 1.3K May 24  2011 Validate_Indels_in_CIGAR.pl
-rw-rw-r--  1 corona users 1.6K Feb 23  2011 validate_reads_in_csfasta_BCXSQ_Frag.sh
-rw-rw-r--  1 corona users 1.6K Mar 22  2011 validate_reads_in_csfasta_XSQ_Frag.sh
-rw-rw-r--  1 corona users 1.8K Mar 22  2011 validate_reads_in_csfasta_XSQ_LMP_PE.sh
-rw-rw-r--  1 corona users 1.5K Feb 23  2011 validate_reads_in_fastq_XSQ_Frag.sh
-rw-rw-r--  1 corona users 1.7K May 26  2011 validate_reads_in_fastq_XSQ_LMP_PE.sh
-rwxrwxr-x  1 corona users 2.3K Feb 27  2009 validateRoc.pl
-rw-rw-r--  1 corona users 7.5K Feb 23  2011 ValidateRunMetada_fastq_XSQ.sh
-rw-rw-r--  1 corona users 5.9K Apr  6  2011 ValidateRunMetada.sh
-rwxrwxr-x  1 zhaij1 users 1.7K Jul 19  2012 validateTiTvRatio.pl
drwxrwxr-x  2 liy15  users  32K May  6  2013 variantCaller_validator
-rwxrwxrwx  1 iruser hdfs  5.1K Apr 15 01:50 VariantsReported.pl
-rwxr-xr-x  1 iruser hdfs  2.8K Apr 18 18:24 vcf2gvcf_v2.py
-rwxrwxr-x  1 iruser hdfs   780 May  9  2012 VcfStats
drwxrwxr-x  3 corona users  32K May  8  2012 verifyScheme
drwxrwxr-x  2 corona users  32K May  8  2012 verifyStep
-rwxrwxr-x  1 iruser hdfs   483 May  9  2012 ViewStatus
-rwxrwxr-x  1 corona users  239 Oct 29  2010 waitForAPID
-rwxrwxr-x  1 corona users  597 Feb 27  2009 waitForPbsJobComplete.pl
-rwxrwxr-x  1 corona users  257 Sep 23  2009 waitForPBSSession
-rwxrwxr-x  1 corona users  211 Aug 21  2009 waitForPBSStatus
-rwxrwxr-x  1 corona users   29 Feb 27  2009 whatsinvv
-rwxrwxr-x  1 corona users   18 Sep 17  2009 whichBioscope
-rwxr-xr-x  1 iruser hdfs  3.7K Apr  1 03:11 which_workflow.pl
-rwxrwxr-x  1 iruser users 2.9K Apr  1 01:09 workflow_mon.pl
-rwxrwxr-x  1 iruser hdfs   153 May  3 01:08 workflow_runner_custom.sh
-rwxrwxr-x  1 iruser hdfs   205 Apr 23 03:01 workflow_runner.sh
-rwxrwxr-x  1 iruser hdfs  6.3K May  2 08:53 workflows_launcher.pl
-rwxrwxr-x  1 iruser hdfs  2.3K Apr  1 01:18 workflows_suite_updater.pl
-rwxr-xr-x  1 iruser users  16K Apr 22 23:42 workflow_stats.pl
-rwxrwxr-x  1 corona users 1.2K Jan 17  2011 WT_Alignments.pl
-rwxrwxr-x  1 corona users 2.0K Jan 16  2011 WT_Compare13v20.pl
-rw-rw-r--  1 corona users 952K Feb 19  2012 wtCountResultValidator.jar
-rwxrwxr-x  1 corona users 264K Feb 23  2011 xsqconvert
drwxr-xr-x  4 corona users  32K Jul 14  2011 XSQConverter
-rwxrwxr-x  1 corona users 5.5K Jun 27  2011 XSQ_read_extract.pl
-rw-rw-r--  1 corona users 1.6K Sep 14  2011 XSQ_Split_by_Panel.sh
-rw-rw-r--  1 corona users 3.6M Jul 29  2011 XSQ_Tools_for_New_ECC.tar.gz
[liy15@jagger tools]$ ls -lh variantCaller_validator/
total 160K
-rwxrwxr-x 1 liy15 users  793 May  6  2013 readme.txt
-rwxr-xr-x 1 liy15 users 110K May  6  2013 variantValidator_multi
[liy15@jagger tools]$ cd variantCaller_validator/
[liy15@jagger variantCaller_validator]$ vi readme.txt 
[liy15@jagger variantCaller_validator]$ ls
readme.txt  variantValidator_multi
[liy15@jagger variantCaller_validator]$ mv readme.txt readme.rst
[liy15@jagger variantCaller_validator]$ ls
readme.rst  variantValidator_multi
[liy15@jagger variantCaller_validator]$ git
usage: git [--version] [--help] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p|--paginate|--no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

The most commonly used git commands are:
   add        Add file contents to the index
   bisect     Find by binary search the change that introduced a bug
   branch     List, create, or delete branches
   checkout   Checkout a branch or paths to the working tree
   clone      Clone a repository into a new directory
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   fetch      Download objects and refs from another repository
   grep       Print lines matching a pattern
   init       Create an empty Git repository or reinitialize an existing one
   log        Show commit logs
   merge      Join two or more development histories together
   mv         Move or rename a file, a directory, or a symlink
   pull       Fetch from and merge with another repository or a local branch
   push       Update remote refs along with associated objects
   rebase     Forward-port local commits to the updated upstream head
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index
   show       Show various types of objects
   status     Show the working tree status
   tag        Create, list, delete or verify a tag object signed with GPG

See 'git help <command>' for more information on a specific command.
[liy15@jagger variantCaller_validator]$ cd ..
[liy15@jagger tools]$ git init
Initialized empty Git repository in /gs1/VV/results1/RegressionDriver/CaseManager/tools/.git/
[liy15@jagger tools]$ git add variantCaller_validator
[liy15@jagger tools]$ git commit -m "validator"
[master (root-commit) 15b86bb] validator
 Committer: Yunfei Li <liy15@jagger.na.ab.applera.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 26 insertions(+)
 create mode 100755 variantCaller_validator/readme.rst
 create mode 100755 variantCaller_validator/variantValidator_multi
[liy15@jagger tools]$ git remote add origin git@github.com:yunfei86/variantCaller.git
[liy15@jagger tools]$ git push -u origin master
Warning: Permanently added 'github.com' (RSA) to the list of known hosts.
Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
[liy15@jagger tools]$ vi ~/.ssh/id_rsa.pub 
[liy15@jagger tools]$ git push -u origin master
Counting objects: 5, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 42.57 KiB, done.
Total 5 (delta 0), reused 0 (delta 0)
To git@github.com:yunfei86/variantCaller.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
[liy15@jagger tools]$ ls
#00_toolsIndex.txt#		   cmgetNextNightlyBuild2.5.CTS			       fetchLogs					       printStringencyTable.pl
00_toolsIndex.txt		   cmgetNextNightlyBuildForNightlyLoop		       ff						       pwdClean
01_template_tool_validate.pl	   cmgoto					       fieldAverage.sh					       pwdThis
03_maintainanceScratch.txt	   cmgotobioscope				       fileContent_validate2.pl				       QC_protocol_resultValidationScript.pl
2				   cmgotoPluginXmlDir				       fileContent_validate_jose2011.bak.pl		       qcValidation_IR.pl
3rdParty			   cmhaveLatestBuild				       fileContent_validate.pl				       qv_ascii2int.pl
abdig				   cminput					       fileContent_validate.pl.containsRecursiveChecks	       qv_int2ascii.pl
addSuffixToLinkAndOriginal	   cmisServerRunning				       fileContent_validate.pl.jose.bak.beforeRecursiveChange  random_sequence_picker.pl
[alignment is not primary,	   cmjmoap					       fileContent_validate.pl.suspicious		       [read fails quality check],
AllRecordsIsPrimary.pl		   cmlogCheckEndBuild01				       findAFreePort.pl					       [read is paired,
AlnLenCalc.jar			   cmlogCheckEndVm01				       findAverageQvForUnmappedBeads.pl			       [read is PCR or optical duplicate],
a.txt				   cmlogCheckStartBuild01			       findException.sh					       [read is unmapped],
backup_dirContent_validate.pl	   cmlogCheckStartVm01				       [first read in pair],				       readme.txt
backup.extractTagsForMerge.pl	   cmlogWatchBuild01				       fragmentMapping.rrs				       readSplittingCheck.pl
backup.mergeSortTags.pl		   cmlogWatchvm01				       fvi						       readsSplitter.sh
bam2sam				   cmmapreadsPerf				       fview						       referenceBaseCount
bamHeaderValidator.sh		   cmmatchFindAllLinksTo			       generateReadmeInFolder.pl			       referenceProperties
bamToContigs.sh			   cmnightly					       getBeadDensity.pl				       renameRPMResults.sh
bamToCsfasta.jar		   cmpluginProperties				       getCigarString.sh				       repointLinkFromTo
bamtosff_blocks.pl		   cmpQVinSam.pl				       GetConsensusCoverage.jar				       Reseq_Compare13v20.pl
BamToXSQ.sh			   cmps						       getCountOfBeadsWithAverageQvGreaterThan.pl	       [reverse strand,
bamvalidation.jar		   cmqstat					       getFileProperties				       robustintersection.verbose
bam_validation_log		   cmrebaselineThisCase				       getFormattedTimeDiff				       runLogScratch.sh
bamValidationTool_SOLiD_ION.jar    cmreference					       getFromBuildMachine.sh				       runLscopeAnalysis.pl
bamValidator			   cmremoveFromPath				       getFromVMBuildMachine.sh				       runLscope.pl
bamValidator.cpp		   cmreports					       getGffPositionErrors.pl				       sam2bam
bamValidatorREADME		   cmresults					       getHostIP					       sam2bam.out
barcodeExtractPreTestInfo.sh	   cmroot					       getInstrumentsFromDiscoLog			       samFieldSorter.pl
barcodeInputIntegrityCheck	   cmroot.bak					       getLocalScore.pl					       sampling_csfasta_by_panel
barcodeOutputIntegrityCheck	   cmroot.era2					       getLogs.sh					       sampling_csfasta_by_panel.c
bedValidator			   cmrootLatestNightly				       getPatternCounts.pl				       sampling_csfasta_by_ratio
bgExec.sh			   cmrunning					       getPositionErrorFreqInCycle.pl			       sampling_csfasta_by_ratio.c
bioscope.conf			   cmsan4.sh					       getProgressiveThroughputsFromLog.pl		       samtools
bioscopeConfigUpdater		   cmsan_nohup					       getQvByTag.pl					       scanBarcodeXml.pl
biowrap				   cmsan.sh					       getRecordsByBeadId.pl				       schemeCheck.pl
biowrap10			   cmshowLatestGoodBuild			       getSelectiveBeadsFromUnmappedBAM.pl		       scratch.txt
biowrap10.5			   cmstatus					       getStableMapReadsBuild				       scriptsTC
biowrap11			   cmsuites					       getStringency.pl					       secondary_analysis
biowrap12.before_f_optionchange    cmsvnRemove.sh				       getSubRefByIndex.pl				       Secondary_Common_Testing_Scripts
biowrap14			   cmtools					       getUnmappedBAMFromMappedBAM.pl			       [second read in pair],
block_uploader_simulator.pl	   cmusage					       gff2bam.sh					       selectQvForGivenMaFile
calulateModuleTime.pl		   cnv_affected_genes_validation.pl		       gffToBam						       separateContigs.pl
caseManagerPath			   cnvPvalCheck.pl				       gff_utils					       serverSideLogs
caseManager.pm			   cnvReportedSegments1.pl			       graphGen.pl					       setNightlyTestBuild
caseManager.pm.jose.backup	   cnvReportedSegments_old.pl			       hideLastLines					       sff2fastq
caseManagerSystemRequirements.sh   cnvReportedSegments.pl			       images						       SFF_Extract
caseManagerUtilities.pm		   cnvReportedSeg_sneha.pl			       imap_fasta2match.pl				       sff_info
caseManagerWa.pm		   CNV_validateSeqments_vcf.pl			       instrumentDataScan_1				       sfr2_nohup
caseManagerWa.pm.bak		   color_to_base_seq.pl				       instrumentDataScanBeadCount			       sfr2.sh
caseManagerWa.pm.bak.jose	   columnsToKeyValuePair.pl			       instrumentDataScanFocalMapMedian			       sfr_nohup
cf				   compareFiles.sh				       instrumentDataScanFocalMapMedianLocal		       sfr.sh
changeExtensions.sh		   ComparisonOfWorkflowRuns			       javascripts					       shortTermTools
checkFailOutput.pl		   compUniqPrimaryVsAllAlignmnets.pl		       jblock						       showCommanLineOption.pl
checkMultiAnchorFromLog.pl	   concurrent_run_launcher.sh			       jcompile.sh					       showstats.py
checkNumOfIterations.pl		   concurrent_run_monitor_new.pl		       jingValidate_CIGAR_length_Frag_LMP.pl		       simulateContigs.pl
checkPassOutput.pl		   concurrent_run_monitor.pl			       jpblock						       smallIndelPathUpdate.sh
checkUnKilledBioscopeProcesses.sh  concurrent_workflows_launcher.pl		       jrun.sh						       sortByBeadIDs.sh
classifyMaByHits.pl		   convert_color_to_base_seq.pl			       jtools						       splitFastaToContigs.pl
CleanScratch			   convertToCoordsLatest			       killPBSJobs.sh					       split_var2snp_indels_mnv_vcf.py
cm1autoStart			   countBaseErrors.pl				       killServer.pl					       src
cm1autoStart_nohup		   countPattern.sh				       largeIndelPathUpdate.sh				       ssh-keyPush
cm2autoStart			   coverageResultValidator.jar			       launchAnalysises.pl				       ssh-keyPush.old
cm2autoStart_nohup		   cphere					       launchClients.pl					       subtractMappedReads.pl
cm2backup			   cpthere					       launchServer.pl					       tempTools1
cm2baseline			   createMergedBam.sh				       ldir						       tertiary_analysis
cm2cases			   createNupdateCases.sh			       ldirs						       test
cm2completelyStopANightlyTest	   createSqf.pl					       lfile						       testCaseCreationAndUpdation.pl
cm2goto				   createWorkflowTestCases.pl			       lfiles						       testCaseCreationAndUpdation_tmap.pl
cm2input			   csfastaToXSQ					       lib						       timeParser
cm2makeNewSuite			   csfasta_validation.pl			       library_xsq					       Time_Reporter.pm
cm2nightly			   csmanager					       linesFrom					       tmapbam
cm2results			   csmgr					       listFilesAndContents				       Tmap_TS_IR_Parity.sh
cm2status			   csmgrLocation				       ListScratch					       todays
cm2suites			   DatasetColorEncoding.sh			       localmapCounts.sh				       todaysTime
cm3baseline			   decode_All_XSQ_Index_reads_to_ColorQuality.pl       localVsProgressive.sh				       toolData
cm3bugs				   decode_All_XSQ_Index_reads_to_ColorQuality.sh       log						       toolData_era2
cm3bugsFrag			   decode_All_XSQreads_to_BaseQuality.pl	       log_extract.sh					       toolData_era3
cm3cases			   decode_All_XSQreads_to_BaseQuality.sh	       logScratchExtract.sh				       toolData_era5
cm3input			   decode_All_XSQreads_to_ColorQuality_ASCII.pl        logScratch.sh					       trimReadLength.pl
cm3makeNewSuite			   decode_All_XSQreads_to_ColorQuality_ASCII.sh        maConsolidator.sh				       updateCoronaVersionFile
cm3results			   decode_All_XSQreads_to_ColorQuality_barcoded.sh     MainTemplateXSQ.java				       updateFrameWork.sh
cm3suites			   decode_All_XSQreads_to_ColorQuality.sh	       maintenance					       updateJars.sh
cm4baseline			   decodeColorCallQV.pl				       mappedBeadCount.sh				       updateMe.sh
cm4bugs				   decode_samflags.pl				       [mapped in proper pair,				       update_testcases.pl
cm4cases			   decode_Start_End_XSQreads_to_ColorQuality.sh        mappingValidator					       upload.sh
cm4input			   decode_XSQreads_to_ColorQuality.pl		       matchAndLinkTestInputsAutomatically		       ValidateBAM.jar
cm4makeNewSuite			   deleteOldArchieve.py				       matchGatherCheck.pl				       Validate_CIGAR_length_Frag_LMP.pl
cm4results			   deleteOldBioscope.py				       matchingCounts.sh				       Validate_CIGAR_length_PE.pl
cm4suites			   deleteOldCorona.py				       matchingStatistics.sh				       Validate_Indels_in_CIGAR.pl
cm5baseline			   deleteOldLifescope.py			       matchKnownTestInput				       validate_reads_in_csfasta_BCXSQ_Frag.sh
cm5bugs				   derby.log					       matchKnownTestInput2				       validate_reads_in_csfasta_XSQ_Frag.sh
cm5cases			   devLicenses					       matchThroughputCheck.pl				       validate_reads_in_csfasta_XSQ_LMP_PE.sh
cm5input			   dicerBackup					       [mate is reverse,				       validate_reads_in_fastq_XSQ_Frag.sh
cm5makeNewSuite			   DiffBam.jar					       [mate is unmapped],				       validate_reads_in_fastq_XSQ_LMP_PE.sh
cm5results			   diffGFF					       matesReportGatherCheck.pl			       validateRoc.pl
cm5suites			   diffKeyValueFiles.jose.pl			       mc						       ValidateRunMetada_fastq_XSQ.sh
cmabortOff			   diffKeyValueFiles.pl				       mergeSortTags.pl					       ValidateRunMetada.sh
cmabortOn			   diffMatch					       missingTagIDCheck.pl.bak1			       validateTiTvRatio.pl
cmarchive			   diffSingleRead				       missingTagIDExtract.pl				       variantCaller_validator
cmarchive.Orig			   diffSingleRead.bak				       moduleTimings.pl					       VariantsReported.pl
cmautoStart			   diffWoComment				       monitoredRun					       vcf2gvcf_v2.py
cmautoStart_nohup		   dirContent_validate5.pl			       monitorNodes					       VcfStats
cmbackup			   dirContent_validate.pl			       monitorTimeOnly					       verifyScheme
cmbaseline			   dirContent_validate.pl.backup.beforesamFieldSorter  mqv2ma.pl					       verifyStep
cmbuildFlags			   duHere					       mqvFiltering.pl					       ViewStatus
cmbuildlist			   dvi						       mvthere						       waitForAPID
cmbuildlistvm			   encodeSequence.pl				       mytestcheckin					       waitForPbsJobComplete.pl
cmbuildMachine			   encodeSequence.pl~				       nightlyTestAutomationScripts			       waitForPBSSession
cmcases				   EnrichmentValidationTool.jar			       NumReadsPassed.sh				       waitForPBSStatus
cmcompletelyStopANightlyTest	   Error.txt					       outdated_scripts					       whatsinvv
cmCopyToBugs			   examine_beadBoundariesOfMaToBamSplits.sh	       pairingCategory_validate.pl			       whichBioscope
cmdataStorage			   examineLogsForDuration.sh			       pairing.dat_validate.pl				       which_workflow.pl
cmfr_nohup			   extract_all_groups.sh			       parseOutput.pl					       workflow_mon.pl
cmfr.sh				   extractBeadCounts				       parse_test_V1_F3.stats.txt.pl			       workflow_runner_custom.sh
cmgetBuildCoreTool		   extract_main_info_fastq_converted_XSQ.sh	       perfDataAverage.pl				       workflow_runner.sh
cmgetCorrectedLink		   extract_main_info_XSQ.sh			       perfHtmlGen.pl					       workflows_launcher.pl
cmgetLatestBuild		   extractQVFileSubSet.pl			       perfLogParser.pl					       workflows_suite_updater.pl
cmgetLatestBuild2.0		   extractReadsFromMappedSam.pl			       perfMakeCharts.pl				       workflow_stats.pl
cmgetLatestBuild2.1		   extractTagsForMerge1.pl			       picard						       WT_Alignments.pl
cmgetLatestBuildCP		   extractTagsForMerge.pl			       picard-tools-1.08				       WT_Compare13v20.pl
cmgetLatestNightlyBuild		   extract_XSQ_ids_barcoded.sh			       pipelineModuleTimingsFromLogs.sh			       wtCountResultValidator.jar
cmgetLatestNightlyBuild2.0	   extract_XSQ_Index_read_ids.sh		       pluginXmlFix.sh					       xsqconvert
cmgetLatestNightlyBuild2.1	   extract_XSQ_read_ids_csfasta_format.sh	       pluginXmlFix.sh.dir				       XSQConverter
cmgetNextNightlyBuild		   extract_XSQ_read_ids.sh			       positionErrorsGatherCheck.pl			       XSQ_read_extract.pl
cmgetNextNightlyBuild2.1	   FastqCIGAR.jar				       prepareResumeData.sh				       XSQ_Split_by_Panel.sh
cmgetNextNightlyBuild2.5	   fcat						       print_bam_header.jar				       XSQ_Tools_for_New_ECC.tar.gz
[liy15@jagger tools]$ cd Validate
ValidateBAM.jar                    Validate_CIGAR_length_PE.pl        ValidateRunMetada_fastq_XSQ.sh     
Validate_CIGAR_length_Frag_LMP.pl  Validate_Indels_in_CIGAR.pl        ValidateRunMetada.sh               
[liy15@jagger tools]$ cd variantCaller_validator
[liy15@jagger variantCaller_validator]$ ls
readme.rst  variantValidator_multi
[liy15@jagger variantCaller_validator]$ vi readme.rst 

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
    $ #germline data takes one truth file
    $ TRUTH_FILES="-t ${MAJOR_TRUTH_FILE}"
    $ #Somatic data takes two truth files
    $ TRUTH_FILES="-t ${MAJOR_TRUTH_FILE} -T ${MINOR_TRUTH_FILE}"

2) Start Validator
    $ variantValidator_multi \
    $ -i "${VARIANT}" \
    $ -F "${VARIANT_filtered}" \
    $ -b ${INPUT_BAM} \
    $ -r ${REF_FILE} \
    $ ${TRUTH_FILES} \
    $ -o ${OUT_FOLDER
~                                                                                                                                                                                        
~                                                                                                                                                                                        
~                                                                                                                                                                                        
~                                                                                                                                                                                        
~                                                                                                                                                                                        
-- INSERT --                                                                                                                                                           16,8          All
