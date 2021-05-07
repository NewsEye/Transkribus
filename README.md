# Transkribus
WP1 - Data generation (GT, LA, ATR, exchange results)

The Transkribus platform (https://transkribus.eu) was developed during the following EU-projects:
*	Transcriptorium (2013-2015): http://transcriptorium.eu/
*	READ (2016-2019): http://read.transkribus.eu
## Description
Although originally developed for handwritten text recognition (HTR) it turned out that the tools and methods are also suitable to produce excellent results for printed material. As part of the NewsEye project the Transkribus platform was enhanced and augmented with new features and tools for processing historical newspapers. It was adapted to the requirements set up by deliverable D1.9 Data models (d), namely the inclusion of features for data exchange and export.  

Moreover Transkribus was used to manage the creation of the required training data necessary for the models and tools of the other work packages and their evaluation in the NewsEye project. This includes mainly data for
*	LA - layout analysis (WP3)
*	ATR - automated text recognition (WP3)
*	AS - article separation (and other structural elements) (WP3)
*	NER - named entity recognition (WP4)
*	NEL - named entity linking (WP4)
*	SD - stance detection (WP4)

For this purpose, the Transkribus platform thas been extended and enriched with additional methods for annotating articles and other structural elements, for creating named entities including links and stances and for exporting data in the required formats.
And finally Transkribus was also used to process about 1,5 mill. newspaper pages with the tools developed by UROS in WP3: layout analysis and ATR and has acted as exchange platform for the 'AS processing' and the ‘Demonstrator’. The latter means that the intermediate and final results were shared via the Transkribus REST API.

The Transkribus GitHub repository can be found at https://gitlab.com/readcoop/transkribus/.

The repositories needed to run the local SWT based client are:
*	PdfUtils
*	fimagestore-http-client
*	TranskribusCore
*	TranskribusClient
*	TranskribusSwtGui

It is recommended to check them out with Eclipse, to configure them as Maven projects and run "maven install" on them in the given order.

## Relevant Transkribus GitHub Repositories for NewsEye:
*	https://gitlab.com/readcoop/transkribus/PdfUtils
*	https://gitlab.com/readcoop/transkribus/fimagestore-http-client
*	https://gitlab.com/readcoop/transkribus/TranskribusCore
*	https://gitlab.com/readcoop/transkribus/TranskribusClient
*	https://gitlab.com/readcoop/transkribus/TranskribusSwtGui
*	https://gitlab.com/readcoop/thirdparty/TranskribusPyClient
*	https://gitlab.com/readcoop/thirdparty/TranskribusErrorRate
