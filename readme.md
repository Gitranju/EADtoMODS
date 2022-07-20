In my work I have come across scenarios where there has been need of writing simple transformation from one XML code to another. So, I thought of putting together some simple transformation codes. This XSLT is for transformation of EAD to DC metadata, which would be useful in scenarios where organisations need to do metadata crosswalk (exported from Archival system and to be ingested into Digital Library).

In this case, I have written XSLT to Transform an EAD file that has come from CALM Archival management system to Simple DC metadata file. This is done with thinking that the output of DC will be usable in any Digital Library.

While EAD is a single file, a Digital Library sees things as Collection and Items. Since EAD consists of both the Collection level Information and Item level Information in one file, for the extraction of all metadata, I think there are two XSLTs needed, one to get Collection Level information from EAD and the other to get Item level Information from EAD.
