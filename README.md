# Asset Administration Shell (AAS)
The Asset Administration Shell (AAS) is the digital representation of an asset. The AAS consists of a number of submodels in which all the information and functionalities of a given asset – including its features, characteristics, properties, statuses, parameters, measurement data and capabilities – can be described. It allows for the use of different communication channels and applications and serves as the link between objects and the connected, digital and distributed world.  

The structure of the AAS is defined via a technology independent metamodel and several technology specific serialization mappings such as XML, JSON or OPC UA. Its contents are defined via domain-specific submodel templates. [Details of the Asset Administration Shell](references/Details_of_the_Asset_Administration_Shell_Part1_V3.pdf).

## [AASX Package Explorer](https://github.com/admin-shell-io/aasx-package-explorer)
AASX Package Explorer [Tutorial](https://www.youtube.com/@csuyux/videos).  
[Submodel templates of the Asset Administration Shell](references/Submodel_templates-Asset_Administration_Shell-Technical_Data.pdf).

### [ECLASS](https://eclass.eu/support/technical-specification/data-model/conceptual-data-model)

The AASX file if it is renamed from .aasx to .zip you can see the files that were attached together with the file, that's why the name package. The aasx framework uses eclass. ECLASS is a cross-industry master-data business standard for products and services information to be exchanged in a computer-sensible form across all borders – across sectors, countries, languages and organizations. The ECLASS data dictionary is based on ISO 13584-42 and IEC 61360-2. It is used for the exchange of product data for procurement, eCommerce, engineering tools, etc.
Eclass offers you the opportunity to view and research current eclass releases for free.The research function can be used intuitively and allows us to know the norm quickly and without bureaucracy. See  27 Electric engineering, automation, process control engineering. [Search the content of ECLASS](https://eclass.eu/eclass-standard/content-suche).
[Download eclass 13 Asset](https://eclass.eu/shop/produkt/eclass-13-0-asset).

### AASX Examples

- [Servo DC Motor](examples/Example_AAS_ServoDCMotor_21.png)
- [Pressure Sensor](examples/Wika_PSD4.png)

## AASX Server
The AASX Server is based on code of AASX Package Explorer.  
[AASX Server](https://github.com/admin-shell-io/aasx-server) serves Industrie 4.0 AASX packages accessible by REST, OPC UA and MQTT protocols.  
Industrial Digital Twin Association (IDTA) provides an example AASX Server at https://admin-shell-io.com/5001. 