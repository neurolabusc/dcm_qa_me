
## About

dcm_qa_me is a simple DICOM to NIfTI validator script to test conversion of Siemens [multi-echo sequences](https://github.com/neurolabusc/dcm_qa/issues/8) images. This data plus a larger multi-echo T1 scan are also available on [NITRC](https://www.nitrc.org/plugins/mwiki/index.php/dcm2nii:MainPage#Unusual_MRI).

## DataSets

* me_FieldMapGRE
  * Siemens Prisma D13D
  * Gradient Echo Fieldmap
  * Echo Times: 5.19, 7.65ms
  * Note: instance numbers are not unique for this series.
  
* me_fMRI
  * Siemens Prisma D13D
  * T2* BOLD sequence
  * Echo Times: 20.00, 37.83ms
