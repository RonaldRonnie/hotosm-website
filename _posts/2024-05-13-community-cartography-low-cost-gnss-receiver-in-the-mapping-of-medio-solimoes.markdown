---
title: 'Community Cartography: Low-Cost GNSS Receiver in the Mapping of Medio Solimões'
date: 2024-05-13 15:00:00 Z
Summary Text: Explore how low-cost GNSS technology is revolutionizing mapping in the
  Medio Solimões, with support from HOT and the LAC Hub. This innovative project,
  conducted by the Federal University of São João del-Rei, promotes participatory
  cartography, improving resource management and resilience of riverside communities
  in the Brazilian Amazon.
Feature Image: "/uploads/Mapeamento%20do%20Me%CC%81dio%20Solimo%CC%83es.jpg"
Person:
- Silvia Elena Ventorini
- Ana Luísa Teixeira
- Rafael Quetz Oliveira
Country:
- Brazil
Project:
- Collaborative and Inclusive Mapping of the Middle Solimões, Amazon
---

> [Versão em Português](https://www.hotosm.org/updates/cartografia-comunitaria-receptor-de-baixo-custo-no-mapeamento-do-medio-solimoes/) / [Versión en Español](https://www.hotosm.org/updates/cartografia-comunitaria-receptor-de-bajo-costo-en-el-mapeo-del-medio-solimoes/)

In a world where geographical precision is becoming increasingly vital, the Collaborative Mapping Initiative of Medio Solimões stands out for its innovative and inclusive approach. Developed in collaboration between the [Federal University of São João del-Rei](https://www.ufsj.edu.br/), the [Higher Studies Center of Tefé at the State University of Amazonas](https://avauea.uea.edu.br/course/index.php?categoryid=210), and the Humanitarian OpenStreetMap (HOT)'s [Open Mapping Hub in Latin America and the Caribbean (LAC Hub)](https://www.hotosm.org/hubs/open-mapping-hub-latin-america-and-the-caribbean/), this project utilizes low-cost GNSS technology to overcome the cartographic challenges of the region.

In this final blog post, researchers Silvia Elena Ventorini, Ana Luísa Teixeira, and Rafael Quetz Oliveira share valuable insights on the methodologies used and the results obtained, shedding light on the path for future collaborative mapping initiatives in the Amazon.

![Mapeamento do Médio Solimões 1.jpg](/uploads/Mapeamento%20do%20Me%CC%81dio%20Solimo%CC%83es%201.jpg)

GNSS (Global Navigation Satellite System) is an important equipment for collecting precise coordinates of a specific location or object. Currently, it is considered one of the most advanced technologies, and according to the European Union Agency for the Space Programme, it is expected to experience exponential growth this decade. Among the various applications of GNSS receivers is their fundamental use in processing aerial photographs taken from the popularly known Drones.

Despite all the advancements in the area of GNSS positioning, commercial GNSS receivers still have a very high cost, not to mention the need for theoretical and technical knowledge for their use, which limits their use by researchers and public agency professionals. To minimize this inaccessibility, researchers worldwide have dedicated themselves to developing and studying low-cost GNSS receivers.

In Brazil, the lack of access to GNSS by public agency professionals and researchers contributes to the country's unequal and outdated cartography. In complex regions like the Brazilian Amazon, which has been increasingly affected by the effects of climate change, contributing to the transformation of this scenario becomes essential. It was with this goal that a group of researchers assembled and analyzed the viability of a low-cost Receiver provided through the project [“Collaborative and Integrative Mapping of Medio Solimões”](https://www.hotosm.org/projects/collaborative-and-inclusive-mapping-of-the-middle-solimoes/) supported by the Latin American Humanitarian OpenStreetMap Team (HOT) and developed in collaboration with the [Higher Studies Center of Tefé - State University of Amazonas (CEST-UEA)](https://avauea.uea.edu.br/course/index.php?categoryid=210).

![Mapeamento do Médio Solimões 2.jpg](/uploads/Mapeamento%20do%20Me%CC%81dio%20Solimo%CC%83es%202.jpg)

The team formed by professors Silvia Elena Ventorini (coordinator) and Leonardo Cristian Rocha, master's student in Geography Ana Luísa Teixeira, and undergraduate in Geography Rafael Quetz, all from the Federal University of São João del-Rei (UFSJ), received initial guidance on the characteristics of the equipment from HOT experts and conducted countless tests in the cities of São João del-Rei, Minas Gerais- Brazil, Tefé, and Alvarães, Amazonas-Brazil to be able to adapt the equipment to the challenging local reality, being able to develop new techniques for the use of GNSS.

The equipment used is composed of a base and a rover, which communicate with each other. To start data collection, it is necessary for the base to remain static for 4 hours, stabilized on a tripod and as high as possible by a pole. After that time, the collected observations are transformed into rinex data (a universal observation data format) to be submitted on platforms of official bodies - in the case of Brazil, the Brazilian Institute of Geography and Statistics (IBGE).

After this correction over the internet, the corrected point (x, y, and z coordinates) is inserted and fixed at the base to start collecting other points with the rover. The major problem with this method refers to the absence of the internet at the location for sending the coordinates to the responsible agency. However, this problem can be corrected when the uncorrected data is later worked on in a Geographic Information System (GIS) and applying scientific techniques and procedures for its correction.

Despite seeming practical and simple, the procedures are not, and the team of researchers adopted test and re-test procedures followed by analysis. Such facts were necessary due to the restricted internet access in the locations in the Amazon where the fieldwork was conducted, mainly in the riverside community of São Luís do Macari - rural area of Tefé, as well as other logistical aspects such as the heat and extreme drought of November 2023. The El Niño phenomenon caused a severe drought, affecting river transport between Tefé and nearby cities. Tefé is central in the Medio Solimões, housing essential services such as banks, supermarkets, etc. Under these circumstances, mapping the populations becomes even more important. Thus, data were collected with the base in two different locations, due to the community's migration to another place due to the constant erosions caused by the phenomenon called "fallen lands" which cause economic and social harm to the population. The results obtained through the trials conducted by the team showed the efficacy of the equipment, whose results are similar to commercial receivers (both the data collected with and without the internet), but at a much more accessible cost. The data collected in the community now have millimeter precision, indicating the viability of its use for drone mapping and to minimize financial costs that often make some types of mapping work unfeasible.

![Mapeamento do Médio Solimões 3.jpg](/uploads/Mapeamento%20do%20Me%CC%81dio%20Solimo%CC%83es%203.jpg)

In addition to the methodology used to solve the problem of restricted internet access, the UFSJ team sought ways to facilitate its assembly and use in the field. To this end, they adopted tripods with bubble levels and 4.6-meter high poles, as well as reinforced and longer cables for connecting the receivers and mobile phones, 3D-printed acrylic boxes for the protection of the arduinos, a suitcase for carrying all the elements of the receiver, and supports for mobile phones. The applications used during point collection were GNSS Master and SW Maps and for data processing after the field were EMLID Studio, PPP-IBGE, and QGIS.

It should be noted that this equipment, as well as any GNSS, requires specific knowledge of the basic operation of the geodesy networks in Brazil and theoretical concepts about planning, collection, and post-processing of data. However, with continuous training, especially for public agency professionals such as Civil Defense and city councils, it is possible to use it for the construction and updating of cartographic databases to solve local problems and mitigate issues.

Despite the satisfactory results found so far, the team continues testing the equipment in São João del-Rei. Regarding the practical part, the team has been conducting tests in study areas of the members of the School and Digital Cartography Laboratory of the UFSJ (LabCar). Currently, procedures are also being carried out for testing the bluetooth connection between the mobile phone and the receivers and the perfection of the design of the acrylic boxes with the 3D printer. Such tests are being developed by Prof. Dr. Eduardo Bento, coordinator of the Assistive Robotics Center of the UFSJ.

The use of GNSS offers vast potential for improving collaborative mapping of erosive processes in riverside communities, to understand and mitigate the challenges faced by these communities. By employing this technology, researchers and professionals can map in greater detail the areas vulnerable to erosive processes, allowing for more targeted and efficient intervention. Moreover, by involving the communities themselves in the data collection process, collaborative mapping promotes local empowerment, citizen participation in the management and protection of their natural resources, and the development of disaster prevention plans with a human-centered approach. By making this type of technology accessible to local researchers and professionals, it is possible to strengthen the capacity of local communities. The results achieved so far demonstrate the efficacy of the equipment, despite the existing challenges still to be overcome and improvements to be implemented.

By concluding this pioneering project, the transformative power of community commitment and interinstitutional collaboration in addressing complex challenges becomes evident. The use of the OSM platform and low-cost GNSS technologies not only fills vital cartographic gaps but also strengthens local communities, promoting more effective management of natural resources and fostering sustainable development.

The experience of Medio Solimões serves as an inspiring model for other regions, demonstrating that technology and community collaboration can go hand in hand in preserving cultural and environmental diversity and building a more resilient future.