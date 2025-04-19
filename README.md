# GProxy

GProxy is a proxy server/client application designed for Warcraft 3, providing enhanced connectivity and game hosting capabilities. The application features a modern GUI interface and various utilities for managing game connections and bot configurations.

## Features

- Modern GUI interface with multiple windows for different functionalities
- Game hosting capabilities
- Bot configuration and management
- Battle.net protocol support
- User authentication and login system
- Game list management
- Customizable settings and configurations

## Project Structure

```
├── GProxy/                 # Main application directory
│   ├── source/            # Main source code directory
│   │   ├── bnet/         # Battle.net related functionality
│   │   ├── data/         # Data files
│   │   ├── delegate/     # UI delegates
│   │   ├── gmp/          # Game management protocol
│   │   ├── images/       # Image resources
│   │   ├── mysql/        # Database functionality
│   │   ├── sounds/       # Sound resources
│   │   ├── thread/       # Thread management
│   │   ├── util/         # Utility functions
│   │   └── widget/       # Custom widgets
│   ├── icons/            # Application icons
│   ├── build/            # Build output directory
│   ├── debug/            # Debug build files
│   └── release/          # Release build files
└── BNCSUtil/             # Battle.net protocol utility library
    ├── source/           # Source code files
    ├── include/          # Header files
    └── build/            # Build output directory
```

## Building the Project

The project uses Qt framework and can be built using the provided `.pro` file. To build the project:

1. Make sure you have Qt installed on your system
2. Open the `GProxy.pro` file in Qt Creator
3. Build the project using the appropriate build configuration (Debug/Release)

## Dependencies

- Qt Framework
- MySQL (optional, for database functionality)
- BNCSUtil (for Battle.net protocol support)

## Configuration

The application can be configured through the Config GUI interface, which allows you to:
- Set up connection parameters
- Configure bot settings
- Manage game hosting options
- Customize user interface preferences

## License

This project is licensed under the terms specified in the project files.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

For support and issues, please refer to the project's issue tracker or contact the maintainers. 
