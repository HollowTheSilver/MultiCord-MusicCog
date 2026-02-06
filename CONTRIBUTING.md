# Contributing to Music Cog

Thank you for your interest in contributing to the MultiCord Music Cog!

## How to Contribute

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Test your changes with multiple templates
5. Commit your changes with a clear message
6. Push to your fork
7. Open a Pull Request

## Guidelines

- Cog must work with any MultiCord template
- Access bot config via `getattr(bot, 'config', {})`
- Update `cog.json` manifest for any new features
- Include docstrings for all commands
- Test with `multicord bot cog add <bot> music`

## Questions?

Open an issue if you have questions or suggestions.
