# CAT_Annotation_Experiment_3

This repository contains the data, code for analyses, and other supplemental materials for the paper "Identifying visual depictions of animate entities in narrative comics: An annotation study".

## File List

* [Participant_Information_Sheet_animacy.pdf](Participant_Information_Sheet_animacy.pdf) - This pdf is an information sheet about the study described in the associated paper. This information sheet shows that the study was approved by Queen Mary University of London. It was given to every annotator before their participation in the study.

* [instructions_and_examples_animacy_outline.pdf](instructions_and_examples_animacy_outline.pdf) - This pdf provides basic instructions on how to use the Comics Annotation Tool (CAT) and the full annotation scheme, including examples of animate versus inanimate entities and pictorial examples of correctly annotated panels with drawn outlines. This pdf is downloadable from the Comics Annotation Tool (CAT) so that an annotator can refer to it at any time.

* [ComicPages](ComicPages) - This folder contains pdfs of all the comic pages that were annotated in the annotation experiments described in the paper. 

  * [Story1](ComicPages/Story1) - This folder contains all five pages of "The Cadmus Seed!" as pdfs. [Story1_Info.md](ComicPages/Story1/Story1_Info.md) provides the authorship and publication information. 
  * [Story2](ComicPages/Story2) - This folder contains all five pages of "The Fourth Dimension is a Many Splattered Thing!" as pdfs. [Story2_Info.md](ComicPages/Story2/Story2_Info.md) provides the authorship and publication information.
  * [Story3](ComicPages/Story3) - This folder contains all five pages of "My Robot Plants" as pdfs. [Story3_Info.md](ComicPages/Story3/Story3_Info.md) provides the authorship and publication information.
  * [Story4](ComicPages/Story4) - This folder contains all five pages of "The Man Who Never Lived" as pdfs. [Story4_Info.md](ComicPages/Story4/Story4_Info.md) provides the authorship and publication information.
 
* [Annotations_Prolific](Annotations_Prolific) - This folder contains all the collected annotations for each study.
  
  * [Animacy_Story1](Annotations_Prolific/Animacy_Story1) - Holds all the annotations collected when testing agreement for Story 1 using IOU overlap scores. The [Processed_Data](Annotations_Prolific/Animacy_Story1/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Animacy_Type_and_Reference_Story1](Annotations_Prolific/Animacy_Type_and_Reference_Story1) - Holds all the annotations for testing animacy category agreement for Story 1 using Krippendorff's alpha. The [Processed_Data](Annotations_Prolific/Animacy_Type_and_Reference_Story1/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Animacy_Story2](Annotations_Prolific/Animacy_Story2) - Holds all the annotations collected when testing agreement for Story 2 using IOU overlap scores. The [Processed_Data](Annotations_Prolific/Animacy_Story2/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Animacy_Type_and_Reference_Story2](Annotations_Prolific/Animacy_Type_and_Reference_Story2) - Holds all the annotations for testing animacy category agreement for Story 2 using Krippendorff's alpha. The [Processed_Data](Annotations_Prolific/Animacy_Type_and_Reference_Story2/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Animacy_Story3](Annotations_Prolific/Animacy_Story3) - Holds all the annotations collected when testing agreement for Story 3 using IOU overlap scores. The [Processed_Data](Annotations_Prolific/Animacy_Story3/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Animacy_Type_and_Reference_Story3](Annotations_Prolific/Animacy_Type_and_Reference_Story3) - Holds all the annotations for testing animacy category agreement for Story 3 using Krippendorff's alpha. The [Processed_Data](Annotations_Prolific/Animacy_Type_and_Reference_Story3/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Animacy_Story4](Annotations_Prolific/Animacy_Story4) - Holds all the annotations collected when testing agreement for Story 4 using IOU overlap scores. The [Processed_Data](Annotations_Prolific/Animacy_Story4/Processed_Data) subfolder contains each individual participant's annotations in JSON files.
  * [Animacy_Type_and_Reference_Story4](Annotations_Prolific/Animacy_Type_and_Reference_Story4) - Holds all the annotations for testing animacy category agreement for Story 4 using Krippendorff's alpha. The [Processed_Data](Annotations_Prolific/Animacy_Type_and_Reference_Story4/Processed_Data) subfolder contains each individual participant's annotations in JSON files.

 
* [Inter-Annotator_agreement_analysis_code](Inter-Annotator_agreement_analysis_code) - This folder contains the code to calculate annotator agreement for each study. The analyses are done using python within jupyter notebook files. Annotation data can be read in from the JSON files in the [Annotations_Prolific](Annotations_Prolific) folder. 

  * [Animacy_Polygon_IAA_Story1.ipynb](Inter-Annotator_agreement_analysis_code/Animacy_Polygon_IAA_Story1.ipynb) - Contains agreement results for Experiment 1, where polygon IOU scores are calculated, for Story 1.
  * [Animacy_Polygon_IAA_Story2.ipynb](Inter-Annotator_agreement_analysis_code/Animacy_Polygon_IAA_Story2.ipynb) - Contains agreement results for Experiment 1, where polygon IOU  scores are calculated, for Story 2.
  * [Animacy_Polygon_IAA_Story3.ipynb](Inter-Annotator_agreement_analysis_code/Animacy_Polygon_IAA_Story3.ipynb) - Contains agreement results for Experiment 1, where polygon IOU scores are calculated, for Story 3.
  * [Animacy_Polygon_IAA_Story4.ipynb](Inter-Annotator_agreement_analysis_code/Animacy_Polygon_IAA_Story4.ipynb) - Contains agreement results for Experiment 1, where polygon IOU scores are calculated, for Story 4.
  * [Animacy_Polygon_IAA_Boxplot.ipynb](Inter-Annotator_agreement_analysis_code/Animacy_Polygon_IAA_Boxplot.ipynb) - Contains code to visualize the distributions of agreement scores between annotator pairs as a boxplot, for Experiment 1.
  * [Animacy_hierarchy_classification_IAA.ipynb](Inter-Annotator_agreement_analysis_code/Animacy_hierarchy_classification_IAA.ipynb) - Contains agreement results for Experiment 2, where the all-against-all Krippendorff's Alpha scores are calculated per story. 

  
* [Consent_Form.pdf](Consent_Form.pdf) - This pdf is the consent form given to each annotator to confirm that they choose to participant in the study and can withdraw consent at any time. These statements were given to each annotator to initial and sign out within the Comics Annotation Tool (CAT).

* [VLFI_Questionnaire.pdf](VLFI_Questionnaire.pdf) - This pdf provides the questions of the Visual Language Fluency Index (VLFI). These questions were given to each annotator to fill out within the Comics Annotation Tool (CAT).  
