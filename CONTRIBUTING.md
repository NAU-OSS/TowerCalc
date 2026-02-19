# Contributing to TowerCalc

Thank you for your interest in contributing! 🎉  
This project aims to provide a transparent and accurate DPS calculation and combat simulation tool for Anime World Tower Defense players.

We welcome bug reports, feature suggestions, documentation improvements, and code contributions.

---

## How to Contribute

### 1. Fork the Repository
- Click the **Fork** button on GitHub.
- Clone your fork locally:
  ```bash
  git clone https://github.com/your-username/TowerCalc.git
  cd TowerCalc

## 2. Create a Branch

Create a new branch for your feature or fix:

git checkout -b feature/short-description

## 3. Make Your Changes

Write clear, readable, and tested code.

## 4. Commit Changes

Use descriptive commit messages:

git commit -m "Add burn passive stacking calculation"

## 5. Open a Pull Request

Push your branch and open a Pull Request against main.
Clearly explain:

- What you changed

- Why you changed it

- Any assumptions made

## Reporting Bugs

If you find a bug:

Open a GitHub Issue

Include:

- A clear description of the issue

- Steps to reproduce

- Expected behavior

- Actual behavior

- Screenshots or logs (if applicable)

Please check existing issues before creating a new one.

## Proposing New Features

To propose a new feature:

Open a GitHub Issue labeled Feature Request

Describe:

- The problem your feature solves

- The proposed solution

- Any alternative approaches considered

Example use cases

Major feature proposals may require discussion before implementation.

## Testing Requirements

All contributions must:

- Include tests for new functionality

- Not break existing tests

- Pass all test cases before submitting a Pull Request

If adding new mechanics (e.g., passives, leader skills), include:

Mathematical verification

Edge case handling (stacking limits, durations, etc.)

## Code Style Guidelines

Follow PEP 8 (for Python projects)

Use descriptive variable names

Keep functions small and focused

Add comments for complex calculations

Avoid unnecessary global state

Example:

def calculate_burn_damage(base_damage: float, ticks: int) -> float:
    """Calculate total burn damage over a number of ticks."""

## Documentation Standards

Public functions must include docstrings

Complex formulas should include explanations

Update README.md if adding new features

Clearly document new passives or mechanics

Good documentation helps maintain transparency in damage calculations.

## 🤝 Community Guidelines

Please:

Be respectful and constructive

Provide clear feedback

Assume good intent

Keep discussions focused and professional

Harassment, toxic behavior, or personal attacks will not be tolerated.

## 📌 Project Goals

This project focuses on:

Accurate DPS modeling

Transparent calculation logic

Expandable combat simulation systems

Community-driven improvements

Thank you for contributing!
