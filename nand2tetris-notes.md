# Nand2Tetris — Learning Notes

## Overview

Nand2Tetris is a course that teaches how to build a computer system from fundamental logic gates to a functioning computer.

The goal of this document is to record my learning process, explanations, experiments, and observations as I progress through the course.

## 1. Boolean Logic

Boolean logic is a system of mathematics based on two possible values:

- `0` — False
- `1` — True

It is fundamental to digital computing because computer hardware processes information using binary representations.

### Basic Boolean Operations

| Operation | Description |
|---|---|
| NOT | Reverses the input value |
| AND | Outputs 1 only when both inputs are 1 |
| OR | Outputs 1 when at least one input is 1 |
| XOR | Outputs 1 when the inputs differ |

## 2. NAND Gate

A NAND gate performs the opposite of an AND operation.

Its output is 0 only when both inputs are 1. For every other input combination, the output is 1.

| A | B | NAND Output |
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

NAND is known as a universal gate because combinations of NAND gates can implement any Boolean function.

## 3. Learning Progress

This section will expand as I study more concepts, implement hardware components, and test them using the Nand2Tetris tools.

## Resources

- [Nand2Tetris Official Website](https://www.nand2tetris.org/)
