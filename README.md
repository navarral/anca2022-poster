# Rare diseases: making environmental health studies’ data as open as possible
[The 20th International Vasculitis and ANCA Workshop | Dublin, Ireland, 3-6 April 2022](https://vasculitis2022.org/)
## Authors
Albert Navarro-Gallinad* <sup>1</sup>, Maria Christofidou<sup>2</sup>, Solange Gonzalez Chiappe<sup>3</sup>, Fabrizio Orlandi<sup>1</sup> and Declan O’Sullivan<sup>1</sup>

<sup>1</sup> ADAPT Centre for Digital Content, Trinity College Dublin, Dublin, Ireland

<sup>2</sup> The European Institute for Innovation Through Health Data (i-HD), Ghent, Belgium

<sup>3</sup> Department of Rheumatology, Kantonsspital St.Gallen, St. Gallen, Switzerland

## Background
Researchers are confronted with increased data protection risks when trying to publish in an open manner data related to their studies into environmental factors related to rare diseases, even if the data is pseudonymised. Identification risks exist for the patients being studied, in terms of singling out an individual, data linking with other sources, or inferencing certain data from the linked data [1]. In addition, effective anonymization methods cannot be applied without losing the value of the data for research with low sample sizes, as in rare diseases [2]. For example, permuting the environmental observations would affect the temporality of the data or introducing noise would affect the magnitude of the values. Both methods can potentially hide the signal that the researchers are looking for.

## Methods
The approach we recommend is to publish example patient event-environmental linked data and its associated metadata, which could be shared as Open Data following the Findable Accessible Interoperability and Reusability (FAIR) guiding principles. In our approach, we recommend the example data and metadata are described using the Resource Description Framework ([RDF](https://www.w3.org/TR/1999/REC-rdf-syntax-19990222/)), a standard graph data model, following W3C standards and recommendations for statistical data ([RDF Data Cube](https://www.w3.org/TR/vocab-data-cube/)), dataset descriptors ([DCAT](https://www.w3.org/TR/vocab-dcat-2/)), provenance and lineage ([PROV-O](https://www.w3.org/TR/prov-o/)); and data protection domains ([DPV](https://w3c.github.io/dpv/dpv/)). We then recommend that the data and associated metadata is published in an open repository preferred by your community generating a unique Digital Object Identifier (DOI) for the dataset.

## Results
An example of a dataset that has been published in an open manner according to our proposed approach can be found at the following DOI: https://doi.org/10.5281/zenodo.5544257. The dataset is an example result of associating air pollution and weather data subsets to particular health events within a region in the Republic of Ireland, together with the relevant metadata fields. The implementation of the FAIR guiding principles was applied on the necessary metadata and a Data Protection Impact Assessment, in accordance with the GDPR, [3] was created, therefore ensuring good data protection practices were met to assess the necessary risks that could arise.

## Conclusions
The approach proposed would facilitate data publication as open as possible for researchers studying rare disease environmental risk factors. Furthermore, the data pre-processing step will be recorded in the metadata (i.e., a transparent record) enhancing the data re-use of researchers in the community and stakeholders.

## Disclosures
The authors have declared no conflicts of interest.

## Acknowledgements
This research was conducted with the financial support of HELICAL as part of the European Union’s Horizon 2020 research and innovation programme under the Marie Sklodowska-Curie Grant Agreement No. 813545 and No. 713567 at the ADAPT Centre for Digital Content Technology (grant number 13/RC/2106 P2) at Trinity College Dublin, collaborating with the European Institute for Innovation through Health Data (i~HD).

## References
[1] [Data Protection Commission, 2019. Guidance on Anonymisation and Pseudonymisation.](https://www.dataprotection.ie/sites/default/files/uploads/2020-09/190614%20Anonymisation%20and%20Pseudonymisation.pdf)

[2] [Boronow, K.E., et al., 2020. Privacy risks of sharing data from environmental health studies. Environmental health perspectives, 128(1), p.017008.](https://doi.org/10.1289/EHP4817)

[3] [Article 35(1), Article 35 (3), Article 36 and Recitals 89 to 96 of the General Data Protection Regulation (GDPR).](https://gdpr-info.eu/art-35-gdpr/)
