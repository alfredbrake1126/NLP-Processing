# Tracking Progress in Natural Language Processing

## Table of contents

### English

- [Automatic speech recognition](english/automatic_speech_recognition.md)
- [CCG](english/ccg.md)
- [Common sense](english/common_sense.md)
- [Constituency parsing](english/constituency_parsing.md)
- [Coreference resolution](english/coreference_resolution.md)
- [Data-to-Text Generation](english/data_to_text_generation.md)
- [Dependency parsing](english/dependency_parsing.md)
- [Dialogue](english/dialogue.md)
- [Domain adaptation](english/domain_adaptation.md)
- [Entity linking](english/entity_linking.md)
- [Grammatical error correction](english/grammatical_error_correction.md)
- [Information extraction](english/information_extraction.md)
- [Intent Detection and Slot Filling](english/intent_detection_slot_filling.md)
- [Language modeling](english/language_modeling.md)
- [Lexical normalization](english/lexical_normalization.md)
- [Machine translation](english/machine_translation.md)
- [Missing elements](english/missing_elements.md)
- [Multi-task learning](english/multi-task_learning.md)
- [Multi-modal](english/multimodal.md)
- [Named entity recognition](english/named_entity_recognition.md)
- [Natural language inference](english/natural_language_inference.md)
- [Part-of-speech tagging](english/part-of-speech_tagging.md)
- [Paraphrase Generation](english/paraphrase-generation.md)
- [Question answering](english/question_answering.md)
- [Relation prediction](english/relation_prediction.md)
- [Relationship extraction](english/relationship_extraction.md)
- [Semantic textual similarity](english/semantic_textual_similarity.md)
- [Semantic parsing](english/semantic_parsing.md)
- [Semantic role labeling](english/semantic_role_labeling.md)
- [Sentiment analysis](english/sentiment_analysis.md)
- [Shallow syntax](english/shallow_syntax.md)
- [Simplification](english/simplification.md)
- [Stance detection](english/stance_detection.md)
- [Summarization](english/summarization.md)
- [Taxonomy learning](english/taxonomy_learning.md)
- [Temporal processing](english/temporal_processing.md)
- [Text classification](english/text_classification.md)
- [Word sense disambiguation](english/word_sense_disambiguation.md)

### Vietnamese

- [Dependency parsing](vietnamese/vietnamese.md#dependency-parsing)
- [Intent detection and Slot filling](vietnamese/vietnamese.md#intent-detection-and-slot-filling)
- [Machine translation](vietnamese/vietnamese.md#machine-translation)
- [Named entity recognition](vietnamese/vietnamese.md#named-entity-recognition)
- [Part-of-speech tagging](vietnamese/vietnamese.md#part-of-speech-tagging)
- [Semantic parsing](vietnamese/vietnamese.md#semantic-parsing)
- [Word segmentation](vietnamese/vietnamese.md#word-segmentation)

### Hindi

- [Chunking](hindi/hindi.md#chunking)
- [Part-of-speech tagging](hindi/hindi.md#part-of-speech-tagging)
- [Machine Translation](hindi/hindi.md#machine-translation)

### Chinese

- [Entity linking](chinese/chinese.md#entity-linking)
- [Chinese word segmentation](chinese/chinese_word_segmentation.md)
- [Question answering](chinese/question_answering.md)

For more tasks, datasets and results in Chinese, check out the [Chinese NLP](https://chinesenlp.xyz/#/) website.

### French

- [Question answering](french/question_answering.md)
- [Summarization](french/summarization.md)

### Russian

- [Question answering](russian/question_answering.md)
- [Sentiment Analysis](russian/sentiment-analysis.md)
- [Summarization](russian/summarization.md)

### Spanish

- [Named Entity Recognition](spanish/named_entity_recognition.md)
- [Entity linking](spanish/entity_linking.md#entity-linking)
- [Summarization](spanish/summarization.md)

### Portuguese

- [Question Answering](portuguese/question_answering.md)

### Korean

- [Question Answering](korean/question_answering.md)

### Nepali

- [Machine Translation](nepali/nepali.md#machine-translation)

### Bengali
- [Part-of-speech Tagging](bengali/part_of_speech_tagging.md)
- [Sentiment Analysis](bengali/sentiment_analysis.md)

### Persian
- [Named entity recognition](persian/named_entity_recognition.md)
- [Natural language inference](persian/natural_language_inference.md)
- [Summarization](persian/summarization.md)

### Turkish

- [Summarization](turkish/summarization.md)

### German

- [Question Answering](german/question_answering.md)
- [Summarization](german/summarization.md)

### Arabic
- [Language modeling](arabic/language_modeling.md)


This document aims to track the progress in Natural Language Processing (NLP) and give an overview
of the state-of-the-art (SOTA) across the most common NLP tasks and their corresponding datasets.

It aims to cover both traditional and core NLP tasks such as dependency parsing and part-of-speech tagging
as well as more recent ones such as reading comprehension and natural language inference. The main objective
is to provide the reader with a quick overview of benchmark datasets and the state-of-the-art for their
task of interest, which serves as a stepping stone for further research. To this end, if there is a 
place where results for a task are already published and regularly maintained, such as a public leaderboard,
the reader will be pointed there.

If you want to find this document again in the future, just go to [`nlpprogress.com`](https://nlpprogress.com/)
or [`nlpsota.com`](http://nlpsota.com/) in your browser.

### Contributing

#### Guidelines

**Results** &nbsp; Results reported in published papers are preferred; an exception may be made for influential preprints.

**Datasets** &nbsp; Datasets should have been used for evaluation in at least one published paper besides 
the one that introduced the dataset.

**Code** &nbsp; We recommend to add a link to an implementation 
if available. You can add a `Code` column (see below) to the table if it does not exist.
In the `Code` column, indicate an official implementation with [Official](http://link_to_implementation).
If an unofficial implementation is available, use [Link](http://link_to_implementation) (see below).
If no implementation is available, you can leave the cell empty.

### Wish list

These are tasks and datasets that are still missing:

- Bilingual dictionary induction
- Discourse parsing
- Keyphrase extraction
- Knowledge base population (KBP)
- More dialogue tasks
- Semi-supervised learning
- Frame-semantic parsing (FrameNet full-sentence analysis)

### Exporting into a structured format

You can extract all the data into a structured, machine-readable JSON format with parsed tasks, descriptions and SOTA tables. 

The instructions are in [structured/README.md](structured/README.md).

### Instructions for building the site locally

Instructions for building the website locally using Jekyll can be found [here](jekyll_instructions.md).


