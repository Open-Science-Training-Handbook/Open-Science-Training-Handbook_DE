## <img src="/Images/Icons/open_data.png" width="200" height="200" />
## 2. Offene Forschungsdaten und Materialien

### Was ist das?

Offene Forschungsdaten sind Daten, die für akademische Forschung, Lehrzewecke und darüber hinaus frei zugänglich sind, wiederverwendet und weiterverteilt werden können. Im Idealfall haben offene Daten (Open Data) keine Einschränkungen bei der Wiederverwendung oder Weitergabe und werden entsprechend lizenziert. In Ausnahmefällen, z.B. zum Schutz der Identität von Menschen, werden besondere oder begrenzte Zugangsbeschränkungen festgelegt. Die Offenlegung von Daten ermöglicht ihre Überprüfung, was die Grundlage für die Verifizierbarkeit und Reproduzierbarkeit von Forschung bildet und einen Weg zu einer breiteren Kollaboration eröffnet. Open Data können höhstens der Namensnennung und der Weitergabe unter den gleichen Lizenzbedingungen unterliegen \((siehe das [Open Data Handbook](http://opendatahandbook.org/guide/en/what-is-open-data)\).


## <img src="/Images/Icons/data2.png" width="150" height="150" />
### Einleitung

Forschungsdaten sind oft der wertvollste Output vieler Forschungsprojekte. Sie werden als primäre Quellen genutzt, die die wissenschaftliche Forschung unterstützen und die Ableitung theoretischer oder angewandter Erkenntnisse ermöglichen. Um Erkenntnisse/Studien replizierbar, oder zumindest reproduzierbar oder auf eine andere Weise wiederverwendbar zu machen \(siehe [Reproducible Research And Data Analysis](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md)\), ist die Best-Practice-Empfehlung für Forschungsdaten: so offen und [FAIR](https://www.force11.org/fairprinciples) wie möglich, wobei ethische, kommerzielle und datenschutzrechtliche Einschränkungen bei sensiblen Daten oder geschützten Daten berücksichtigt werden müssen.


## <img src="/Images/Icons/finish.png" width="150" height="150" />

### Lernziele

1. Verständnis für die grundlegenden Merkmale und Prinzipien von offenen und FAIRen Forschungsdaten, einschließlich geeigneter Aufbereitung und Dokumentation gewinnen, damit andere sie verstehen, reproduzieren und auf alternative Weise wiederverwenden können.

2. Umgang mit der Art von Daten erlernen, die als sensibel angesehen werden können, und mit den Einschränkungen diese offen weiterzugeben.

3. Die Fähigkeit entwickeln, einen "geschlossenen" Datensatz in einen "offenen" umzuwandeln, indem die erforderlichen Maßnahmen mit entsprechender Datenpflege und Metadaten in einem Datenmanagementplan implementiert werden.

4. Die Fähigkeit entwicklen, einen Datenmanagementplan zu nutzen und  Forschungsergebnisse auffindbar und zugänglich zu machen, auch wenn sie sensible Daten enthalten.

5. Die Vor- und Nachteile der offenen Weitergabe verschiedener Arten von Daten \(z.B. Datenschutz, Sensibilität, De-Identifikation, vermittelte Zugriffe\) verstehen.

6. Die Bedeutung geeigneter Metadaten für eine nachhaltige Archivierung von Forschungsdaten verstehen.

7. Die grundlegenden Abläufe und Werkzeuge für die Weitergabe von Forschungsdaten verstehen.

### Hauptbestandteile
## <img src="/Images/Icons/brain.png" width="150" height="150" /><img src="/Images/Icons/gears.png" width="150" height="150" />
#### Grundwissen & Fähigkeiten
##### Die FAIR-Prinzipien

Im Jahr 2014 wurde ein Kernsatz von Prinzipien erarbeitet, um die Wiederverwendbarkeit von Forschungsdaten zu optimieren, die sogenannten [FAIR Data Principles](https://www.force11.org/group/fairgroup/fairprinciples)\(FAIR-Prinzipien\). Sie stellen eine von der Gemeinschaft entwickelte Reihe von Richtlinien und bewährten Verfahren dar, um sicherzustellen, dass Daten oder digitale Objekte auffindbar \(**F**indable\), zugänglich \(**A**ccessible\), interoperabel \(**I**nteroperable\) und wiederverwendbar \(**R**e-usable\) sind:

**Auffindbar:** Das erste, was gegeben sein muss, um Daten wiederverwendbar zu machen, ist die Möglichkeit, sie zu finden. Es sollte einfach sein, die Daten und Metadaten sowohl für Menschen als auch für Computer zu finden. Die automatische und zuverlässige Erkennung von Datensätzen und Diensten hängt von maschinenlesbaren persistenten Identifikatoren \(PIDs\) und Metadaten ab.

**Zugänglich:** Die (Meta-)Daten sollten durch ihren Identifikator unter Verwendung eines standardisierten und offenen Kommunikationsprotokolls abrufbar sein - möglicherweise unter Verwendung von Authentifizierungs- und Autorisierungsschritten. Darüberhinaus sollten Metadaten verfügbar sein, auch wenn die Daten nicht mehr verfügbar sind.

**Interoperabel:** Die Daten sollten mit anderen Daten oder Tools kombiniert und verwendet werden können. Das Format der Daten sollte daher für verschiedene Werkzeuge, einschließlich anderer Datensätze, offen und interpretierbar sein. Das Konzept der Interoperabilität gilt sowohl auf Daten- als auch auf Metadatenebene. Beispielsweise sollten die \(Meta-\)Daten Vokabulare verwenden, die den FAIR-Prinzipien entsprechen.

**Wiederverwendbar:** Schließlich zielt FAIR darauf ab, die Wiederverwendung von Daten zu optimieren. Um dies zu erreichen, sollten Metadaten und Daten gut beschrieben sein, damit sie in verschiedenen Situationen repliziert und/oder kombiniert werden können. Auch die Wiederverwendung der \(Meta-\)Daten sollte mit \(einer\) klaren und zugänglichen Lizenz\(en\) angegeben werden.

Im Gegensatz zu Peer-Initiativen, die sich auf den Menschen konzentrieren, legen die FAIR-Prinzipien einen besonderen Schwerpunkt auf die Verbesserung der Fähigkeit von Maschinen, Daten oder digitale Objekte automatisch zu finden und zu verwenden, sowie auf die Unterstützung der Wiederverwendung der Daten durch Einzelpersonen. Die FAIR-Prinzipien sind Leitsätze, keine Standards. FAIR beschreibt Eigenschaften oder Verhaltensweisen, die erforderlich sind, um Daten maximal wiederverwendbar zu machen \(z.B. Dokumentation, Zitation\). Diese Qualitäten können durch verschiedene Standards erreicht werden.

![](/Images/02%20Open%20Science%20Basics/02_open_research_data_material.png)

##### Publikation von Daten

Die meisten Forschenden sind mit der Open-Access-Veröffentlichung von Forschungsartikeln und Büchern mehr oder weniger vertraut \(siehe Kapitel 5\). Seit Kurzem und aus den oben genannten Gründen hat die Datenveröffentlichung zunehmend an Bedeutung gewonnen. Immer mehr Geldgeber erwarten, dass die in den von ihnen finanzierten Forschungsprojekten gewonnenen Daten auffindbar, zugänglich und so offen wie möglich sind.

Es gibt verschiedene Möglichkeiten, Forschungsdaten zugänglich zu machen, darunter \([Wikipedia](https://en.wikipedia.org/wiki/Data_publishing)\):

* Veröffentlichung von Daten als ergänzendes Material im Zusammenhang mit einem [Forschungsartikel](https://en.wikipedia.org/wiki/Research_article), typischerweise mit den vom Herausgeber des Artikels gehosteten Daten.

* Bereitstellen von Daten auf einer öffentlich zugänglichen Website mit Dateien zum Herunterladen.

* Ablegen von Daten in einem Repositorium, das zur Unterstützung der Datenpublikation entwickelt wurde, z.B. [Dataverse](https://en.wikipedia.org/wiki/Dataverse), [Dryad](https://en.wikipedia.org/wiki/Dryad_(repository)), [figshare](https://en.wikipedia.org/wiki/Figshare), [Zenodo](https://en.wikipedia.org/wiki/Zenodo).

* Es gibt eine Vielzahl von allgemeinen und fachspezifischen Datenrepositorien, die die Forschenden bei der Publikation ihrer Daten zusätzlich unterstützen können.

* Veröffentlichung eines Data-Papers zum Datensatz, das als Preprint, in einem Journal oder in einem Data-Journal veröffentlicht werden kann, welches der Unterstützung von Data-Papern dient. Die Daten können vom Journal oder separat in einem Repositorium bereitgestellt werden. Beispiele für Data-Journals sind [Scientific Data](https://www.nature.com/sdata/) \(by SpringerNature\) und das [Data Science Journal](http://www.codata.org/publications/data-science-journal) \(by CODATA\). Für eine umfassende Übersicht über Data-Journals siehe [Candela et al](https://doi.org/10.1002%2Fasi.23358).

Der CESSDA ERIC [Expert tour guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Data-publishing-routes) gibt einen Überblick über Vor- und Nachteile der verschiedenen Wege der Datenpublikation. Manchmal fordert der Geldgeber oder eine andere externe Partei, dass ein bestimmtes Repositorium verwendet wird. Wenn die Auswahl jedoch offen ist, sollte die Reihenfolge der Präferenzen in den [Empfehlungen von OpenAIRE](https://www.openaire.eu/opendatapilot-repository-guide) berücksichtigt werden: 

1. Verwende ein externes Datenarchiv oder Repositorium, das bereits für Deine Forschungsdomäne eingerichtet wurde, um die Daten nach anerkannten Standards in Deiner Disziplin zu sichern.

2. Verwende, falls verfügbar, ein institutionelles Forschungsdaten-Repositorium oder die etablierten Datenverwaltungseinrichtungen Deiner Forschungsgruppe.

3. Verwende ein kostenloses Datenrepositorium wie [Dataverse](https://dataverse.org/), [Dryad](https://datadryad.org/pages/faq#depositing-cost), [figshare](https://figshare.com/) oder [Zenodo](https://zenodo.org/).

4. Suche nach anderen Datenrepositorien in [re3data](https://www.re3data.org/). Es gibt keine einzelne Filteroption in re3data, die die FAIR-Prinzipien abdeckt, aber die folgenden Filteroptionen helfen, FAIR-kompatible Repositorien zu finden: Zugriffskategorien, Datennutzungslizenzen, vertrauenswürdige Datenrepositorien \(mit Zertifikat oder explizit nach Archivstandards\) und ob ein Repositorium den Daten einen persistenten Identifikator \(PID\) vergibt. Ein weiterer zu berücksichtigender Aspekt ist, ob das Repositorium Versionierung unterstützt.

## <img src="/Images/Icons/archive.png" width="150" height="150" />
You should consider where to deposit and publish your data already in your research data management plan. CESSDA offers some practical questions, which are recommended to be considered. For example: Which data and associated metadata, documentation and code will be deposited? How long does the data need to be retained? For how long should the data remain reusable? How will the data be made available? What access category will you choose? For more questions check [Adapt your DMP: part 6](https://www.cessda.eu/Research-Infrastructure/Training/Expert-Tour-Guide-on-Data-Management/6.-Archive-Publish/Adapt-your-DMP-part-6). On the other hand don’t forget to check if a chosen repository meets requirements of your research and of your funder. Some repositories have already gained certification, like CoreTrustSeal, which certifies them to be trustworthy and to be able to meet Core Trustworthy Data Repositories Requirements. It is worth mentioning that some domain specific repositories may accept only high-quality data with a potential for reuse and that can be publicly shared.

Since there are several routes to publish your data, you should note that for a dataset to "count" as a publication, it should follow a similar publication process as an article \([Brase et al., 2009](https://doi.org/10.3233/ISU-2009-0595)\) and should be:

* Properly documented with metadata;

* Reviewed for quality, e.g. content of the study, methodology, relevance, legal consistency and documentation of materials;

* Searchable and discoverable in catalogues \(or databases\);

* Citable in articles.

## <img src="/Images/Icons/metadata.png" width="150" height="150" />
##### Data citation

Data citation services help research communities discover, identify, and cite research data \(and often other research objects\) with confidence. This typically involves the creation and allocation of Digital Object Identifiers \(DOIs\) and accompanying metadata through services such as [DataCite](https://www.datacite.org), and can be integrated with research workflows and standards. This is an emerging field, and involves aspects such as conveying to journal publishers the importance of appropriate data citation in articles, as well as enabling research articles themselves to be linked to any underlying data. Through this, citable data become legitimate contributions to the process of scholarly communication, and can help pave the way for new metrics and publication models that recognize and reward data sharing.

As an initial step towards good practice for data citation, the Data Citation Synthesis Group of FORCE11 has put forward the [Joint Declaration of Data Citation Principles](https://doi.org/10.25490/a97f-egyk), targeted at both researchers and data service providers. Adhering to these principles, data repositories usually provide researchers with a reference they can use when referring to a given dataset.

## <img src="/Images/Icons/database.png" width="150" height="150" />
##### Data packaging

Data packages are containers for describing and sharing accompanying data files, and typically comprise a metadata file describing the features and context of a dataset. This can include aspects such as creation information, provenance, size, format type, field definitions, as well as any relevant contextual files, such as data creation scripts or textual documentation. From the [Data Packaging Guide](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md):

* Data are forever: Datasets outlive their original purpose. Limitations of data may be obvious within their original context, such as a library catalog, but may not be evident once data is divorced from the application it was created for.

* Data cannot stand alone: Information about the context and provenance of the data--how and why it was created, what real-world objects and concepts it represents, the constraints on values--is necessary to helping consumers interpret it responsibly.

* Structuring metadata about datasets in a standard, machine-readable way encourages the promotion, shareability, and reuse of data.

## <img src="/Images/Icons/privacy.png" width="150" height="150" />
##### Sharing sensitive and proprietary data

With appropriate data management planning much sensitive and proprietary data can be shared, reused, and FAIR. The metadata can almost always be shared. Guidance and best practices for sharing sensitive data are necessarily region-specific because of differing regulations \(see for example UKDS’[Companion material for Managing and Sharing Research Data handbook](https://www.ukdataservice.ac.uk/manage-data/handbook)\). [International Association for Social Science Information Services and Technology](http://www.iassistdata.org/resources/data-management/best-practices) keeps a list of international guidance in data management that is a good starting point. There are several approaches and initiatives to help researchers achieve this. [DCC’s DMPonline tool](http://www.dcc.ac.uk/dmponline) includes a number of templates for funders. [The CESSDA Expert Tour Guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection) provides information and practical examples on how to share personal data and on copyright and database issues across the European countries. The Tour Guide also gives an overview on the impact of the GDPR which will harmonize personal data legislation in Europe \(May 2018\), and provides an updated overview on [EU diversity on data protection](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection).[ ](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection)

###### Data brokers

Data brokers are knowledgeable, independent parties who act as data stewards for sensitive data. Researchers can transfer their sensitive data and jurisdiction over access to that data to the broker. This is especially common with patient-level data from clinical studies. Brokers provide a level of independence in the evaluation of whose data requests are scientifically valid and will not violate the privacy of research participants. Examples of data brokers include [The YODA Project](http://yoda.yale.edu/), [ClinicalStudyDataRequest.com](https://www.clinicalstudydatarequest.com/), [National Sleep Research Resource](https://sleepdata.org/) and [Supporting Open Access for Researchers \(SOAR\)](https://dcri.org/our-approach/data-sharing/).

## <img src="/Images/Icons/data.png" width="150" height="150" />
##### Analysis portals

Analysis portals are platforms that allow approved analysis of data without allowing full access \(viewing or downloading\) or controlling where and who gets access. Some data brokers also use analysis portals. Analysis portals control what additional datasets can be pooled with the sensitive data as well as what analyses can be run to ensure that personal information is not revealed during reanalysis. Examples of virtual analysis portals include [Project Data Sphere](https://www.projectdatasphere.org/projectdatasphere/html/home), [Vivli](http://vivli.org/), [RAIRD](http://raird.no/), [Corpuscle](http://clarino.uib.no/korpuskel/page), and [INESS](http://clarino.uib.no/iness/page).

Social science and other researchers with sensitive data use a single-site analysis portal that can be accessed only under controlled regime. Approved researchers can access the data on-site, in a safe room, for scientific purposes. However, the metadata describing the data should be openly available and adhering to the FAIR principles.

##### De-identified and synthetic data

Many datasets containing participant-level private information can be shared once the dataset has been de-identified \(Safe Harbor method\) or a expert has determined that the dataset is not individually identifiable \(Expert Determination method\). Consult with your Research Ethics Board / Institutional Review Board to learn how to do this with your data. We also recommend [the CESSDA Expert Tour Guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection), which provides information and practical examples on how to share personal data. However, some datasets cannot be safely de-identified and shared. Researchers can still improve the openness of research on such data by creating and sharing synthetic data. Synthetic data is similar in structure, content, and distribution to the real data and aims to attain "analytic validity": statistical analysis will return the same results for the synthetic data as the real data. The United States Census Bureau, for example, uses [synthetic data and analysis portals](https://census.gov/content/dam/Census/programs-surveys/sipp/methodology/SSBdescribe_nontechnical.pdf) in combination to allow reuse of highly sensitive data.

###### DataTags

[DataTags](https://datatags.org/) is a framework designed to enable computer-assisted assessments of the legal, contractual, and policy restrictions that govern data sharing decisions. The DataTags system asks a user a series of questions to elicit the key properties of a given dataset and applies inference rules to determine which laws, contracts, and best practices are applicable. The output is a set of recommended DataTags, or simple, iconic labels that represent a human-readable and machine-actionable data policy, and a license agreement that is tailored to the individual dataset. The DataTags system is being designed to integrate with data repository software, and it will also operate as a standalone tool. DataTags is being developed at Harvard University. In Europe, DANS is working on adjusting DataTags to European legislation / General Data Protection Regulation \([GDPR](https://www.eugdpr.org/)\) \(cf. [DANS GDPR DataTags](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)\).

As mentioned above, the ultimate goal of data sharing your research data is to make them maximally reusable. To that end, before sharing your data you should manage them according to best practice. This includes, i.a., documentation and the choice of open file formats and licenses. You can read more about these issues in [Section 4: Reproducible Research and Data Analysis](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md) as well as [Section 6: Open Licensing and File Formats](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/06OpenLicensingAndFileFormats.md).


## <img src="/Images/Icons/usb.png" width="150" height="150" />
##### Open Materials

In addition to data sharing, the openness of research relies on sharing of materials. What materials researchers use is discipline-specific and sometimes unique to a lab. Below are examples of materials you can share, although always confer with peers in your discipline to identify which repositories are used. When you have materials, data, and publications from the same research project shared in different repositories, cross-reference them with a link and a unique identifier so they can be easily located.

###### Reagents

A reagents is a substance, compound or mixture that can be added to a system in order to create a chemical or other reaction. Reagents can be deposited with repositories like [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/), and [ATCC](https://www.atcc.org/) to make them easily accessible to other researchers. License your materials so they can be reused by other researchers.

###### Protocols

A protocol describes a formal or official record of scientific experimental observations in a structured format. Deposit virtual protocols for citation, adaptation, and reuse using [Protocols.](https://www.protocols.io/)[io](https://www.protocols.io/).

###### Notebooks, containers, software, and hardware

Reproducible analysis is aided by the use of literate programming, container technology, and virtualization. In addition to sharing your code and data, also share your Jupyter notebooks, Docker images, or other analysis materials or software dependencies. Share notebooks with Open services such as [mybinder](http://mybinder.org) that allow for public viewing and execution of the entire notebook on shared resources. Containers and notebooks can be shared with [Rocker](https://arxiv.org/abs/1710.03675) or [Code Ocean](https://codeocean.com/). Software and hardware used in your research should be shared following best practices for documentation as outlined in [Section 3](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/03OpenResearchSoftwareAndOpenSource.md). Read-only protocols should be deposited in your disciplines registry such as [ClinicalTrials.gov](https://clinicaltrials.gov/) and [SocialScienceRegistry](https://www.socialscienceregistry.org/) or a general registry like [Open Science](https://osf.io/)[ Framework](https://osf.io/). Many journals, such as [Trials](https://trialsjournal.biomedcentral.com/), [JMIR Research Protocols](https://www.researchprotocols.org/), or [Bio-Protocol](https://bio-protocol.org/), will publish your protocol. Best practices for publishing your protocol open access are the same as publishing your report open access \(see [Section 5](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/05OpenAccessToPublishedResearchResults.md)\).


## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questions, obstacles, and common misconceptions

Q: "Is it sufficient to make my data openly available?"

A: "No—openness is a necessary but not sufficient condition for maximum reuse. Data have to be FAIR in addition to open."

Q: "What do the FAIR principles mean/imply for different stakeholders/audiences?"

A: "This is a great topic for discussion!"

Obstacle: Researchers may be reluctant to share their data because they are afraid that others will reuse them before they have extracted the maximum usage from them, or that others might not fully understand the data and therefore mis-use them.

\(suggested\) A: You may publish your data to make them findable with metadata, but set an embargo period on the data to make sure that you can publish your own article\(s\) first.

Q: "Is making my data FAIR a lot of extra work?"

A: "Not necessarily! Making data FAIR is not only the responsibility of the individual researchers but of the whole group. The best way to ensure that your data is FAIR is to create a Data Management Plan and plan everything beforehand. During the data collection and data processing follow the discipline standards and measures recommended by a repository.

Q: "I want to share my data. How should I license them?"

A: "That’s a good question. First of all think about who owns the data? A research funder or an institution that you work for. Then, think about authorship. Applying a suitable license to your data is crucial in order to make them reusable. For more information about licensing, please see [6. Open Licensing and File Formats](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/tree/master/02OpenScienceBasics/06OpenLicensingAndFileFormats).

Q: "I cannot make my data directly available—they are too large to share conveniently / have restrictions related to privacy issues. What should I do?"

A: "You should talk to experts in domain specific repositories on how to provide sufficient instructions to make your data findable and accessible."


## <img src="/Images/Icons/output.png" width="150" height="150" />
### Learning outcomes

1. Understand the characteristics of open data, and in particular the FAIR principles.

2. Be familiar with some of the arguments for and against open data.

3. Be able to differentiate and address sensitive data and opFAIR data; these two categories are not necessarily incompatible.

4. Be able to transform a dataset into one that is sufficient for open sharing \(non-proprietary format\), meets the standards of the FAIR principles, and is designed for maximized accessibility, transparency and re-use by providing sufficient metadata.

5. Know the difference between raw and processed \(or cleaned\) data, and the importance of version labels.

6. Know commonly used file formats and community standards for maximum re-usability.

7. Be able to write a data management plan.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Further reading
* Averkamp et al. (2018). Data packaging guide. [github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md).

* Barend et al. (2017). Cloudy, increasingly FAIR; revisiting the FAIR Data guiding principles for the European Open Science Cloud. [doi.org/10.3233/ISU-170824](https://doi.org/10.3233/ISU-170824)

* Brase et al. (2009). Approach for a joint global registration agency for research data. [doi.org/10.3233/ISU-2009-0595](https://doi.org/10.3233/ISU-2009-0595)

* Candela et al. (2015). Data journals: A survey. [doi.org/10.1002/asi.23358](https://doi.org/10.1002/asi.23358)

* CESSDA Training Working Group (2017-2018a). CESSDA Data Management Expert Guide. Bergen, Norway: CESSDA ERIC. [cessda.eu/DMGuide](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management)

* CESSDA Training Working Group (2017-2018b). CESSDA Data Management Expert Guide: Citing your data. Bergen, Norway: CESSDA ERIC.[cessda.eu/DMGuide/citingdata](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Publishing-with-CESSDA-archives/Citing-your-data)

* FAIRsharing.org (2016). FAIR. The FAIR Principles. [doi.org/10.25504/FAIRsharing.WWI10U](https://doi.org/10.25504/FAIRsharing.WWI10U)

* Force 11 (n.y.). Guiding principles for Findable, Accessible, Interoperable, and Re-usable data publishing Version B1.0. [force11.org/fairprinciples](https://www.force11.org/fairprinciples)

* Gorgolewski et al. (2013). Making data sharing count: a publication-based solution. [doi.org/10.3389/fnins.2013.00009](https://doi.org/10.3389/fnins.2013.00009)

* Kratz and Strasser (2015). Making Data Count. [doi.org/10.1038/sdata.2015.39](https://www.nature.com/articles/sdata201539) 

* Piwowar and Vision (2013). Data reuse and the open data citation advantage. [doi.org/10.7717/peerj.175](https://doi.org/10.7717/peerj.175)

* Wilkinson et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship. [doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)

* Wilkinson et al. (2918). A design framework and exemplar metrics for FAIRness. [doi.org/10.1038/sdata.2018.118](https://doi.org/10.1038/sdata.2018.118)


#### Initiatives and projects

* DANS GDPR DataTags. [zingtree.com](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)

* FAIR Metrics. [fairmetrics.org](http://fairmetrics.org/)

* GO FAIR Initiative. [go-fair.org](https://www.go-fair.org/)

*  The FAIR Data Principles explained. [go-fair.org](https://www.go-fair.org/fair-principles/)

*  5★ OPEN DATA. [5stardata.info](http://5stardata.info/en/)


