# SVEN: Machine Vision for Tactile Perception

> Teaching machines to feel through sight

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Research Status](https://img.shields.io/badge/Status-Research%20Prototype-blue.svg)]()
[![Harvard](https://img.shields.io/badge/Institution-Harvard-crimson.svg)]()

## Overview

SVEN is a research project that explores how computer vision systems can evolve beyond simple object recognition to understand the textural and material qualities that define human sensory experience.

## The Problem

Current computer vision systems excel at identifying and classifying objects but fail to perceive the material properties that humans intuitively understand. A child can recognize ice cream not just by its shape, but by understanding its material qualities—the surface that promises coldness and creaminess. This research addresses the fundamental gap between machine object detection and human multisensory perception.

## Our Approach

SVEN redefines both the inputs and outputs of machine vision:

- **Inputs**: Finer-scale visual details and motion that mirror human texture perception
- **Outputs**: Rich artifacts like texture maps and simulations instead of simple text descriptions

Using a microscopic imaging system built around a small field microscope, SVEN captures surface landscapes invisible to the naked eye and translates them into "machine touch" descriptions.

## Key Features

### 🔬 **Microscopic Texture Capture**
- Systematic surface scanning at microscopic resolution
- Programmable motion control for consistent data collection
- Mobile device integration for real-time adjustments

### 🧠 **Three Analytical Workflows**

1. **Spatial Texture Mapping**: Maps environments through tactile qualities rather than object identification
2. **Machine Tactile Visual Generation**: Reimagines objects through generated textures from edge maps
3. **Temporal Texture Dynamics**: Captures how materials change over time and space

### 📊 **Novel Perception Metrics**
- **Edge Density**: Quantifies visual texture complexity
- **Grain Continuity**: Measures surface pattern consistency
- **Temporal Texture Evolution**: Tracks material changes across time

## Repository Structure

```
sven-tactile-perception/
├── sven-research-overview/     # Main documentation and coordination
├── sven-hardware/              # Device design and assembly
├── sven-computer-vision/       # Core CV algorithms
├── sven-data-analysis/         # Analysis workflows and visualizations
├── sven-datasets/              # Curated texture datasets
├── sven-mobile-app/            # Control interface
├── sven-web-interface/         # Visualization platform
└── sven-experiments/           # Research prototypes
```

## Quick Start

### Prerequisites
- Python 3.8+
- OpenCV 4.0+
- Microscope hardware (or sample datasets)

### Installation
```bash
git clone https://github.com/your-org/sven-computer-vision.git
cd sven-computer-vision
pip install -r requirements.txt
```

### Basic Usage
```python
from sven import TextureAnalyzer, SpatialMapper

# Initialize analyzer
analyzer = TextureAnalyzer()

# Process surface image
texture_map = analyzer.analyze_surface("path/to/surface_image.jpg")

# Generate spatial mapping
mapper = SpatialMapper()
environment_map = mapper.create_texture_map(texture_map)
```

## Results & Findings

- **Textural Identity Discovery**: Different environments possess unique textural signatures
- **Indoor/Outdoor Clustering**: Distinct patterns in color variation vs. hue relationships
- **Spatial Texture Mapping**: Successfully created maps based on tactile qualities rather than object placement

## Research Applications

- **Material Science**: Understanding surface properties through visual analysis
- **Robotics**: Enhanced tactile feedback for manipulation tasks
- **Architecture**: Designing spaces based on textural experience
- **Accessibility**: Creating tactile descriptions for visually impaired users
- **Digital Art**: Generating texture-based creative content

## Contributing

We welcome contributions from researchers, developers, and anyone interested in expanding machine perception capabilities.

### Research Collaboration
- Share texture datasets
- Propose new analysis methods
- Report findings and replications
- Suggest hardware improvements

## Hardware

The SVEN prototype uses readily available components:
- Field microscope (base imaging system)
- Programmable motion control (Arduino-based)
- Mobile device integration
- 3D-printed mounting system

See [sven-hardware](https://github.com/your-org/sven-hardware) for complete assembly instructions.

## Datasets

We provide curated texture datasets collected from various environments:
- Indoor surfaces (rugs, wood floors, tiles)
- Outdoor textures (bark, stone, fabric)
- Material categories with metadata
- Collection protocols and quality metrics

Access datasets at [sven-datasets](https://github.com/your-org/sven-datasets).

## Academic Use

### Citation
If you use SVEN in your research, please cite:
```bibtex
@article{sven2025,
  title={SVEN: Machine Vision for Tactile Perception},
  author={Sophia Cabral Casino},
  year={2025},
  note={Research prototype available at https://github.com/your-org/sven-tactile-perception}
}
```

## Roadmap

- [ ] **Phase 1**: Hardware refinement and data collection expansion
- [ ] **Phase 2**: Deep learning model development for texture classification
- [ ] **Phase 3**: Real-time processing and mobile deployment
- [ ] **Phase 4**: Integration with robotic systems
- [ ] **Phase 5**: Large-scale texture database creation

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by Harun Farocki's "eye/machine trilogy"
- Built on affordance theory by J.J. Gibson
- Informed by Sherry Turkle's work on human-object relationships
- Research on human tactile perception (Schifferstein and Cleiren, 2005)

## Contact

- **Project Lead**: Sophia Cabral Casino - [sophiagcabral@gmail.com](mailto:sophiagcabral@gmail.com)
- **Organization**: Harvard University


---

*"We think with the objects we love; We love the objects we think with."* - Sherry Turkle

**SVEN helps machines think with the textures that surround us.**
