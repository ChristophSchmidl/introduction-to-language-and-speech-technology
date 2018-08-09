# Table of Contents

* Book: **Martin, J. H., & Jurafsky, D. (2009). Speech and language processing: An introduction to natural language processing, computational linguistics, and speech recognition. Pearson/Prentice Hall.**


## Foreword

## Preface

## About the Authors 

## 1 Introduction

* 1.1 Knowledge in Speech and Language Processing

* 1.2 Ambiguity

* 1.3 Models and Algorithms

* 1.4 Language, Thought, and Understanding

* 1.5 The State of the Art

* 1.6 Some Brief History

	* 1.6.1 Foundational Insights: 1940s and 1950s

	* 1.6.2 The Two Camps: 1957—1970

	* 1.6.3 Four Paradigms: 1970—1983

	* 1.6.4 Empiricism and Finite State Models Redux: 1983—1993

	* 1.6.5 The Field Comes Together: 1994—1999

	* 1.6.6 The Rise of Machine Learning: 2000—2008

	* 1.6.7 On Multiple Discoveries

	* 1.6.8 A Final Brief Note on Psychology

1.7 Summary

Bibliographical and Historical Notes

**Part I Words**

## 2 Regular Expressions and Automata

2.1 Regular Expressions

2.1.1 Basic Regular Expression Patterns

2.1.2 Disjunction, Grouping, and Precedence

2.1.3 A Simple Example

2.1.4 A More Complex Example

2.1.5 Advanced Operators

2.1.6 Regular Expression Substitution, Memory, and ELIZA

2.2 Finite-State Automata

2.2.1 Using an FSA to Recognize Sheeptalk

2.2.2 Formal Languages

2.2.3 Another Example

2.2.4 Non-Deterministic FSAs

2.2.5 Using an NFSA to Accept Strings

2.2.6 Recognition as Search

2.2.7 Relating Deterministic and Non-Deterministic Automata

2.3 Regular Languages and FSAs

2.4 Summary

Bibliographical and Historical Notes

Exercises

## 3 Words and Transducers

3.1 Survey of (Mostly) English Morphology

3.1.1 Inflectional Morphology

3.1.2 Derivational Morphology

3.1.3 Cliticization

3.1.4 Non-Concatenative Morphology

3.1.5 Agreement

3.2 Finite-State Morphological Parsing

3.3 Construction of a Finite-State Lexicon

3.4 Finite-State Transducers

3.4.1 Sequential Transducers and Determinism

3.5 FSTs for Morphological Parsing

3.6 Transducers and Orthographic Rules

3.7 The COmbination of an FST Lexicon and Rules

3.8 Lexicon-Free FSTs: The Porter Stemmer

3.9 Word and Sentence Tokenization

3.9.1 Segmentation in Chinese

3.10 Detection and Correction of Spelling Errors

3.11 Minimum Edit Distance

3.12 Human Morphological Processing

3.13 Summary

Bibliographical and Historical Notes

Exercises

## 4 N-grams

4.1 Word Counting in Corpora

4.2 Simple (Unsmoothed) N-grams

4.3 Training and Test Sets

4.3.1 N-gram Sensitivity to the Training Corpus

4.3.2 Unknown Words: Open Versus Closed Vocabulary Tasks

4.4 Evaluating N-grams: Perplexity

4.5 Smoothing

4.5.1 Laplace Smoothing

4.5.2 Good-Turing Discounting

4.5.3 Some Advanced Issues in Good-Turing Estimation

4.6 Interpolation

4.7 Backoff

4.7.1 Advanced: Details of Computing Katz Backoff a and P∗

4.8 Practical Issues: Toolkits and Data Formats

4.9 Advanced Issues in Language Modeling

4.9.1 Advanced Smoothing Methods: Kneser-Ney Smoothing

4.9.2 Class-Based N-grams

4.9.3 Language Model Adaptation and Web Use

