# Introduction
Log analysis is a major part of a support engineer’s work. It is crucial for understanding customer system behavior and diagnosing problems that may arise.

Log files capture thousands and thousandss of data points every day, which makes it difficult to identify patterns, detect unusual behavior, or even understand what is really happening in the system.

Thus, running scripts that retrieve important information, analyze it, and provide insightful results is essential.
In this context, I developed a script for my team that focuses on what we call “preprocessing,” a major pain point for our customers around the world.

# What's the preprocessing?
In medical imaging, the <b>preprocessing</b> refers to the set of operations applied to raw image data before higher-level tasks such as visualization, segmentation, registration, quantitative analysis, or AI inference.
The goal is to standardize, enhance, and clean the data so downstream algorithms can operate reliably and consistently.

Think of preprocessing like preparing ingredients before cooking a meal. When you get ingredients from the store, some are dirty, some are too big, too small, or inconsistent and some parts aren’t usable. 
Before you cook, you wash the groceries, peel or trim them, cut them into similar sizes, remove unwanted parts. Only after that can you cook your delicious meal. 
In medical imaging, it's the same thing:
- Raw medical images = groceries straight from the store.
- Preprocessing = washing, cutting, and organizing ingredients.
- Analysis / AI / measurements = cooking the meal.

![Preprocessing](Prétraitement des images médicales.png)
