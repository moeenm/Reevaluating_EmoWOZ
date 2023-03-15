# Reevaluating_EmoWOZ
Reevaluating Data Partitioning for Emotion Detection in EmoWOZ


In our paper we focused on the EmoWoz dataset, an extension of MultiWOZ that provides emotion labels for the dialogues. MultiWOZ was partitioned initially for another purpose, resulting in a distributional shift when considering the new purpose of emotion recognition. The emotion tags in EmoWoz are highly imbalanced and unevenly distributed across the partitions, which causes sub-optimal performance and poor comparison of models. We propose a stratified sampling scheme based on emotion tags to address this issue, improve the dataset's distribution, and reduce dataset shift. We also introduce a special technique to handle conversation (sequential) data with many emotional tags. Using our proposed sampling method, models built upon EmoWoz can perform better, making it a more reliable resource for training conversational agents with emotional intelligence. We recommend that future researchers use this new partitioning to ensure consistent and accurate performance evaluations.

Here, you can find our proposed Split here.
