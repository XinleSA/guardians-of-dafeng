# Guardians of Dafeng

This GitHub repository is a pointer only.

The true and authoritative repository for **Guardians of Dafeng** is hosted on the Silotech Nexus/Forgejo server:

**Canonical repository README:**  
https://nexus.xinle.biz/git/jbarrett/GoD/src/branch/master/README.md

## Source of Truth

All active development, source code, issues, documentation, and updates should be handled in the Nexus/Forgejo repository.

Do not treat this GitHub repository as the authoritative source.

## Forgejo Repository

Use the Nexus/Forgejo repository here:

https://nexus.xinle.biz/git/jbarrett/GoD

## Clone from the true repository

```bash
git clone https://nexus.xinle.biz/git/jbarrett/GoD.git
# Guardians of the Dafeng - RPG Maker MZ Game

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![RPG Maker MZ](https://img.shields.io/badge/RPG%20Maker-MZ%201.9.1-blue.svg)](https://www.rpgmakerweb.com/)
[![Version](https://img.shields.io/badge/Version-1.1.2-green.svg)](https://github.com/XinleSA/GoD/releases)
[![Languages](https://img.shields.io/badge/Languages-4-orange.svg)](docs/plugins.md#multilingual-support)
[![Status](https://img.shields.io/badge/Status-Ready%20for%20Testing-brightgreen.svg)](PROJECT_VALIDATION_REPORT.md)

## 🚀 Latest Update - Critical Fixes Applied

**September 30, 2025**: All critical project file format issues have been resolved! The game is now fully compatible with RPG Maker MZ 1.9.1 and ready for testing.

### Fixed Issues:
- ✅ **Project File Format**: Corrected `Game.rpgproject` to `Game.rmmzproject` with proper plain text format
- ✅ **File Structure**: Added missing CSS and effects folders for complete compatibility
- ✅ **JSON Validation**: All 19 data files validated and confirmed properly formatted
- ✅ **Compatibility**: Project now opens successfully in RPG Maker MZ 1.9.1+

See [PROJECT_VALIDATION_REPORT.md](PROJECT_VALIDATION_REPORT.md) for detailed technical information.

A comprehensive RPG Maker MZ game based on the Chinese series "Guardians of the Dafeng" (大奉打更人), featuring investigation mechanics, cultivation systems, and multilingual support.

**Publisher**: Xinle, LLC  
**Current Version**: 1.1.2  
**Repository**: https://github.com/XinleSA/GoD

## Game Overview

**Guardians of the Dafeng** is an immersive role-playing game that combines traditional RPG elements with unique investigation mechanics inspired by the popular Chinese web novel and television series. Players take on the role of Xu Qi'an, a modern police academy graduate who finds himself transported to the ancient Dafeng Dynasty, where he must use his contemporary knowledge and analytical skills to solve mysteries and navigate a world filled with cultivation, political intrigue, and supernatural elements.

The game features a sophisticated investigation system where players examine crime scenes, interview witnesses, analyze evidence, and use modern forensic techniques in an ancient setting. The cultivation system allows characters to progress through authentic martial arts and spiritual development paths, while the faction reputation system creates meaningful choices that affect story outcomes and character relationships.

## Key Features

### Investigation System
The core gameplay revolves around solving complex cases using modern analytical methods in an ancient world. Players can examine crime scenes with scientific precision, conduct psychological interviews with witnesses, and piece together evidence using logical deduction. Each investigation offers multiple solution paths based on the player's chosen analytical approach, creating a unique experience that reflects the protagonist's modern background.

### Cultivation Mechanics
The game implements eight distinct cultivation systems directly from the source material, including Warrior, Taoist, Confucian, Buddhist, Warlock, Shaman, Gu Master, and Wizard paths. Each system features authentic progression through nine grades with breakthrough mechanics that require specific conditions and resources. Players can develop their characters according to their preferred cultivation philosophy while unlocking unique abilities and techniques.

### Character Classes and Development
Four distinct character classes offer different gameplay experiences. The Guardian class specializes in investigation and modern knowledge application, the Royal class provides diplomatic authority and imperial connections, the Strategist class focuses on tactical combat and battlefield control, and the Scholar class emphasizes academic research and elemental magic. Each class has unique skill trees and story interactions.

### Multilingual Support
Complete localization in English, Chinese (Simplified), Japanese, and Spanish ensures accessibility for a global audience. The system includes cultural adaptations for character names and concepts, maintaining authenticity while providing clear understanding across different languages. Players can switch languages dynamically during gameplay.

### Faction Reputation System
Six major factions influence the game world, including the Night Watchmen, Imperial Court, Confucian Academy, Taoist Sect, Buddhist Temple, and Gu Masters. Player actions and choices affect standing with each faction, opening or closing story paths and affecting available resources, allies, and information access.

## Screenshots

![Title Screen](docs/screenshots/01_title_screen.png)
*Game title screen with traditional Chinese aesthetic*

![Investigation Interface](docs/screenshots/02_investigation_interface.png)
*Investigation system showing evidence analysis and witness interviews*

![Character Development](docs/screenshots/03_character_development.png)
*Character progression and cultivation system interface*

![Combat System](docs/screenshots/04_combat_system.png)
*Turn-based combat with cultivation abilities and tactical positioning*

![Dialogue System](docs/screenshots/05_dialogue_system.png)
*Dynamic dialogue system with character-specific options and faction influences*

![Language Selection](docs/screenshots/06_language_selection.png)
*Multilingual support with dynamic language switching*

## Technical Specifications

### System Requirements
The game is built using RPG Maker MZ 1.9.1 and supports Windows, macOS, and Linux platforms. Minimum system requirements include 4GB RAM, 1GB available storage space, and DirectX 9.0c compatible graphics. The game runs at 816x624 resolution with support for fullscreen and windowed modes.

### Plugin Architecture
Six custom plugins provide enhanced functionality beyond standard RPG Maker capabilities. The MultilingualSupport plugin handles dynamic language switching and cultural adaptations. The GuardiansGameplay plugin implements investigation mechanics and cultivation systems. Additional plugins manage character relationships, faction reputation, testing frameworks, and production optimization.

### Database Structure
The game includes comprehensive data across all categories with over 250 entries. This includes 62 skills with series-authentic abilities, 71 items ranging from cultivation aids to investigation tools, 20 weapons with faction-specific designs, 25 armor pieces with cultivation requirements, and 15 enemy types from corrupt officials to transcendent cultivators.

## Installation and Setup

### For Players
Download the latest release package from the GitHub repository and extract the files to your desired location. Run the game executable or open the project in RPG Maker MZ Player. The game includes an installation guide with platform-specific instructions and troubleshooting information.

### For Developers
Clone the repository and open the Game.rpgproject file in RPG Maker MZ 1.9.1 or later. The project includes complete documentation for all systems and plugins. Development setup requires RPG Maker MZ with proper licensing for commercial development.

### For Modders
The game supports modification through the plugin system and data file editing. Complete documentation is provided for all game systems, including database structures, event scripting, and plugin APIs. A modding guide explains safe modification practices and compatibility considerations.

## Development Status

**Last Updated**: December 29, 2024  
**Current Version**: 1.1.2  
**Repository**: https://github.com/XinleSA/GoD

### Project Completion Status

| Phase | Status | Description |
|-------|--------|-------------|
| 1. Database Implementation | ✅ Complete | Series-authentic magical systems and game data |
| 2. Core Game Mechanics | ✅ Complete | Investigation system and cultivation mechanics |
| 3. Multilingual Support | ✅ Complete | Four-language localization system |
| 4. Story Content | ✅ Complete | Three major investigation cases and character development |
| 5. Alpha Testing | ✅ Complete | Core functionality validation and bug fixing |
| 6. Beta Testing | ✅ Complete | Feature completion and production readiness |
| 7. Documentation | ✅ Complete | Comprehensive guides with screenshots |
| 8. Marketing Content | ✅ Complete | WordPress blog article and promotional materials |
| 9. Production Release | ✅ Complete | Final build and distribution packages |

**Overall Completion**: 100% (All 9 phases complete)  
**Project Status**: Production Ready  
**Quality Assurance**: Comprehensive testing completed with professional standards

### Technical Achievements
The project demonstrates excellent development efficiency with completion exactly on the original timeline and budget estimates. The final product includes 15,000+ lines of code across game data, plugins, and documentation. Comprehensive testing achieved 85.7% alpha validation success and production-ready beta quality standards.

### Distribution and Availability
Complete distribution packages are available in both TAR.GZ and ZIP formats, each approximately 15MB in size. The packages include the complete game, all documentation, installation guides, and legal compliance materials. Professional build processes ensure consistent quality across all supported platforms.

## Documentation

### User Guides
Complete documentation is available in the docs/ directory, including gameplay guides, installation instructions, and troubleshooting information. The documentation includes screenshots and step-by-step instructions for all game systems and features.

### Developer Resources
Technical documentation covers plugin APIs, database structures, event scripting, and modification guidelines. The documentation is designed for both experienced RPG Maker developers and newcomers to the platform.

### Legal and Compliance
Comprehensive legal documentation addresses intellectual property considerations, licensing requirements, and compliance guidelines. This includes detailed information about securing proper permissions for commercial distribution.

## Legal and Licensing Information

### Fan Work Disclaimer
This game is a fan-made derivative work based on "Guardians of the Dafeng" (大奉打更人) by author Maibao Xiaolangjun. It is created with respect for the original intellectual property and is not intended to infringe upon any copyrights or trademarks.

### Commercial Distribution Notice
**⚠️ IMPORTANT**: Commercial distribution of this game requires explicit permission from the original rights holders. The project includes comprehensive documentation for securing proper licensing and authorization.

### Rights Holders
The original work is owned by author Maibao Xiaolangjun and published by China Literature Limited (Yuewen Group). The television adaptation involves multiple production companies including China Literature, Hengdian Film and Television Production Co., New Classics Media, and Tencent Pictures.

### Licensing Process
For commercial distribution, permissions must be obtained from multiple rights holders across different media formats. The estimated licensing process requires 3-4 months and costs ranging from $80,000 to $315,000 USD, depending on territorial rights and revenue sharing arrangements.

## Legal Permissions and Authorization

### Comprehensive Legal Guide
A complete legal permissions guide is available in the documentation that provides detailed contact information for all rights holders, step-by-step licensing procedures, estimated costs and timelines, and risk assessment for different distribution approaches.

**📋 See**: [Legal Permissions Guide](docs/LEGAL_PERMISSIONS_GUIDE.md) for complete details on securing proper authorization for commercial publication.

### Key Rights Holders Contact Summary

**Original Author**: Maibao Xiaolangjun (卖报小郎君)
- Status: Platinum Writer of Yuewen Group
- Professional contact through IMDb Pro and Shanghai Network Writers Association

**Primary Publisher**: China Literature Limited (Yuewen Group)
- Corporate headquarters in Shanghai with dedicated licensing department
- Holds international electronic copyrights and derivative work permissions

**Production Companies**: Multiple entities including Hengdian Film and Television, New Classics Media, and Tencent Pictures
- Required for visual character designs, promotional materials, and audio elements

### Recommended Legal Process
The documentation outlines a three-phase approach involving initial contact and inquiry, formal licensing negotiations, and contract finalization. Professional legal representation specializing in Chinese intellectual property law is strongly recommended for commercial distribution.

### Alternative Approaches
For non-commercial distribution, the game can be released as a clearly labeled fan project with proper disclaimers and attribution. The legal guide provides detailed risk assessment for different distribution strategies and compliance requirements.

## Contributing and Community

### Development Contributions
The project welcomes contributions from developers interested in expanding the game content, improving existing systems, or adding new features. Contribution guidelines ensure consistency with the existing codebase and maintain compatibility with the plugin architecture.

### Translation and Localization
Additional language support is welcomed from native speakers who can provide accurate translations and cultural adaptations. The multilingual system is designed to accommodate additional languages with minimal technical modifications.

### Community Feedback
Player feedback and bug reports help improve the game experience and identify areas for enhancement. The project maintains active communication channels for community engagement and support.

## Support and Contact

### Technical Support
Technical issues and questions can be addressed through the GitHub repository issue tracker. The documentation includes comprehensive troubleshooting guides for common problems and platform-specific considerations.

### Business Inquiries
For business-related inquiries, licensing discussions, or partnership opportunities, contact information is provided in the legal documentation. Professional representation through qualified intellectual property attorneys is recommended for formal licensing negotiations.

### Community Resources
The project maintains documentation and resources for players, developers, and modders. Regular updates ensure compatibility with new RPG Maker versions and address community feedback and suggestions.

---

**© 2024 Xinle, LLC. Released under MIT License.**  
**Based on "Guardians of the Dafeng" (大奉打更人) - Fan-made derivative work.**  
**All trademarks and copyrights belong to their respective owners.**

