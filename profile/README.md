![wustl logo](https://github.com/wustl-oncology/.github/blob/master/profile/wustl_logo.png?raw=true)

### Code and documentation from the WUSTL Division of Oncology

These repositories represent accumulated tools and knowledge that enable labs to get up and running with cloud computing, mostly using cancer genome analysis as the use case.  Some of the contents include:

- How to get your lab signed up for [Google Cloud access through WUSTL IT](https://github.com/wustl-oncology/cloud-workflows/blob/main/docs/getting_started_gcp.md)
- A lecture and slides on [Getting started on cloud](https://github.com/genome/bfx-workshop/blob/master/lectures/week_25/week25_slides.pdf) with details specific to WUSTL. 
- [End-to-end genomic workflows](https://github.com/wustl-oncology/analysis-wdls) for variant calling, rnaseq analyses, epigenomics, and more.
- Guidance for [running these pipelines (or others)](https://github.com/wustl-oncology/cloud-workflows) on Google Cloud, including complete walkthrough examples of using it to run an immunogenomics pipeline see below.
- Guides to running workflows on the local compute cluster, using [GMS](https://github.com/genome/genome/wiki/CWL-Somatic-Pipeline-Walkthrough) ([example](https://github.com/wustl-oncology/immuno-planning/issues/13)) or [Cromwell](https://cromwell.readthedocs.io/en/latest/) for workflow orchestration 
- [Annotation files pre-loaded on the cloud](https://console.cloud.google.com/storage/browser/griffith-lab-workflow-inputs) that are needed for many of these pipelines, as well as [detailed instructions for creating your own](https://github.com/genome/analysis-workflows/wiki/Gathering-input-files)
- Links to useful resources for analysis, cloud computing, or running workflows on other providers such as [Terra](https://workflow-course.pvactools.org/)

### Tutorials for running WDL workflows

The following github repositories contain tutorials on how to run the immuno workflow, end-to-end in different compute environments. Each tutorial differs in where the data is stored, whether it gets staged somewhere else for compute, the job scheduler used (e.g. GCP Batch, LSF, Slurm), use of cloud vs. on-premises compute, etc. 

- [Data stored on the local storage1 cluster that needs to be staged to Google storage and then processed using Google Cloud Compute](https://github.com/wustl-oncology/immuno_gcp_wdl_compute1)
- [Data stored on the local storage1 cluster, that will be processed using LSF and compute1](https://github.com/wustl-oncology/immuno_lsf_wdl_compute1)
- [A simplified version where data may already be put on the cloud that will be processed using Google Cloud Compute](https://github.com/wustl-oncology/immuno_gcp_wdl_local)
- [Data stored in Google storage and processed using Terra](https://workflow-course.pvactools.org/)
- [Data stored on JHU SafeStor, that will be processed using Slurm and JHU Discovery](https://github.com/wustl-oncology/immuno_slurm_wdl_discovery)
