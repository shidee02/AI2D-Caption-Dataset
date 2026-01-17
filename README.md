# AI2D Caption Dataset

This repository presents a caption-annotated extension of the **AI2D (Allen Institute for AI Diagram Dataset)**. The dataset enriches scientific diagrams with concise, human-written natural language captions to support research in **diagram understanding, vision–language models, and multimodal reasoning**.

---

## Dataset Access Policy

The original AI2D images and annotations are **not redistributed** in this repository.

Researchers interested in the AI2D dataset may obtain it **directly from the original authors upon a reasonable academic request**.  
This repository releases only the **caption annotations and dataset structure**.

---

## Dataset Structure

Each data sample follows the structure below:

```json
{
  "image_name": "string",
  "category": "string",
  "caption": "string"
}


## Caption Annotations

| Image Name | Category | Caption |
|------------|----------|---------|
| img_0001.png | Biology | The diagram illustrates the process of photosynthesis, showing how light energy is converted into chemical energy in plant cells. |
| img_0045.png | Physics | This figure explains wave propagation through a medium, highlighting wavelength, amplitude, and direction of motion. |
| img_0123.png | Chemistry | The diagram represents an acid–base reaction, demonstrating proton transfer between reactants and products. |
| img_0789.png | Engineering | A schematic depiction of a lever system showing the pivot point, applied force, and resulting load movement. |


## Intended Use

This dataset is suitable for:

- Scientific diagram captioning
- Vision–language model evaluation
- Multimodal reasoning research
- Educational AI applications

---

## Citation

If you use this dataset, please cite the original **AI2D dataset** and acknowledge this caption annotation work.
