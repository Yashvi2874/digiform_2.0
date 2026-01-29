# CADify : Where ideas take shape!

An AI-powered **Prompt-to-CAD** application that transforms natural language descriptions into parametric 3D CAD models.

## Overview

CADify leverages modern large language models (LLMs) and geometric processing libraries to understand engineering intent and generate manufacturable designs with proper feature trees and parametric constraints. Simply describe what you want to build in natural language, and CADify creates a complete 3D parametric model ready for manufacturing.

## Key Features

- **Natural Language Processing**: Describe your design in plain English with engineering terminology
- **Parametric 3D Models**: Generate fully parametric models with editable dimensions and constraints
- **Feature Trees**: Complete hierarchical feature trees showing all modeling operations
- **Smart Sketching**: Automatically generates fully constrained 2D sketches for 3D features
- **CAD Export**: Export to STEP, STL, and native CAD formats (SolidWorks, Fusion 360)
- **AI Design Assistant**: Get manufacturability analysis and design improvement suggestions
- **Real-time Validation**: Instant feedback on geometric consistency and manufacturing constraints

## Example Usage

```
"Create a rectangular bracket with mounting holes. The bracket should be 100mm long, 50mm wide, and 10mm thick. Add two 8mm diameter holes positioned 20mm from each end, centered on the width."
```

CADify will generate:
- A complete 3D parametric model
- Fully constrained sketches
- Feature tree with all operations
- Editable parameters for all dimensions
- Manufacturing analysis and suggestions

## Architecture

Built on a modular architecture with:
- **Prompt Parser**: Extracts geometric specifications from natural language
- **Intent Analyzer**: Understands design requirements and constraints  
- **Geometry Planner**: Plans optimal CAD operation sequences
- **Model Generator**: Creates 3D geometry using OpenCASCADE Technology
- **Parametric Engine**: Manages parameters and constraint solving
- **Validation Engine**: Ensures geometric validity and manufacturability

## Getting Started

1. Clone the repository
2. Install dependencies
3. Run the application
4. Enter your design description in natural language
5. Review and modify the generated parametric model
6. Export to your preferred CAD format

## Export Formats

- **STEP** - Universal CAD format for professional workflows
- **STL** - 3D printing and rapid prototyping
- **Native formats** - SolidWorks, Fusion 360, AutoCAD (where supported)

## Performance

- Simple models: Generated in under 10 seconds
- Complex models: Generated in under 60 seconds  
- Supports up to 100 parametric features
- Real-time parameter updates and validation

## Contributing

We welcome contributions! Please see our contributing guidelines for details on how to submit pull requests, report issues, and suggest improvements.

## Copyright

Copyright (c) 2025 CADify Contributors. All rights reserved.

## Acknowledgments

- Built with [OpenCASCADE Technology](https://www.opencascade.com/) for geometric modeling
- Inspired by research in text-to-CAD generation including CADmium, Query2CAD, and LLM4CAD
- Special thanks to the open-source CAD and AI communities

Transform your design ideas into manufacturable CAD models with the power of AI.