4.9.4 Using Longer Distance Information: A Brief Summary

4.10 Advanced: Information Theory Background

4.10.1 Cross-Entropy for Comparing Models

4.11 Advanced: The Entropy of English and Entropy Rate Constancy

4.12 Summary

Bibliographical and Historical Notes

Exercises

## 5 Part-of-Speech Tagging

5.1 (Mostly) English Word Classes

5.2 Tagsets for English

5.3 Part-of-Speech Tagging

5.4 Rule-Based Part-of-Speech Tagging

5.5 HMM Part-of-Speech Tagging

5.5.1 Computing the Most-Likely Tag Sequence: An Example

5.5.2 Formalizing Hidden Markov Model Taggers

5.5.3 Using the Viterbi Algorithm for HMM Tagging

5.5.4 Extending the HMM Algorithm to Trigrams

5.6 Transformation-Based Tagging

5.6.1 How TBL Rules Are Applied

5.6.2 How TBL Rules Are Learned

5.7 Evaluation and Error Analysis

5.7.1 Error Analysis

5.8 Advanced Issues in Part-of-Speech Tagging

5.8.1 Practical Issues: Tag Indeterminacy and Tokenization

5.8.2 Unknown Words

5.8.3 Part-of-Speech Tagging for Other Languages

5.8.4 Tagger Combination

5.9 Advanced: The Noisy Channel Model for Spelling

5.9.1 Contextual Spelling Error Correction

5.10 Summary

Bibliographical and Historical Notes

Exercises

## 6 Hidden Markov and Maximum Entropy Models

6.1 Markov Chains

6.2 The Hidden Markov Model

6.3 Likelihood Computation: The Forward Algorithm

6.4 Decoding: The Viterbi Algorithm

6.5 HMM Training: The Forward-Backward Algorithm

6.6 Maximum Entropy Models: Background

6.6.1 Linear Regression

6.6.2 Logistic Regression

6.6.3 Logistic Regression: Classification

6.6.4 Advanced: Learning in Logistic Regression

6.7 Maximum Entropy Modeling

6.7.1 Why We Call it Maximum Entropy

6.8 Maximum Entropy Markov Models

6.8.1 Decoding and Learning in MEMMs

6.9 Summary

Bibliographical and Historical Notes

Exercises

**Part II Speech**

## 7 Phonetics

7.1 Speech Sounds and Phonetic Transcription

7.2 Articulatory Phonetics

7.2.1 The Vocal Organs

7.2.2 Consonants: Place of Articulation

7.2.3 Consonants: Manner of Articulation

7.2.4 Vowels

7.2.5 Syllables 

7.3 Phonological Categories and Pronunciation Variation

7.3.1 Phonetic Features

7.3.2 Predicting Phonetic Variation

7.3.3 Factors Influencing Phonetic Variation

7.4 Acoustic Phonetics and Signals

7.4.1 Waves

7.4.2 Speech Sound Waves

7.4.3 Frequency and Amplitude; Pitch and Loudness

7.4.4 Interpretation of Phones from a Waveform

7.4.5 Spectra and the Frequency Domain

7.4.6 The Source-Filter Model

7.5 Phonetic Resources

7.6 Advanced: Articulatory and Gestural Phonology

7.7 Summary

Bibliographical and Historical Notes

Exercises

## 8 Speech Synthesis

8.1 Text Normalization

8.1.1 Sentence Tokenization

8.1.2 Non-Standard Words

8.1.3 Homograph Disambiguation

8.2 Phonetic Analysis

8.2.1 Dictionary Lookup

8.2.2 Names

8.2.3 Grapheme-to-Phoneme Conversion

8.3 Prosodic Analysis

8.3.1 Prosodic Structure

8.3.2 Prosodic Prominence

8.3.3 Tune

8.3.4 More Sophisticated Models: ToBI

8.3.5 Computing Duration from Prosodic Labels

