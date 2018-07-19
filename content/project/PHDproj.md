+++
title = "An Ontologies and Agents Based Approach for Undersea Feature Characterisation and Generalisation"
date = 2018-07-19T14:27:11+08:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Nautical chart", "Submarine relief", "Ontology", "Cartography", "Multi-agent system", "Generalisation"]

# Project summary to display on homepage.
summary = "Construction of a nautical chart follows very specific rules. An undersea feature is a subjective individuation of a part of the seafloor. Landform recognition is a difficult task because its definition usually relies on a qualitative and fuzzy description. This project aims to define ontologies of the submarine relief and nautical chart. Then, the ontologies are applied to generalisation of nautical chart. In the first part of the research, an ontology is defined to organise geographical and cartographic knowledge for undersea feature representation and nautical chart generalisation. In the second part, a generalisation process based on the ontology is designed relying on a multi-agent system."

# Optional image to display on homepage.
image_preview = "results_phd.jpg"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
A nautical chart is a kind of map used to describe the seafloor morphology and the shoreline of adjacent lands. One of its main purposes is to guaranty safety of maritime navigation. As a consequence, construction of a nautical chart follows very specific rules. The cartographer has to select and highlight undersea features according to their relevance to navigation. In an automated process, the system must be able to identify and classify these features from the terrain model.

An undersea feature is a subjective individuation of a part of the seafloor. Landform recognition is a difficult task because its definition usually relies on a qualitative and fuzzy description. Achieving automatic recognition of landforms requires a formal definition of the landforms properties and their modelling. In the maritime domain, the International Hydrographic Organisation published a standard terminology of undersea feature names which formalises a set of definitions mainly for naming features and communication purpose. This terminology is here used as a starting point for the automatic classification of the features from a terrain model.

In order to integrate knowledge about the submarine relief and its representation on the chart, this research aims to define ontologies of the submarine relief and nautical chart. Then, the ontologies are applied to generalisation of nautical chart. It includes two main parts. In the first part of the research, an ontology is defined to organise geographical and cartographic knowledge for undersea feature representation and nautical chart generalisation. First, a domain ontology of the submarine relief introduces the di↵erent concepts of undersea features with their geometric and topological properties. This ontology is required for the classification of features. Second, a representation ontology is presented, which describes how bathymetric entities are portrayed on the map. Third, a generalisation process ontology defines constraints and operations in nautical chart generalisation. In the second part, a generalisation process based on the ontology is designed relying on a multi-agent system. Four kinds of agents (isobath, sounding, feature and group of features) are defined to manage cartographic objects on the chart. A database model was generated from the ontology. The bathymetric data and the ontology are stored in a triplestore database, and are connected to an interface in Java and C++ to automatically classify the undersea features extracted from the bathymetry, and evaluate the cartographic constraints. At first, geometrical properties describing the feature shape are computed from soundings and isobaths and are used for feature classification. Then, conflicts are evaluated in a MAS and generalisation plans are provided.