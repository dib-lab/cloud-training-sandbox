# Cloud training materials development

## Topics for discussion

We're not at the stage where we can define clear learning objectives yet (that's why we're running this workshop!), but there are some central topics that will likely result in core learning objectives for the materials we develop at the workshop.

- bare basics of cloud resource provisioning
    - big computer in a warehouse somewhere that offers temporary on-demand access to a portion of its CPU, RAM, and storage capacity
- different ways of managing software configurations in the cloud; related services / technologies
    - *ad hoc*: lowest barrier of entry, ultimate flexibility, reproducibility nightmare
    - "lab notebook" approach: follow pre-canned install instructions with each new VM (similar to Eel Pond)
    - AMI with pre-installed software
    - Docker, and Dockstore (vs DockerHub)
- costs of inbound vs outbound data transfer
- cloud data storage
    - VM root partition vs block storage
    - persistence of different types of storage
    - data set provisioning; snapshots of EBS storage
    - costs for storage and use (and outbound transfer)
- accessing data from data commons
    - discoverability
        - which databases/commons exist, and how do I find them??
        - how do I search for data sets within a database/commons?
    - data access / transfer
- cost model, estimation
    - direct costs for using commercial providers
    - making estimates for XSEDE allocation requests

Related topics that may or may not warrant additional discussion.

- workflow execution
- domain-specific platforms

## Use cases

During the materials development workshop at DIBSI, we will focus on one or more use cases as a way of anchoring our discussion about what cloud-related compentencies a particular scientist or group of scientists will need to be successful.
Here are some ideas.

- single scientist, GWAS analysis on Rice 3k genome data
- bioinformatics core facility, deploying an RNA-seq processing pipeline
- research consortium, distributing data and analysis code for a collaborative project