8.3.6 Computing F0 from Prosodic Labels

8.3.7 Final Result of Text Analysis: Internal Representation

8.4 Diphone Waveform synthesis

8.4.1 Steps for Building a Diphone Database

8.4.2 Diphone Concatenation and TD-PSOLA for Prosody

8.5 Unit Selection (Waveform) Synthesis

8.6 Evaluation

Bibliographical and Historical Notes

Exercises

## 9 Automatic Speech Recognition

9.1 Speech Recognition Architecture

9.2 Applying the Hidden Markov Model to Speech

9.3 Feature Extraction: MFCC vectors

9.3.1 Preemphasis

9.3.2 Windowing

9.3.3 Discrete Fourier Transform

9.3.4 Mel Filter Bank and Log

9.3.5 The Cepstrum: Inverse Discrete Fourier Transform

9.3.6 Deltas and Energy

9.3.7 Summary: MFCC

9.4 Acoustic Likelihood Computation 

9.4.1 Vector Quantization

9.4.2 Gaussian PDFs

9.4.3 Probabilities, Log Probabilities and Distance Functions

9.5 The Lexicon and Language Model

9.6 Search and Decoding

9.7 Embedded Training

9.8 Evaluation: Word Error Rate

9.9 Summary

Bibliographical and Historical Notes

Exercises

## 10 Speech Recognition: Advanced Topics

10.1 Multipass Decoding: N-best Lists and Lattices

10.2 A∗ (‘Stack’) Decoding

10.3 Context-Dependent Acoustic Models: Triphones

10.4 Discriminative Training

10.4.1 Maximum Mutual Information Estimation

10.4.2 Acoustic Models Based on Posterior Classifiers

10.5 Modeling Variation

10.5.1 Environmental Variation and Noise

10.5.2 Speaker Variation and Speaker Adaptation

10.5.3 Pronunciation Modeling: Variation Due to Genre

10.6 Metadata: Boundaries, Punctuation, and Disfluencies

10.7 Speech Recognition by Humans

10.8 Summary

Bibliographical and Historical Notes

Exercises

## 11 Computational Phonology

11.1 Finite-State Phonology

11.2 Advanced Finite-State Phonology

11.2.1 Harmony

11.2.2 Templatic Morphology

11.3 Computational Optimality Theory

11.3.1 Finite-State Transducer Models of Optimality Theory

11.3.2 Stochastic Models of Optimality Theory

11.4 Syllabification

11.5 Learning Phonology and Morphology

11.5.1 Learning Phonological Rules

11.5.2 Learning Morphology

11.5.3 Learning in Optimality Theory

11.6 Summary

Bibliographical and Historical Notes

Exercises

**Part III Syntax**

## 12 Formal Grammars of English

12.1 Constituency

12.2 Context-Free Grammars

12.2.1 Formal definition of Context-Free Grammar

12.3 Some Grammar Rules for English

12.3.1 Sentence-Level Constructions

12.3.2 Clauses and Sentences

12.3.3 The Noun Phrase

12.3.4 Agreement

12.3.5 The Verb Phrase and Subcategorization

12.3.6 Auxiliaries

12.3.7 Coordination

12.4 Treebanks

12.4.1 Example: The Penn Treebank Project

12.4.2 Treebanks as Grammars

12.4.3 Treebank Searching

12.4.4 Heads and Head Finding

12.5 Grammar Equivalence and Normal Form

12.6 Finite-State and Context-Free Grammars

12.7 Dependency Grammars

12.7.1 The Relationship Between Dependencies and Heads

12.7.2 Categorial Grammar

12.8 Spoken Language Syntax

12.8.1 Disfluencies and Repair

12.8.2 Treebanks for Spoken Language

12.9 Grammars and Human Processing

12.10 Summary

Bibliographical and Historical Notes

Exercises

## 13 Syntactic Parsing

13.1 Parsing as Search

