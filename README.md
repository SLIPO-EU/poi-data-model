<html>
<HEAD>
</head>
<body>


<div id="readme" class="clearfix announce instapaper_body md">
<article class="markdown-body entry-content" itemprop="mainContentOfPage">

<h2><a name="slipo-poi-model" class="anchor" href="#slipo-poi-model"><span class="octicon octicon-link"></span></a>The SLIPO POI data model</h2>

<p>Welcome to the SLIPO repository for the data model used for representing Points of Interest (POI). This data model, its coresponding OWL ontology and extensions have been developed by the <a href="http://www.imis.athena-innovation.gr/">Information Management Systems Institute</a> at <a href="http://www.athena-innovation.gr/en.html">Athena Research Center</a> under the EU/H2020 Innovation Action <a href="http://slipo.eu">SLIPO: Scalable Linking and Integration of big POI data</a>.</p>


<p>Transforming original POI data into this <a href="https://www.w3.org/RDF/">RDF</a> data model, has allowed us to transfer the tasks involved in POI data integration (i.e., interlinking, fusion, enrichment, etc.) into the Linked Data domain, and thus address the involved challenges using Linked Data technologies.</p>

<p>To derive this POI data model and its corresponding <a href="https://www.w3.org/OWL/">OWL ontology</a>, our work has been based on feedback collected from the project partners and relevant stakeholders, as well as on examining various POI representations employed by several existing sources and commercial data vendors.

<p>In this repository, we provide the OWL ontology that is designed for representing POIs internally in the SLIPO toolkit together with its extensions and intuitive visualizations. Utilized throughout the course of the SLIPO project for mapping a wide range of POI datasets from different providers and serving diverse use cases, this POI ontology has proven quite broad and robust to cover all necessary configurations, effectively requiring only minor amendments and a handful of additional properties. </p>

<p>Apart from an OWL ontology, we have also designed an <a href="https://www.w3.org/standards/xml/schema.html">XML schema</a> that resembles the ontology. This is complementary to our data model and not used internally in the SLIPO ecosystem; it is only provided to facilitate POI data exchange between the SLIPO toolkit and other applications and POI sources without exposing them to the details of the RDF data model.</p>

<p>Given that this POI ontology was designed to be <i>extensible</i> as well, it has been also possible to enhance it with extra concepts and properties for two important cases:</p>

<ul>
<li>Keeping track of the <i>provenance of POIs</i> and their properties as they evolve through a data integration process using the <a href="https://www.w3.org/TR/prov-o/">PROV Ontology</a> and related vocabularies. Since POI entities are by nature volatile with several of their properties changing over time especially after fusion with other POI entities, the SLIPO ontology has been extended with new metadata for recording all such changes.</li>

<li>Enhancing the model for POIs representing <i>charging stations for Electric Vehicles (EV)</i> from various sources as a subclass of POI class in the core POI ontology. Indeed, this kind of data includes generic properties as typical POIs (name, category, contact details, etc.), but also provides a wide range of characteristics specific to EV charging stations only (number of charge points available, max voltage, max power in kW, charging level, etc.).</li>
</ul>


<h2>
<a name="license" class="anchor" href="#license"><span class="octicon octicon-link"></span></a>License</h2>

<p>The contents of this project are licensed under the <a href="https://github.com/SLIPO-EU/poi-data-model/blob/master/LICENSE">GPL v3 License</a>.</p></article>

</body>
</html>
