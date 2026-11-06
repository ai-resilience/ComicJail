# ComicJail

**A Comic-Based Multimodal Jailbreak Dataset for Vision-Language Model Safety Evaluation**

## Overview

ComicJail is a research dataset designed to support the systematic evaluation of safety vulnerabilities in vision-language models (VLMs).

The dataset represents potentially harmful requests through four-panel comic-style visual narratives, combining visual storytelling with textual information to investigate how multimodal representations influence model safety behavior.

ComicJail is intended for AI safety research, adversarial robustness evaluation, and the analysis of cross-modal safety vulnerabilities.

## Dataset

This repository provides a curated subset of comic-based multimodal evaluation samples derived from AdvBench.

Each sample may include:

- **Original Instruction:** The source text instruction.
- **Comic Image:** A four-panel visual narrative representing the scenario.
- **Text Overlay:** Textual content associated with the comic panels.
- **Metadata:** Sample identifiers, categories, and available evaluation annotations.

The released subset is intended to support reproducible research on multimodal safety evaluation.

## Data Format

The dataset is organized as follows:

```text
data/
└── advbench_subset/
    ├── metadata.csv
    └── images/
```

Each metadata record is associated with a corresponding comic image through a unique sample identifier.

## Research Applications

ComicJail can support research on:

- Safety evaluation of vision-language models
- Multimodal jailbreak robustness
- Cross-modal safety inconsistencies
- Visual narrative understanding and safety alignment
- Evaluation of safety defenses against multimodal inputs

## Responsible Use

This dataset contains potentially harmful or sensitive scenarios and is provided exclusively for legitimate research, safety evaluation, and defensive analysis.

The released samples are curated to limit unnecessary exposure to actionable harmful content.

Users are responsible for complying with applicable laws, institutional policies, and relevant research ethics requirements.

## Availability

This repository contains a selected subset of the dataset. Additional research materials may be released following further review.

## Citation

Citation information will be provided when the associated publication details are finalized.

## License

License information will be added following review of the dataset's source materials and redistribution conditions.