13.1.1 Top-Down Parsing

13.1.2 Bottom-Up Parsing

13.1.3 Comparing Top-Down and Bottom-Up Parsing

13.2 Ambiguity

13.3 Search in the Face of Ambiguity

13.4 Dynamic Programming Parsing Methods

13.4.1 CKY Parsing

13.4.2 The Earley Algorithm

13.4.3 Chart Parsing

13.5 Partial Parsing

13.5.1 Finite-State Rule-Based Chunking

13.5.2 Machine Learning-Based Approaches to Chunking

13.5.3 Evaluating Chunking Systems

13.6 Summary

Bibliographical and Historical Notes

Exercises

## 14 Statistical Parsing

14.1 Probabilistic Context-Free Grammars

14.1.1 PCFGs for Disambiguation

14.1.2 PCFGs for Language Modeling

14.2 Probabilistic CKY Parsing of PCFGs

14.3 Learning PCFG Rule Probabilities

14.4 Problems with PCFGs

14.4.1 Independence Assumptions Miss Structural Dependencies Between Rules

14.4.2 Lack of Sensitivity to Lexical Dependencies

14.5 Improving PCFGs by Splitting Non-Terminals

14.6 Probabilistic Lexicalized CFGs

14.6.1 The Collins Parser

14.6.2 Advanced: Further Details of the Collins Parser

14.7 Evaluating Parsers

14.8 Advanced: Discriminative Reranking

14.9 Advanced: Parser-Based Language Modeling

14.10 Human Parsing

14.11 Summary

Bibliographical and Historical Notes

Exercises

## 15 Features and Unification

15.1 Feature Structures

15.2 Unification of Feature Structures

15.3 Feature Structures in the Grammar

15.3.1 Agreement

15.3.2 Head Features

15.3.3 Subcategorization

15.3.4 Long-Distance Dependencies

15.4 Implementation of Unification

15.4.1 Unification Data Structures

15.4.2 The Unification Algorithm

15.5 Parsing with Unification Constraints

15.5.1 Integration of Unification into an Earley Parser

15.5.2 Unification-Based Parsing

15.6 Types and Inheritance

15.6.1 Advanced: Extensions to Typing

15.6.2 Other Extensions to Unification

15.7 Summary

Bibliographical and Historical Notes

Exercises

## 16 Language and Complexity

16.1 The Chomsky Hierarchy

16.2 Ways to Tell if a Language Isn’t Regular

16.2.1 The Pumping Lemma

16.2.2 Proofs That Various Natural Languages Are Not Regular

16.3 Is Natural Language Context-Free?

16.4 Complexity and Human Processing

16.5 Summary

Bibliographical and Historical Notes

Exercises

**Part IV Semantics and Pragmatics**

## 17 The Representation of Meaning

17.1 Computational Desiderata for Representations

17.1.1 Verifiability

17.1.2 Unambiguous Representations

17.1.3 Canonical Form

17.1.4 Inference and Variables

17.1.5 Expressiveness

17.2 Model-Theoretic Semantics

17.3 First-Order Logic

17.3.1 Basic Elements of First-Order Logic

17.3.2 Variables and Quantifiers

17.3.3 Lambda Notation

17.3.4 The Semantics of First-Order Logic

17.3.5 Inference

17.4 Event and State Representations 

17.4.1 Representing Time

17.4.2 Aspect

17.5  Description Logics

17.6 Embodied and Situated Approaches to Meaning

17.7 Summary

Bibliographical and Historical Notes

Exercises

## 18 Computational Semantics

18.1 Syntax-Driven Semantic Analysis

18.2 Semantic Augmentations to Syntactic Rules

18.3 Quantifier Scope Ambiguity and Underspecification

18.3.1 Store and Retrieve Approaches

18.3.2 Constraint-Based Approaches

18.4 Unification-Based Approaches to Semantic Analysis

18.5 Integration of Semantics into the Earley Parser

