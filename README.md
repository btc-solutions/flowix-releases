# Flowix DB Tool

<!-- [![Version](https://img.shields.io/jetbrains/plugin/v/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID) -->
<!-- [![Downloads](https://img.shields.io/jetbrains/plugin/d/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID) -->

Plugin for mocking PostgreSQL queries in JetBrains IDEs. Intercepts SQL queries using configurable patterns and returns predefined responses without accessing the actual database.

Currently supports PostgreSQL. Other databases are planned for future support.

### Features:
- Mock PostgreSQL query responses based on patterns
- Configure predefined result sets for SQL queries
- Create different data scenarios for testing
- Track and record intercepted query history

### Use cases: 
- Development without environment setup
- Demo mode with predictable data
- Unit testing with database isolation

### Installation

- Using the IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "flowix"</kbd> >
  <kbd>Install</kbd>
  
- Using JetBrains Marketplace:

  Go to [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID) and install it by clicking the <kbd>Install to ...</kbd> button in case your IDE is running.

  You can also download the latest release from [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID/versions) or 
[GitHub](https://github.com/btc-solutions/flowix-releases/releases/latest/download/flowix-idea-plugin.zip)
   and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>
