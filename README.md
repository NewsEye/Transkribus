# Transkribus
WP1 - Data generation (GT, LA, ATR, exchange results)

The Transkribus platform (https://transkribus.eu) was developed during the following EU-projects:
*	Transcriptorium (2013-2015): http://transcriptorium.eu/
*	READ (2016-2019): http://read.transkribus.eu
## Description
Although originally developed for handwritten text recognition (HTR) it turned out that the tools and methods are also suitable to produce excellent results for printed material. As part of the NewsEye project the Transkribus platform will be enhanced and augmented with new features and tools for processing historical newspapers. It will also be adapted to the requirements set up by deliverable D1.3 Data models (b), namely the inclusion of IIIF features for data exchange and export.

Moreover Transkribus gets used to manage the generation of ground truth data for most of the research groups in the NewsEye project. This includes mainly data for
*	LA - layout analysis (WP3)
*	ATR - automated text recognition (WP3)
*	AS - article separation (and other structural elements) (WP3)
*	NER - named entity recognition (WP4)
*	NEL - named entity linking (WP4)
*	SD - stance detection (WP4)

And finally Transkribus will process about 1,5 mill. newspaper pages with the tools developed by UROS in WP3: layout analysis and ATR and acts as exchange platform for the 'AS processing' and the ‘Demonstrator’. The latter means that the intermediate and final results are shared via the Transkribus REST API.

The Transkribus GitHub repository can be found at https://gitlab.com/readcoop/transkribus/.

The repositories needed to run the local SWT based client are:
*	PdfUtils
*	fimagestoreClient
*	TranskribusCore
*	TranskribusClient
*	TranskribusSwtGui

It is recommended to check them out with Eclipse, to configure them as Maven projects and run "maven install" on them in the given order.

## Relevant Transkribus GitHub Repositories for NewsEye:
*	https://gitlab.com/readcoop/transkribus/PdfUtils
*	https://gitlab.com/readcoop/transkribus/fimagestore-http-client
*	https://gitlab.com/readcoop/transkribus/TranskribusClient
*	https://gitlab.com/readcoop/transkribus/TranskribusCore
*	https://gitlab.com/readcoop/transkribus/TranskribusSwtGui
*	https://gitlab.com/readcoop/thirdparty/TranskribusPyClient
*	https://gitlab.com/readcoop/thirdparty/TranskribusErrorRate
