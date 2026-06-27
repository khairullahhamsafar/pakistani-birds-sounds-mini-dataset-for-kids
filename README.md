# Pakistani Birds Sounds Classification Mini Dataset for Kids

A small, kid-friendly bird sounds dataset designed for teaching machine learning, artificial intelligence, and audio classification concepts to children and beginners.

This dataset helps students learn how AI can recognize patterns in audio recordings and classify bird species based on their vocalizations.

## 📁 Dataset Structure

```text
Pakistani_Birds_Sounds_Classification_Mini_Dataset_For_Kids/
├── Buff_Browed_Chachalaca/          # 10 audio samples
├── Lesser_Nothura/                  # 10 audio samples
├── Puna_Tinamou/                    # 10 audio samples
├── Quebracho_Crested_Tinamou/       # 10 audio samples
└── White_Crested_Guan/              # 10 audio samples
```

### Classes

- `Buff_Browed_Chachalaca`
- `Lesser_Nothura`
- `Puna_Tinamou`
- `Quebracho_Crested_Tinamou`
- `White_Crested_Guan`

## 🎯 Purpose

This dataset is perfect for:

- Teaching machine learning to kids
- Introduction to audio classification
- Bird species recognition projects
- Learning about sound pattern recognition
- Artificial intelligence and computer vision education
- STEM and AI classroom activities
- Exploring wildlife conservation through AI

## 📊 Details

| Attribute | Value |
|-----------|---------|
| Classes | 5 bird species |
| Audio samples per class | 10 |
| Total audio samples | 50 |
| Dataset size | Mini/small |
| Source | Selected from a larger publicly available bird sounds dataset |

## 🧠 Learning Objective

Using this dataset, students can:

1. Train a simple audio classification model
2. Learn how AI recognizes sound patterns
3. Understand supervised machine learning
4. Explore biodiversity using artificial intelligence
5. Learn the difference between image and audio classification
6. Build beginner-friendly wildlife AI applications

## 🚀 Quick Start

```python
from pathlib import Path

dataset_dir = Path("Pakistani_Birds_Sounds_Classification_Mini_Dataset_For_Kids")

for class_dir in dataset_dir.iterdir():
    if class_dir.is_dir():
        print(
            f"{class_dir.name}: "
            f"{len(list(class_dir.glob('*')))} audio files"
        )
```

## 🎧 Suggested Classroom Activity

1. Train an audio classification model using the bird sound recordings.
2. Test the model with unseen bird sounds.
3. Compare predictions with the correct bird species.
4. Discuss how AI distinguishes one bird species from another using sound patterns.

Questions for students:

- How are bird sounds different from one another?
- Why can computers learn to recognize bird calls?
- What challenges might occur if two bird species sound similar?
- How could collecting more audio samples improve the model?

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

Machine Learning for Kids, AI for Kids, Audio Classification, Bird Sound Classification, Bird Call Recognition, Bioacoustics, Wildlife AI, Nature Sounds Dataset, Sound Recognition, Audio Pattern Recognition, Educational Dataset, Beginner Machine Learning Dataset, Artificial Intelligence Education, STEM Education, Supervised Learning, Audio Machine Learning, Mini Dataset, Small Dataset, Bird Species Classification, Environmental AI

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

Focused on making Machine Learning, Artificial Intelligence, Computer Vision, Audio AI, Data Science, and Generative AI accessible to children, students, educators, and beginners.
