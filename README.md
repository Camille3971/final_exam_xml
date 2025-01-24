# Jean de La Fontaine Fables XML Encoding Project

## Project Overview
The goal of this project is to explore and represent the diversity in the fables of Jean de La Fontaine by focusing on the poetic structure. Jean de La Fontaine (1621-1695) was a French poet and fabulist, well known for his large collection of fables written in verse and often using animals to represent human traits.

In general, fables are written to convey moral lessons to the reader and the work of Jean de La Fontaine exemplifies this tradition. He even dedicates his collection to the Dauphin, the heir of the French throne, who was only seven at the time, to educate him about the world. Therefore, encoding this project in XML enables us to understand how La Fontaine used and adapted the structure of his fables to convey various morals.

In this project, XML is primarily used to encode the formal elements of the fables, such as rhyme schemes, meter and caesuras. This approach makes it easier to compare the different structures. Moreover, encoding the corpus in XML enables machine queries like searching for patterns and calculating percentages on the frequency of XML elements, which adds a level of precision that would be difficult to achieve through human observation.

In addition to serving as a set of rules for standardizing the encoding of the various texts within this project’s corpus, this ODD file can be applied to other French poetic works (with some specific adjustments made for the particularities of each work).

This project also contains a custom RNG schema to validate any xml document in the corpus and a HTML file, both generated from the ODD.

## Goals

1. Represent the diversity of poetic structures in La Fontaine's fables.
2. Enable precise structural analysis using XML encoding.
3. Standardize the encoding process for reuse in other poetic works.

## Key Features

1. XML Encoding: Encodes structural elements for computational analysis.
2. ODD File: Defines rules for consistent encoding and can be adapted to other works.
3. Custom RNG Schema: Validates XML documents in the corpus.
4. HTML Output: Provides a human-readable version of the encoding guidelines.