18.6 Idioms and Compositionality

18.7 Summary

Bibliographical and Historical Notes

Exercises

## 19 Lexical Semantics

19.1 Word Senses

19.2 Relations Between Senses

19.2.1 Synonymy and Antonymy

19.2.2 Hyponymy

19.2.3 Semantic Fields

19.3 WordNet: A Database of Lexical Relations

19.4 Event Participants

19.4.1 Thematic Roles

19.4.2 Diathesis Alternations

19.4.3 Problems with Thematic Roles

19.4.4 The Proposition Bank

19.4.5 FrameNet

19.4.6 Selectional Restrictions

19.5 Primitive Decomposition

19.6 Advanced: Metaphor

19.7 Summary

Bibliographical and Historical Notes

Exercises

## 20 Computational Lexical Semantics

20.1 Word Sense Disambiguation: Overview

20.2 Supervised Word Sense Disambiguation

20.2.1 Feature Extraction for Supervised Learning

20.2.2 Naive Bayes and Decision List Classifiers

20.3 WSD Evaluation, Baselines, and Ceilings

20.4 WSD: Dictionary and Thesaurus Methods

20.4.1 The Lesk Algorithm

20.4.2 Selectional Restrictions and Selectional Preferences . . . . 684

20.5 Minimally Supervised WSD: Bootstrapping

20.6 Word Similarity: Thesaurus Methods

20.7 Word Similarity: Distributional Methods

20.7.1 Defining a Word’s Co-Occurrence Vectors

20.7.2 Measuring Association with Context

20.7.3 Defining Similarity Between Two Vectors

20.7.4 Evaluating Distributional Word Similarity

20.8 Hyponymy and Other Word Relations

20.9 Semantic Role Labeling

20.10 Advanced: Unsupervised Sense Disambiguation

20.11 Summary

Bibliographical and Historical Notes

Exercises

## 21 Computational Discourse

21.1 Discourse Segmentation

21.1.1 Unsupervised Discourse Segmentation

21.1.2 Supervised Discourse Segmentation

21.1.3 Discourse Segmentation Evaluation

21.2 Text Coherence

21.2.1 Rhetorical Structure Theory

21.2.2 Automatic Coherence Assignment

21.3 Reference Resolution

21.4 Reference Phenomena

21.4.1 Five Types of Referring Expressions

21.4.2 Information Status

21.5 Features for Pronominal Anaphora Resolution

21.6 Three Algorithms for Pronominal Anaphora Resolution

21.6.1 Pronominal Anaphora Baseline: The Hobbs Algorithm

21.6.2 A Centering Algorithm for Anaphora Resolution

21.6.3 A Log-Linear Model for Pronominal Anaphora Resoluton

21.6.4 Features for Pronominal Anaphora Resoluton

21.7 Coreference Resolution

21.8 Evaluation of Coreference Resolution

21.9 Advanced: Inference-Based Coherence Resolution

21.10 Psycholinguistic Studies of Reference

21.11 Summary

Bibliographical and Historical Notes

Exercises

**Part V Applications**

## 22 Information Extraction

22.1 Named Entity Recognition

22.1.1 Ambiguity in Named Entity Recognition

22.1.2 NER as Sequence Labeling

22.1.3 Evaluation of Named Entity Recognition

22.1.4 Practical NER Architectures

22.2 Relation Detection and Classification

22.2.1 Supervised Learning Approaches to Relation Analysis

22.2.2 Lightly Supervised Approaches to Relation Analysis

22.2.3 Evaluation of Relation Analysis Systems

22.3 Temporal and Event Processing

22.3.1 Temporal Expression Recognition

22.3.2 Temporal Normalization

22.3.3 Event Detection and Analysis

22.3.4 TimeBank

22.4 Template-Filling

22.4.1 Statistical Approaches to Template-Filling

22.4.2 Finite-State Template-Filling Systems

