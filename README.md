# The Feeney Triangle

**A Generalised Recursive Triangle and its Mathematical Properties**

**Author:** Dominic Feeney

## About

The Feeney Triangle is a recursively generated family of triangular arrays determined by a starting value, a fixed constant, and a fixed binary operator.

The project investigates how the resulting triangles behave under different operators, including:

- Addition
- Subtraction
- Multiplication
- Division
- Exponentiation

The investigation began from an attempt to construct an extremely complicated mathematical pattern. During this process, recurring behaviour was observed in the resulting triangular array, leading to an investigation into why these patterns occur and whether they could be described algebraically.

The project develops a formal recursive definition, investigates diagonal and column behaviour, derives closed-form expressions where possible, and identifies several open problems for further investigation.

## Research Paper

The main result of the project is presented in:

**[Feeney Triangle — Research Paper](feeney-triangle.pdf)**

The LaTeX source used to produce the paper is also provided:

**[LaTeX Source](feeney-triangle.tex)**

## Research Notes

`research-notes.md` contains ongoing research material, including conjectures, computational investigations, intermediate results, and open questions that are not necessarily part of the final paper.

These notes are preserved to document the development of the investigation.

## Current Areas of Investigation

The project currently considers:

- Closed forms for different operators
- Behaviour of diagonal increments
- Mathematical properties of the resulting arrays
- Connections with existing recursive triangular arrays
- Computational interpretations
- Generalisation to arbitrary binary operations
- Higher-dimensional generalisations
- Further properties of the exponentiation case

## Status

This is an ongoing independent mathematical investigation. Some results in the research notes are conjectural and require further proof.

The published paper should therefore be distinguished from the ongoing research and conjectures contained in `research-notes.md`.

## Repository Structure

```text
Feeney-Triangle/
├── README.md
├── feeney-triangle.pdf
├── feeney-triangle.tex
└── research-notes.md