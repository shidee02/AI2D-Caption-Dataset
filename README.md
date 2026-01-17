# AI2D Caption Dataset

This repository presents a caption-annotated extension of the **AI2D (Allen Institute for AI Diagram Dataset)**. The dataset enriches scientific diagrams with concise, human-written natural language captions to support research in **diagram understanding, vision–language models, and multimodal reasoning**.

---

## Dataset Access Policy

The original AI2D images and annotations are **not redistributed** in this repository.

Researchers interested in the AI2D dataset may obtain it **directly from the original authors upon a reasonable academic request**.  
This repository releases only the **caption annotations and dataset structure**.

---

## Dataset Structure

Each data sample in this dataset follows the structure below:

```json
{
  "image_name": "string",
  "category": "string",
  "caption": "string"
}


## Dataset Structure

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row1Col1 | Row1Col2 | Row1Col3 |
| Row2Col1 | Row2Col2 | Row2Col3 |
| Row3Col1 | Row3Col2 | Row3Col3 |
| Row4Col1 | Row4Col2 | Row4Col3 |
| Row5Col1 | Row5Col2 | Row5Col3 |

