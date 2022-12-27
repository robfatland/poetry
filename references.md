[das repository home](http://github.com/robfatland/das)


## USGS article: Seismology in the cloud; a new streaming workflow

MacCarthy, Jonathan, Marcillo, Omar, Trabant, Chad

Seismological research letters, 2020, Vol.91 (3), p.1804-1812

#### Description

Data-intensive research in seismology is experiencing a recent boom, driven in part by large 
volumes of available data and advances in the growing field of data science. However, there 
are significant barriers to processing large data volumes, such as long retrieval times from 
data repositories, complex data management, and limited computational resources. New tools 
and platforms have reduced the barriers to entry for scientific cluster computing, including 
the maturation of the commercial cloud as an accessible instrument for research. In this 
work, we build a customized research cluster in the cloud to test a new workflow for 
large-scale seismic analysis, in which data are processed as a stream (retrieved on-the-fly 
and acted upon without storing), with data from the Incorporated Research Institutions 
for Seismology Data Management Center. We use this workflow to deploy a spectral peak 
detection algorithm over 5.6 TB of compressed continuous seismic data from 2074 stations 
of the USArray Transportable Array EarthScope network. Using a 50-node cluster in the 
cloud, we completed the noise survey in 80 hr, with an average data throughput of 1.7 GB 
per minute. By varying cluster sizes, we find the scaling of our analysis to be sublinear, 
due to a combination of algorithmic limitations and data center response times. The 
cloud-based streaming workflow represents an order-of-magnitude increase in acquisition 
and processing speed compared to a traditional download-store-process workflow, and offers 
the additional benefits of employing a flexible, accessible, and widely used computing 
architecture. It is limited, however, due to its reliance on Internet transfer speeds 
and data center service capacity, and may not work well for repeated analyses or those 
for which even higher data throughputs are needed. These research applications will 
require a new class of cloud-native approaches in which both data and analysis are in the cloud.

#### Metadata

- United States: Seismological Society of America
- Identifier
- ISSN: 0895-0695
- EISSN: 1938-2057
- DOI: 10.1785/0220190357


## QuakeFlow: a scalable machine-learning-based earthquake monitoring workflow with cloud computing

- Zhu, Weiqiang and 6 others
- Geophysical journal international, 2022, Vol.232 (1), p.684-693

#### Description
SUMMARY Earthquake monitoring workflows are designed to detect earthquake signals and 
to determine source characteristics from continuous waveform data. Recent developments 
in deep learning seismology have been used to improve tasks within earthquake 
monitoring workflows that allow the fast and accurate detection of up to orders 
of magnitude more small events than are present in conventional catalogues. To 
facilitate the application of machine-learning algorithms to large-volume seismic 
records at scale, we developed a cloud-based earthquake monitoring workflow, 
QuakeFlow, which applies multiple processing steps to generate earthquake catalogues 
from raw seismic data. QuakeFlow uses a deep learning model, PhaseNet, for picking 
P/S phases and a machine learning model, GaMMA, for phase association with 
approximate earthquake location and magnitude. Each component in QuakeFlow is 
containerized, allowing straightforward updates to the pipeline with new deep 
learning/machine learning models, as well as the ability to add new components, 
such as earthquake relocation algorithms. We built QuakeFlow in Kubernetes to 
make it auto-scale for large data sets and to make it easy to deploy on cloud 
platforms, which enables large-scale parallel processing. We used QuakeFlow to 
process three years of continuous archived data from Puerto Rico within a few 
hours, and found more than a factor of ten more events that occurred on much 
the same structures as previously known seismicity. We applied Quakeflow to 
monitoring earthquakes in Hawaii and found over an order of magnitude more 
events than are in the standard catalogue, including many events that illuminate 
the deep structure of the magmatic system. We also added Kafka and Spark streaming 
to deliver real-time earthquake monitoring results. QuakeFlow is an effective 
and efficient approach both for improving real-time earthquake monitoring and 
for mining archived seismic data sets.

#### Metadata

- Publisher
- Ithaca: Oxford University Press
- Identifier
- ISSN: 0956-540X
- EISSN: 1365-246X
- EISSN: 2331-8422
- DOI: 10.1093/gji/ggac355
