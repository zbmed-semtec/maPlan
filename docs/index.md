# ![](maPlan_logo.png) maPlan Project 

|              |    |    |
:---------------------:|:---------------------:|:---------------------:
![NFDI4DataScience](nfdi4ds_logo_badge.png)  | ![DMP4NFDI](dmp4nfdi.png)  | A metadata service in collaboration between [NFDI4DataScience](https://www.nfdi4datascience.de/) and [DMP4NFDI](https://base4nfdi.de/projects/dmp4nfdi)

## Description

The creation of AI models involve research artifacts such as datasets and software, to finally obtain the AI model itself. These three artifcats should be managed along the research cycle in an integrated and harmonized way.

To achieve this, we propose a machine-actionable AI Research Plan (maPlan), which combines elements from Data Management Plans (DMPs) and Datasheets, Softaware Management Plans (SMPs), and Model Cards, together with metadata layers enabling machine-actionability.

## Current status

At the moment, in collaboration with [NFDI4DataScience](https://www.nfdi4datascience.de/) and [DMP4NFDI](https://base4nfdi.de/projects/dmp4nfdi), we are focusing on DMPs and SMPs plus the metadata layer required by them. 

### Activities at DMP4NFDI

A maDMP is being under development by DMP4NFDI and our [maSMP](https://zbmed-semtec.github.io/maSMPs) will be later integrated to it. In this way, researchers will have the chance to have in one place a management plan for their data together with the software used to collect it and transform it.

### Activities at NFDI4NFD

A management plan for AI models does not exist yet. The closer to it would be the [Machine Learning model cards]((https://doi.org/10.1145/3287560.3287596)). Despite being intially defined for Machine Learning, they work well for Deep Learning and Generative AI (e.g., Large Language Models). We have started with awaraness and outreach on the subject, as they are not yet well adopted.

In addition to ML Model Cards, [Datasheet Cards](https://doi.org/10.48550/arXiv.1803.09010) are also used in AI approaches, to document the data used for training and/or evaluation. Once we have the first integrated DMP+SMP template in DMP4NFDI, we will proceed to extend it so it also includes elements from Datasheet Cards. 

## Related projects in NFDI4DS

[In-silico protocols for AI reproducibility](https://zbmed-semtec.github.io/in-silico-protocols-4ML/) in another project part of NFDI4DS. While maPlan focuses on basic aspected relevant to DMP+SMP activities, in-silico protocols aim at representing the whole AI workflow, from pre-processing to deployment, with rich metadata, so it can be used as a first layer to improve and assess reproducibility. In-silico protocols scope regarding metadata and tools is more comprenhensive that the one from maPlan. maPlan metadata schemas wil reused in in-silico protocols as needed.


__DMPS__
You can find more information on DMPs at [DMP4NFDI](https://base4nfdi.de/projects/dmp4nfdi) and the [Research Data Management Organiser (RDMO)](https://rdmorganiser.github.io/)

__SMPs__
You can find more information on SMPs at [maSMPs](https://zbmed-semtec.github.io/maSMPs/)

## Relevant background sources

* [RDA machine-actionable Data Management Plan (maDMP)](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard)
* [The NFDI DMP template framework](https://doi.org/10.5281/zenodo.16737078)
* NFDI4DS/DMP4NFDI [maSMP](https://doi.org/10.5281/zenodo.7806638)
* [Model cards](https://doi.org/10.1145/3287560.3287596)
* [Datasheets](https://doi.org/10.48550/arXiv.1803.09010)

 