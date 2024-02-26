# Emotion Discovery and Reasoning its Flip in Conversation (EDiReF)

## Overview

This project participated in the SemEval2024 competition, specifically focusing on the third sub-task related to Emotion Discovery and Reasoning its Flip (EFR) in English conversations. The competition aimed to explore the nature of meaning in natural languages, encompassing various semantic topics, including sentiment analysis, word sense identification, and more.

### Task Description

The specific sub-task involved identifying trigger utterances for an emotion-flip in a multi-party conversation dialogue. Given a dialogue, the objective was to pinpoint the utterance(s) that serve as triggers for a change in emotion.

## Project Structure

- `data/`: Contains datasets for emotion classification and trigger detection.
- `models/`: Stores the trained BERT models for emotion classification and trigger detection.
- `src/`: Source code for data preprocessing, model training, and evaluation.

## Competition Details

SemEval2024 competition: [SemEval2024-EDiReF](https://lcs2.in/SemEval2024-EDiReF/)

## Workflow

1. **Emotion Classification:**
   - Utilized a BERT-based algorithm to classify the associated emotion with each phrase in the conversation.
   - Implemented emotion classification using the `src/emotion_classification.py` script.

2. **Trigger Detection:**
   - Extended the BERT model to identify trigger utterances for emotion flips within the conversation.
   - Implemented trigger detection using the `src/trigger_detection.py` script.

3. **Model Evaluation:**
   - Evaluated the performance of both emotion classification and trigger detection models on test sets.
   - Leveraged the evaluation script in `src/evaluate.py`.

## Results and enhancement

For more in-depth details, refer to our paper related to this project.

## Contributors

Barnabé Sellier
Valentin Koenig
Maxence Murat
Benoit Noemie

## License

This project is licensed under the [MIT License](LICENSE).