22.5 Advanced: Biomedical Information Extraction

22.5.1 Biological Named Entity Recognition

22.5.2 Gene Normalization

22.5.3 Biological Roles and Relations

22.6 Summary

Bibliographical and Historical Notes

Exercises

## 23 Question Answering and Summarization

23.1 Information Retrieval

23.1.1 The Vector Space Model

23.1.2 Term Weighting

23.1.3 Term Selection and Creation

23.1.4 Evaluation of Information-Retrieval Systems

23.1.5 Homonymy, Polysemy, and Synonymy

23.1.6 Ways to Improve User Queries

23.2 Factoid Question Answering

23.2.1 Question Processing

23.2.2 Passage Retrieval

23.2.3 Answer Processing

23.2.4 Evaluation of Factoid Answers

23.3 Summarization

23.4 Single Document Summarization 

23.4.1 Unsupervised Content Selection

23.4.2 Unsupervised Summarization Based on Rhetorical Parsing

23.4.3 Supervised Content Selection

23.4.4 Sentence Simplification

23.5 Multi-Document Summarization

23.5.1 Content Selection in Multi-Document Summarization

23.5.2 Information Ordering in Multi-Document Summarization

23.6 Focused Summarization and Question Answering

23.7 Summarization Evaluation

23.8 Summary

Bibliographical and Historical Notes

Exercises

## 24 Dialogue and Conversational Agents

24.1 Properties of Human Conversations

24.1.1 Turns and Turn-Taking

24.1.2 Language as Action: Speech Acts

24.1.3 Language as Joint Action: Grounding

24.1.4 Conversational Structure

24.1.5 Conversational Implicature

24.2 Basic Dialogue Systems

24.2.1 ASR component

24.2.2 NLU component

24.2.3 Generation and TTS components

24.2.4 Dialogue Manager

24.2.5 Dealing with Errors: Confirmation and Rejection

24.3 VoiceXML

24.4 Dialogue System Design and Evaluation

24.4.1 Designing Dialogue Systems

24.4.2 Evaluating Dialogue Systems

24.5 Information-State and Dialogue Acts

24.5.1 Using Dialogue Acts

24.5.2 Interpreting Dialogue Acts

24.5.3 Detecting Correction Acts

24.5.4 Generating Dialogue Acts: Confirmation and Rejection

24.6 Markov Decision Process Architecture

24.7 Advanced: Plan-Based Dialogue Agents

24.7.1 Plan-Inferential Interpretation and Production

24.7.2 The Intentional Structure of Dialogue

24.8 Summary

Bibliographical and Historical Notes

Exercises

## 25 Machine Translation

25.1 Why Machine Translation Is Hard

25.1.1 Typology

25.1.2 Other Structural Divergences

25.1.3 Lexical Divergences

25.2 Classical MT and the Vauquois Triangle

25.2.1 Direct Translation

25.2.2 Transfer

25.2.3 Combined Direct and Tranfer Approaches in Classic MT

25.2.4 The Interlingua Idea: Using Meaning

25.3 Statistical MT

25.4 P(F|E): the Phrase-Based Translation Model

25.5 Alignment in MT

25.5.1 IBM Model 1

25.5.2 HMM Alignment

25.6 Training Alignment Models

25.6.1 EM for Training Alignment Models

25.7 Symmetrizing Alignments for Phrase-Based MT

25.8 Decoding for Phrase-Based Statistical MT

25.9 MT Evaluation

25.9.1 Using Human Raters

25.9.2 Automatic Evaluation: BLEU

25.10 Advanced: Syntactic Models for MT

25.11 Advanced: IBM Model 3 and Fertitlity

25.11.1 Training for Model 3

25.12 Advanced: Log-linearModels for MT . . . . . . . . . . . . . . . . 903

25.13 Summary

Bibliographical and Historical Notes

Exercises

## Bibliography

## Author Index

## Subject Index