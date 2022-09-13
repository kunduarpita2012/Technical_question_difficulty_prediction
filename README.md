# Technical_question_difficulty_prediction
Dateset.csv
This dataset has 360 pairs of questions along with their gold relative difficulty annotation. We take majority voting of 5 annotations to get annotation for each pair.

Schema:
Question 1: Contains the first question
Reason 1: Contains a set of reasons given by the annotators, why they think Question 1 is more difficult(less difficult)
Question 2: Contains the second question
Reason 2: Contains a set of reasons given by the annotators, why they think Question 2 is more difficult(less difficult)
Relative difficulty: Contains relative difficulty of Question 1 and Question 2.

Options for Relation difficulty: 
(i) First question is more difficult 
(ii) They are equally diificult
(iii) Second question is more difficult

Options for Reason 1 and Reason 2:
(i) Is about a fundamental concept
(ii) Is about an obscure concept
(iii) Involves many prerequisite concepts
(iv) Does not involve a lot of prerequisite concepts
(v) Involves intricate mathematics
(vi) Involves very little or no mathematics
(vii) Appears early in the book or is otherwise highlighted
(viii)Appears towards the end of the book or is otherwise hidden
(ix) Other
Blooms_level_extended.json
This contains extended definition of bloom's taxonomy. In this json file, the keys are bloom's level i.e. Remember, Understand, Apply, Analyze, Evaluate and Create and values are list of verbs, a list of WH words and a list of templates. 
