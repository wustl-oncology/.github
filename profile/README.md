![wustl logo](https://github.com/wustl-oncology/.github/blob/master/profile/wustl_logo.png?raw=true)

### Code and documentation from the WUSTL Division of Oncology

These repositories represent accumulated tools and knowledge that enable labs to get up and running with cloud computing, mostly using cancer genome analysis as the use case.  Some of the contents include:

- How to get your lab signed up for [Google Cloud access through WUSTL IT](https://github.com/wustl-oncology/cloud-workflows/blob/main/docs/getting_started_gcp.md)
- A lecture and slides on [Getting started on cloud](https://github.com/genome/bfx-workshop/blob/master/lectures/week_25/week25_slides.pdf) with details specific to WUSTL. 
- [End-to-end genomic workflows](https://github.com/wustl-oncology/analysis-wdls) for variant calling, rnaseq analyses, epigenomics, and more.
- Guidance for [running these pipelines (or others)](https://github.com/wustl-oncology/cloud-workflows) on Google Cloud, including complete walkthrough examples of using it to run an immunogenomics pipeline from [data you've already put on the cloud](https://github.com/wustl-oncology/immuno_gcp_wdl_local) or from [data stored on the local compute1 cluster ](https://github.com/wustl-oncology/immuno_gcp_wdl_local)
- Guides to running workflows on the local compute cluster, using [GMS](https://github.com/genome/genome/wiki/CWL-Somatic-Pipeline-Walkthrough) ([example](https://github.com/wustl-oncology/immuno-planning/issues/13)) for workflow orchestration or [Cromwell]()
- [Annotation files pre-loaded on the cloud](https://console.cloud.google.com/storage/browser/griffith-lab-workflow-inputs) that are needed for many of these pipelines, as well as [detailed instructions for creating your own](https://github.com/genome/analysis-workflows/wiki/Gathering-input-files)
- Links to useful resources for analysis, cloud computing, or running workflows on other providers such as [Terra](https://support.terra.bio/hc/en-us/categories/360005881492-Getting-Started) or [DNAnexus](https://documentation.dnanexus.com/getting-started)
