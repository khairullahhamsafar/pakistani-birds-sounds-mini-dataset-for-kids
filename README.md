# Bird Sounds Classification Mini Dataset for Kids

A small, kid-friendly bird sounds dataset designed for teaching machine learning, artificial intelligence, and audio classification concepts to children and beginners.

This dataset helps students learn how AI can recognize patterns in audio recordings and classify bird species based on their vocalizations.

## 📁 Dataset Structure

```text
Bird_Sounds_Classification_Mini_Dataset_For_Kids/TRAIN/
├── Buff_Browed_Chachalaca/          # 10 training audio samples
├── Lesser_Nothura/                  # 10 training audio samples
├── Puna_Tinamou/                    # 10 training audio samples
├── Quebracho_Crested_Tinamou/       # 10 training audio samples
└── White_Crested_Guan/              # 10 training audio samples

Bird_Sounds_Classification_Mini_Dataset_For_Kids/TEST/
├── Puna Tinamou12.mp3
├── Puna Tinamou13.mp3
├── White-crested Guan12.mp3
└── White-crested Guan13.mp3
```

### Training Classes

- `Buff_Browed_Chachalaca`
- `Lesser_Nothura`
- `Puna_Tinamou`
- `Quebracho_Crested_Tinamou`
- `White_Crested_Guan`

### Test Set

The `Test_Set` directory contains:

- 2 unseen audio samples of **Puna_Tinamou**
- 2 unseen audio samples of **White_Crested_Guan**

These recordings can be used to evaluate a trained model's prediction performance on new, unseen bird sounds.

## 🎯 Purpose

This dataset is perfect for:

- Teaching machine learning to kids
- Introduction to audio classification
- Bird species recognition projects
- Learning about sound pattern recognition
- Artificial intelligence education
- STEM classroom activities
- Exploring wildlife and biodiversity using AI

## 📊 Details

| Attribute | Value |
|-----------|---------|
| Classes | 5 bird species |
| Training audio samples per class | 10 |
| Total training audio samples | 50 |
| Testing audio samples | 4 |
| Total audio samples | 54 |
| Dataset size | Mini/small |
| Source | Selected from a larger publicly available bird sounds dataset |

## 🧠 Learning Objective

Using this dataset, students can:

1. Train a simple audio classification model.
2. Learn how AI recognizes sound patterns.
3. Understand supervised machine learning.
4. Explore biodiversity using artificial intelligence.
5. Test model performance using unseen bird sounds.
6. Compare predictions with the correct species labels.

## 🚀 Quick Start

```python
from pathlib import Path

train_dir = Path("Bird_Sounds_Classification_Mini_Dataset_For_Kids")
test_dir = Path("Test_Set")

print("Training Dataset")
for class_dir in train_dir.iterdir():
    if class_dir.is_dir():
        print(f"{class_dir.name}: {len(list(class_dir.glob('*')))} audio files")

print(f"\nTest samples: {len(list(test_dir.glob('*')))} audio files")
```

## 🎧 Suggested Classroom Activity

1. Train an audio classification model using the training dataset.
2. Play each recording from the `Test_Set`.
3. Let the AI predict the bird species.
4. Compare the predictions with the correct answers.
5. Discuss how AI identifies different birds using only their sounds.

Questions for students:

- How are bird calls different from one another?
- Which bird species was easiest for the AI to recognize?
- Why do we use separate training and testing datasets?
- How would adding more recordings improve the model?

## ⚠️ Notes

- Audio samples were selected and prepared from a larger publicly available bird sounds dataset.
- Intended for educational purposes and beginner AI/ML projects.
- Designed for teaching audio classification and sound recognition concepts.
- Small size enables quick experimentation on local machines.
- Suitable for classroom demonstrations and guided learning activities.

## 📝 License

Public dataset for educational use.

## 🙏 Acknowledgments

The audio recordings in this mini dataset were selected from a larger publicly available bird sounds dataset. Credit belongs to the original dataset creators and contributors.

## 🔍 Keywords

Machine Learning for Kids, AI for Kids, Audio Classification, Bird Sound Classification, Bird Call Recognition, Bird Species Identification, Wildlife AI, Bioacoustics, Nature Sounds Dataset, Sound Recognition, Audio Pattern Recognition, Educational Dataset, Beginner Machine Learning Dataset, Artificial Intelligence Education, STEM Education, Supervised Learning, Audio Machine Learning, Mini Dataset, Small Dataset, Bird Audio Dataset

## 🏷️ Topics

#MachineLearning #ArtificialIntelligence #AudioClassification
#BirdSounds #BirdSoundClassification
#BirdCallRecognition #Bioacoustics
#WildlifeAI #NatureSounds
#MachineLearningForKids #AIForKids
#EducationalDataset #AudioDataset
#SupervisedLearning #PatternRecognition
#STEMEducation #MiniDataset
#SoundRecognition #EnvironmentalAI

## 👨‍💻 Author

Prepared and curated by **Khairullah Hamsafar** for educational and classroom learning purposes.

Focused on making Machine Learning, Artificial Intelligence, Audio AI, Computer Vision, Data Science, and Generative AI accessible to children, students, educators, and beginners.
