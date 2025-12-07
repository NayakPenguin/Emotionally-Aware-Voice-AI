# Emotionally Aware Voice AI
"Voice to Text", but it also understands the your tone! Because there are multiple versions of the same sentence spoken in different emotions.

![Angry I can’t believe this is happening right now! (Sharp, loud, tense; emphasis on can’t believe)](https://github.com/user-attachments/assets/8f6f4ad1-90d5-48e9-ac20-35c57c6872f8)

## Code overview :
- Models need fixed-size input, and 3 seconds gives enough emotion while keeping computation small.
- Mel spectrograms turn audio into a human-hearing-scaled time–frequency image that models can learn from.
- Log-mel compresses amplitudes, highlights quiet details, matches loudness perception, and stabilizes training.
- GPUs train neural networks fast through parallelism; CPUs are slower but fine for running trained models.
- CNNs learn frequency patterns while GRUs learn temporal patterns, and together they capture full emotional cues.

## Result :
![Angry I can’t believe this is happening right now! (Sharp, loud, tense; emphasis on can’t believe) (1)](https://github.com/user-attachments/assets/c05579d5-8e60-4344-b6d4-dd09c684e408)
