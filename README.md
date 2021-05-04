# Improved-Relation-Extraction

Group project for CS7650 Natural Language Processing <br /><br /><br />

## Version Info.<br />
## 0501 (current version)<br />

(1) Get rid of pronoun exclusion, since CoreNLP can recognize a significant proportion of pronouns
(2) Modified the output format, added a new Boolean field called "in_tacred" to denote whether the entity is at least martial match with the gold entities (subj or obj) in Tacred dataset.
(3) Fix the discrepancy of token spans. Added a argument to specify whitespace to be the only delimiter for CoreNLP to tokenize the sentences.<br />

## 0428<br />

(1) Add the partial_match statistics, which include all the inferences with the same NER types as target entities
(2) Include a function to exclude PERSON-type entities that belong to pronouns.<br />

## 0426<br />

(1) A basic pipline that can run the CoreNLP inference and evaluate the results.<br />