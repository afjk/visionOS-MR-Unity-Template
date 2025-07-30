# visionOS-MR-Unity-Template

A Unity template for developing Mixed Reality (MR) applications on Apple Vision Pro using visionOS.

## Overview

This repository provides a ready-to-use Unity project template specifically designed for Mixed Reality application development on Apple Vision Pro. The template includes pre-configured settings, essential packages, and optimized configurations for visionOS development.

### Key Features

- **Unity 6000.0.48f1** - Latest LTS Unity version
- **PolySpatial for visionOS** - Unity's official visionOS development framework
- **visionOS XR Plugin** - Native visionOS XR support
- **XR Interaction Toolkit** - Unity's XR interaction framework
- **Universal Render Pipeline (URP)** - Optimized rendering for mixed reality
- **XR Hands** - Hand tracking support for natural interactions
- **Input System** - Modern input handling

## Setup Instructions

For detailed setup instructions and development guide, please refer to the comprehensive tutorial on Qiita:

📖 **[visionOS MR App Development Setup Guide](https://qiita.com/afjk/items/099c75f8285f19dfd470)**

### Quick Start

1. **Clone or download** this repository
2. **Open in Unity 6000.0.48f1** or later
3. **Follow the Qiita tutorial** for detailed visionOS development environment setup
4. **Build and deploy** to your Apple Vision Pro device or simulator

## Project Structure

```
Assets/
├── Scenes/
│   └── SampleScene.unity          # Main scene with basic MR setup
├── Settings/                      # XR and project settings
├── XR/                           # XR-related assets and configurations
├── XRI/                          # XR Interaction Toolkit assets
└── Resources/                    # Runtime resources

Packages/
└── manifest.json                 # Package dependencies including visionOS SDK
```

## Package Dependencies

This template includes the following key packages:

- **PolySpatial for visionOS** (v2.3.1) - Unity's official visionOS development framework
- **visionOS XR Plugin** (v2.2.4) - Native visionOS XR support and integration
- **XR Interaction Toolkit** (v3.2.0) - Unity's XR interaction system
- **XR Hands** (v1.6.1) - Hand tracking support for natural interactions
- **Universal Render Pipeline** (v17.0.4) - Optimized rendering pipeline
- **Input System** (v1.14.0) - Modern input handling system
- **AI Navigation** (v2.0.8) - Navigation and pathfinding for 3D environments

## Usage

1. **Development Environment**: Follow the [Qiita setup guide](https://qiita.com/afjk/items/099c75f8285f19dfd470) to configure your visionOS development environment
2. **Scene Setup**: Start with the included `SampleScene.unity` which contains basic MR components
3. **Build Settings**: The project is pre-configured for visionOS builds targeting Apple Vision Pro
4. **Testing**: Deploy to your Apple Vision Pro device or test in the visionOS Simulator

## Requirements

- **Unity 6000.0.48f1** or later
- **Apple Vision Pro** device or visionOS Simulator
- **macOS** with Xcode for building
- **Apple Developer Account** for device deployment
- **PolySpatial package** for visionOS development

## Contributing

Feel free to submit issues and enhancement requests. This template is designed to be a starting point for visionOS MR development.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Resources

- 📖 [Setup Guide (Qiita)](https://qiita.com/afjk/items/099c75f8285f19dfd470)
- 🔗 [Unity PolySpatial Documentation](https://docs.unity3d.com/Packages/com.unity.polyspatial@2.3/manual/index.html)
- 🔗 [Apple visionOS Developer Documentation](https://developer.apple.com/visionos/)
- 🔗 [Unity XR Interaction Toolkit](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@3.2/manual/index.html)
- 🔗 [Unity visionOS Development](https://unity.com/features/visionos)

---

**Happy MR Development on visionOS! 🥽✨**
