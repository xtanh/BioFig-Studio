# Reference 001: SMRTnet Fig.1

## Source and local visual reference

- Paper: Predicting small molecule–RNA interactions without RNA tertiary structures.
- Journal: Nature Biotechnology.
- DOI: https://doi.org/10.1038/s41587-025-02942-z
- Figure: Fig.1, Overview of SMRTnet; PDF page 3.
- Local original PDF: `local/paper.pdf`.
- User-selected image: `local/fig1.png`.
- Received: 2026-11-04.
- Original PDF and screenshot are retained locally and excluded from Git. Remote clones need these source files restored separately or retrieved from the source under its applicable terms.
- Before using this case to draw, inspect the reference image as well as these notes.

## User-confirmed preferences

Original feedback: “喜欢这张fig1。首先整体感觉让我觉得非常清楚。包括整体的配色感觉也很好看。模型的架构是简化版，但是非常清爽。”

Confirmed: overall clarity, overall color palette, and simplified yet clean model architecture.
Not yet confirmed: preference for every individual hue, icon, panel arrangement, or dense connection pattern. Do not turn a single example into a universal template.

## Scientific structure checked against the caption

Panel a provides the method overview: RNA sequence/secondary structure and small-molecule SMILES as inputs; binding score and potential binding site as outputs; experimental evaluation, tool comparison, and screening as downstream uses.

Panel b gives the architecture: PDB-derived training examples; separate sequence and structure branches for RNA and small molecules; encoders; multimodal data fusion; ensemble scoring. The RNA sequence encoder uses RNASwan-seq; the chemical language model is MoLFormer; structure branches use convolutional and graph-attention networks. The figure describes the final score as the median of five models from fivefold cross-validation. Treat these as properties of this paper, not defaults for future figures.

## Visual analysis: hypotheses to validate with more references

1. Two levels of explanation: panel a answers what the method does; panel b answers how it works. Model internals do not interrupt the first overview.
2. Stable reading direction: left-to-right stages; upper and lower encoder groups align their input, encoder, embedding, and fusion positions. Four colored chevrons reinforce the high-level stages between panels.
3. Semantic color and area hierarchy: white canvas; pale green/pink encoder backgrounds and pale blue fusion background; stronger blue, green, yellow, orange, purple, and red marks identify compact elements. The page feels light because strong colors occupy limited area, not because every color is pale.
4. Local consistency rather than one universal color meaning: layer colors are explained by the bottom legend and repeated in panel b; the stage strip in panel a has its own meanings. Avoid claiming every color encodes one biological entity throughout the whole figure.
5. Selective simplification: networks become familiar node-link symbols; computational layers become short rounded bars; embeddings and fusion are represented schematically. Modality distinctions and important paths remain visible; parameter-level detail is omitted.
6. Biological grounding: actual molecular structures on the left establish the data source; simplified RNA and chemical drawings explain modalities. The figure combines scientific structures and abstract model symbols purposefully.
7. Consistent visual grammar: thin dark connectors, flat illustrations, restrained backgrounds, short nearby labels, shared legend, and generous group spacing.
8. Remaining density: the middle fusion wiring is still busy. The user liked the whole figure, but has not explicitly endorsed this wiring density. New diagrams should preserve their true computational paths while simplifying routing where possible.

## Candidate rules for future drawings

- Start with the research message, inputs, outputs, and evidence/application before drawing architecture.
- Consider an overview plus architecture layout when two levels of explanation are needed; do not require it for every figure.
- Use pale region fills for grouping and stronger colors for small meaningful marks; define and repeat color meanings within each diagram.
- Compress repeated modules into consistent symbols while preserving scientifically important distinctions.
- Align parallel branches; keep labels near their objects; reserve detailed internals for supplementary views when appropriate.
- Transfer design principles rather than copying this paper's biological content, wiring, or evaluation procedure.

## Status

First reference only. No global style profile or validated drawing Skill yet. Compare subsequent references and trial drawings before promoting inferred preferences to requirements.
