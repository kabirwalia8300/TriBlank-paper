# TriBlank: Multiple Entity Blanking for Relation Learning

Final project for CS 6740 - Advanced Language Technologies (Cornell University) in collaboration with [William Ma](https://github.com/whoiswillma)

## Abstract

Efforts in sentence and document level relation extraction (RE) have often depended on predefined schema or knowledge graphs (KG) to develop mappings from text to relations, or to develop extendable textual representations. However, due to variations in KGs, it becomes difficult to develop a general relation extractor that can perform well on arbitrary relations. Soares et al., 2019 [9] leverage recent work in contextual word representations to construct task-agnostic relation representations. In this work, we build on their "Matching the Blanks" (MTB) training methodology by replacing entities in sets of three in a given example and task our model to identify rela- tions between pairs of blanked entities. We evaluate our model, TRIBLANK, on the DocRED [11] dataset. Our results showcase the difficulty of identifying semantic relations in the absence of contextual entities.
