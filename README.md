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

Caption Annotations (Sample Examples)
Image Name	Category	Caption
img_0001.png	Biology	The diagram illustrates photosynthesis.
img_0045.png	Physics	This figure explains wave propagation.
img_0123.png	Chemistry	The diagram represents an acid–base reaction.
img_0789.png	Engineering	A lever system showing pivot and force.
