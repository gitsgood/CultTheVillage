# CommonLoadingScreen - Unreal Engine Plugin

This is the **CommonLoadingScreen** plugin extracted from Epic Games' **Lyra Sample Game**, providing a comprehensive loading screen management system for Unreal Engine games.

## About CommonLoadingScreen

CommonLoadingScreen is a sophisticated loading screen framework from Epic Games that handles the creation and display of loading screens during game transitions. It offers:

- **Loading Screen Management**: Centralized system for handling loading screen creation and display
- **Custom Widget Support**: Project-specified loading screen widget integration
- **Loading Process Tasks**: Framework for managing and tracking loading operations
- **Startup Loading Screen**: Pre-loading screen functionality for initial game startup
- **Process Interface**: Abstract interface for loading process management

## Original Source

This plugin originates from Epic Games' **Lyra Sample Game**:
- **Project Repository**: https://github.com/EpicGames/UnrealEngine/tree/ue5-main/Samples/Games/Lyra
- **Original Location**: `LyraStarterGame/Plugins/CommonLoadingScreen`
- **Author**: Epic Games
- **License**: Unreal Engine EULA

## Plugin Description

*Loading screen manager handling creation and display of a project-specified loading screen widget*

This plugin provides a complete solution for loading screen management, including:

- **LoadingScreenManager**: Central manager for loading screen lifecycle
- **LoadingProcessTask**: Base class for creating custom loading operations
- **LoadingProcessInterface**: Interface for implementing loading processes
- **CommonPreLoadScreen**: Startup loading screen implementation
- **SCommonPreLoadingScreenWidget**: Slate widget for pre-loading display

## Key Features

- **Flexible Architecture**: Support for custom loading screen widgets and processes
- **Task-Based Loading**: Structured approach to loading operations with progress tracking
- **Startup Integration**: Seamless integration with game startup sequence
- **Widget Customization**: Easy customization of loading screen appearance and behavior
- **Process Management**: Built-in support for complex loading workflows

## Dependencies

This plugin typically works with:
- **UMG**: Unreal Motion Graphics for UI creation
- **Slate**: Low-level UI framework
- **CommonUI**: Epic's UI framework (optional, for enhanced integration)
- **Engine Core**: Core Unreal Engine systems

## Usage

CommonLoadingScreen provides:

1. **Loading Screen Management**: Automatic handling of loading screen display during level transitions
2. **Custom Loading Widgets**: Support for project-specific loading screen designs
3. **Loading Process Framework**: Structured system for implementing complex loading operations
4. **Startup Loading**: Pre-loading screen functionality for game initialization

## Integration with Common Framework

This plugin is part of Epic's "Common" plugin ecosystem:
- **CommonUI**: Core UI framework
- **CommonInput**: Input handling system
- **CommonGame**: Gameplay classes and UI management
- **CommonUser**: User management and profiles

## Module Structure

- **CommonLoadingScreen**: Main loading screen management functionality
- **CommonStartupLoadingScreen**: Startup-specific loading screen implementation

## Credits

- **Epic Games**: Original creator of the CommonLoadingScreen plugin as part of Lyra Sample Game
- **Lyra Team**: Development team behind the Lyra Sample Game template
- **Unreal Engine Team**: Framework and engine support for loading screen systems