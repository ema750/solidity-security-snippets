# Solidity Security Snippets

A collection of security-focused code snippets for Solidity development in VS Code.

## Features

This extension provides useful Solidity snippets focused on security best practices:

- **Reentrancy Guard** - Protection against reentrancy attacks
- **Checks-Effects-Interactions** - Pattern to prevent reentrancy
- **Pausable** - Contract pausing mechanism
- **Using assert for Invariants** - Runtime invariant checking
- **Safe Math** - Overflow/underflow protection (for Solidity <0.8)

## Snippets

| Trigger | Description |
|---------|-------------|
| `reentrancyGuard` | Reentrancy guard modifier |
| `checksEffectsInteractions` | Checks-Effects-Interactions pattern |
| `pausable` | Pausable contract pattern |
| `assertInvariant` | Invariant checking with assert |
| `safeMath` | SafeMath library for Solidity <0.8 |

## Usage

1. Install the extension
2. In a Solidity file, type the trigger prefix (e.g., `reentrancyGuard`)
3. Press Tab or Enter to expand the snippet

## Requirements

- VS Code version 1.60.0 or higher
- Solidity language support

## Extension Settings

This extension contributes no settings.

## Known Issues

None so far.

## Release Notes

### 1.0.0
Initial release of Solidity Security Snippets

-----------------------------------------------------------------------------------------------------------

**Enjoy!**