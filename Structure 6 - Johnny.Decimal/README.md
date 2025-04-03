<div align="center">

# 🔢 Johnny.Decimal System

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Organization](https://img.shields.io/badge/Organization-System-blue)](https://johnnydecimal.com)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()

**A system to organize your digital and physical life**

[Getting Started](#getting-started) • 
[Documentation](#documentation) • 
[Examples](#examples) • 
[FAQ](#faq) • 
[Contributing](#contributing)

</div>

## 📑 Table of Contents

- [Overview](#overview)
- [Core Principles](#core-principles)
- [Number Structure](#number-structure)
- [Benefits](#benefits)
- [Getting Started](#getting-started)
  - [Step 1: Planning Your System](#step-1-planning-your-system)
  - [Step 2: Creating Areas](#step-2-creating-areas)
  - [Step 3: Defining Categories](#step-3-defining-categories)
  - [Step 4: Assigning IDs](#step-4-assigning-ids)
  - [Step 5: Implementation](#step-5-implementation)
- [Implementation Notes](#implementation-notes)
- [Examples](#examples)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)
- [Origins & Resources](#origins--resources)

## Overview

The Johnny.Decimal system is a numeric organization framework that provides a unique identifier for every item in your filesystem, making navigation, search, and recall significantly easier.

> **"A place for everything, and everything in its place."**

By using a structured numerical system, Johnny.Decimal transforms chaotic file management into an intuitive and efficient process.

## Core Principles

Johnny.Decimal relies on three fundamental components:

| Component | Description | Example |
|-----------|-------------|--------|
| **Areas** | Broad divisions (10 maximum) | `10-19 Finance` |
| **Categories** | Specific sections within areas (10 maximum per area) | `11 Tax Returns` |
| **IDs** | Individual identifiers for files/folders | `11.01 2024 Tax Return` |

## Number Structure

```
AA.NN
│  │
│  └─ Item ID (01-99)
│
└─── Category ID (11, 12, 13, etc.)
     within Area range (10-19, 20-29, etc.)
```

- **Areas**: Assigned a range in increments of 10 (e.g., `10-19`, `20-29`)
- **Categories**: Assigned a specific number within the area range (e.g., `11`, `12`, `13`...)
- **IDs**: Decimal extensions of categories (e.g., `11.01`, `11.02`, `11.03`...)

## Benefits

- ✅ **Unambiguous**: Each location has a unique numeric ID
- ✅ **Memorable**: Humans remember numbers well, especially in this structured pattern
- ✅ **Searchable**: Easy to find items by typing their ID
- ✅ **Navigable**: Simple to maintain and understand folder hierarchy
- ✅ **Flexible**: Can be adapted to any content or domain
- ✅ **Scalable**: Works for small personal projects or large team environments

## Getting Started

### Step 1: Planning Your System

Before creating any folders, plan your areas and categories:

- [ ] Identify major areas of your life/work (e.g., Finance, Projects, Personal)
- [ ] List categories within each area
- [ ] Sketch your structure on paper before implementation

### Step 2: Creating Areas

Assign number ranges to each area:

```
10-19 Finance
20-29 Projects
30-39 Personal
40-49 Health
...
```

> ⚠️ **Important**: Limit yourself to 10 areas maximum for simplicity and effectiveness.

### Step 3: Defining Categories

Within each area, create up to 10 categories:

```
10-19 Finance
  11 Tax Returns
  12 Investments
  13 Banking
  14 Insurance
  ...
```

### Step 4: Assigning IDs

Create decimal IDs for individual items:

```
11 Tax Returns
  11.01 2023 Federal Return
  11.02 2023 State Return
  11.03 Tax Receipts
  ...
```

### Step 5: Implementation

Create folders following your structure in your preferred filesystem:

```
/10-19 Finance/
  /11 Tax Returns/
    /11.01 2023 Federal Return/
    /11.02 2023 State Return/
    /11.03 Tax Receipts/
  /12 Investments/
    /12.01 Retirement Accounts/
    /12.02 Stock Portfolio/
...
```

## Implementation Notes

- Never use more than 10 areas (00-99) or 10 categories per area
- Keep a master index of your decimal system for reference
- Begin IDs with the same numbers as their parent category
- Use for both digital and physical organization (e.g., notebook pages, binders)
- Consider using Alfred, Spotlight, or other quick launchers to jump directly to IDs

## Examples

Here are some real-world Johnny.Decimal implementations:

<details>
<summary><strong>Personal File Management</strong></summary>

```
10-19 Personal Admin
  11 Identity
  12 Finance
  13 Insurance
  14 Medical
  15 Education

20-29 Household
  21 Home Maintenance
  22 Utilities
  23 Appliances
  24 Furniture

30-39 Work
  31 Career
  32 Job Applications
  33 Professional Development
  34 Business Ideas
```
</details>

<details>
<summary><strong>Project Management</strong></summary>

```
10-19 Project Administration
  11 Project Brief
  12 Contracts
  13 Timelines
  14 Meetings

20-29 Research
  21 Market Research
  22 Competitive Analysis
  23 User Interviews

30-39 Design
  31 Wireframes
  32 Mockups
  33 Prototypes
  34 Style Guide

40-49 Development
  41 Source Code
  42 Assets
  43 Documentation
  44 Testing
```
</details>

## FAQ

<details>
<summary><strong>Can I use letters instead of numbers?</strong></summary>

While the system is designed around numbers for their unique benefits, you could adapt it using letters. However, this reduces some of the system's inherent advantages, particularly in searchability and memorability.
</details>

<details>
<summary><strong>What if I need more than 10 categories in an area?</strong></summary>

Consider whether some categories could be combined or if a new area should be created. The 10-category limit encourages thoughtful organization and prevents excessive complexity.
</details>

<details>
<summary><strong>Can I implement this digitally only?</strong></summary>

Absolutely! While the system works for both physical and digital organization, it's perfectly suited for digital-only implementation.
</details>

<details>
<summary><strong>How do I handle projects that span multiple areas?</strong></summary>

You have two options:
1. Choose the most relevant area and place the project there
2. Use cross-references in your index to connect related items across areas
</details>

## Contributing

Contributions to this guide are welcome! If you have suggestions, improvements, or examples to share:

1. Fork this repository
2. Create a feature branch
3. Submit a pull request

## License

This documentation is licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).

## Origins & Resources

The Johnny.Decimal system was created by Johnny Noble. For more details, examples, and community resources:

- [Official Website](https://johnnydecimal.com)
- [Johnny.Decimal Community Forum](https://forum.johnnydecimal.com)
- [The Johnny.Decimal Blog](https://johnnydecimal.com/blog/)

---

<div align="center">

**Made with ❤️ by organized people**

</div>
