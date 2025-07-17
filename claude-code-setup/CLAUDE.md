# Default rules

## Build and test commands
```
npm run:build                   # Build ESM and CJS versions
npm run:lint                    # Run ESLint
npm test                        # Run all tests
npm run test:watch              # Run tests in watch mode
npx jest path/to/file.test.ts   # Run specific test file
npx jest -t "test name"         # Run tests matching pattern
```

## Code Style Guidelines
- **TypeScript**: Strict mode enabled, explicit return types for functions
- **Naming**: PascalCase for classes/types, camelCase for functions/variables
- **Files**: kebab-case for files, test files with `.test.ts` suffix
- **Imports**: ES modules with `.js` extension, group by: external, internal, relative
- **Error Handling**: Prefer explicit error types, avoid any
- **Formatting**: 2-space indentation, semicolons required, single quotes
- **Testing**: Co-locate tests with source files, use descriptive test names
- **Comments**: JSDoc for public APIs, inline comments for complex logic

## Project Structure
```
  /src              # Source code
    /components     # Reusable components
    /utils          # Utility functions
    /types          # TypeScript type definitions
  /tests            # Integration tests
  /dist             # Build output
```

## Dependencies
- Node.js >= 18 LTS
- TypeScript for type checking
- ESLint for linting
- Jest for testing
- express.js for backend framework
- vue.js for frontend framework