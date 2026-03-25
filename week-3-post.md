
**Student:** Brian Dillion  
**Course:** Intro Artificial Intelligence (11122)  
**Institution:** Columbus State Community College  
**Date:** March 2026

---

## How Teachable Machine Uses Machine Learning

Teachable Machine is a browser-based tool developed by Google that applies 
supervised machine learning to image classification. The user defines two or 
more classes, collects image samples via webcam, and clicks Train Model. The 
tool builds a neural network that learns to distinguish visual patterns between 
the classes.

The process mirrors the seven steps of machine learning directly:

1. Data is collected via webcam samples
2. Data is prepared as captured frames
3. A model is trained using those frames
4. The model is evaluated in the preview panel
5. The model is deployed via an exportable URL

The user does not write code — the ML process runs entirely in the browser.

> Source: WIIT-7810 Course Slides, Machine Learning Part 2, Columbus State
> Community College[^1]

---

## Application: Whiskey Bottle vs. Wine Bottle Classifier

### What application did I create?

A two-class image classifier trained to distinguish between a whiskey bottle 
and a wine bottle using webcam images.

### What problem is it intended to solve?

Shape recognition within a shared object category. Wine bottles are largely 
uniform in shape across manufacturers; tall; cylindrical, consistent shoulder 
profile. Whiskey bottles vary considerably; square, ornamental, or otherwise 
distinct. The model tests whether ML can reliably identify those shape 
differences without explicit programmed rules.

Real-world applications include:

- Manufacturing quality control
- Automated inventory management
- Retail product identification[^2]

### Why did I choose this application?

Two reasons:

- Both objects are bottles, so the classifier must learn subtle differences in 
silhouette, color, and form. This is not for broad category differences
- It was a practical test of a core ML principle: consistent training data 
produces better models. Varying distance and angle during testing degraded 
classification confidence. Step 2 (Data Preparation).
### Performance

| Condition | Classification Result |
|-----------|:---------------------:|
| Consistent distance and angle | Reliable |
| Varied distance or angle | Degraded confidence |

Variability in distance or camera angle introduced misclassification — 
confirming that data quality and collection consistency directly affect 
model performance.

---

## Model

[Whiskey vs. Wine Bottle Classifier](https://teachablemachine.withgoogle.com/models/zhLLmbYmF/)

---
[^1]: WIIT-7810 Course Slides. (2025). Machine Learning Part 2. Columbus State Community College.
[^2]: Google. (2025). Teachable Machine. https://teachablemachine.withgoogle.com
