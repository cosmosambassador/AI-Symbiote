# Copilot Instructions for AI-Symbiote

## Project Overview
AI-Symbiote is an emerging project focused on creating a symbiotic environment for AI-assisted coding. The goal is to integrate AI agents seamlessly into development workflows to boost productivity and code quality.

## Architecture
- **Modular Design**: The system is designed with modularity in mind, allowing for easy extension and integration of new AI capabilities.
- **Component Boundaries**: Core components include AI agent interfaces, code generation modules, and user interaction layers.
- **Data Flow**: AI inputs (prompts, code contexts) flow through processing pipelines to generate outputs (code suggestions, reviews).

## Development Workflows
- **Version Control**: Use Git with feature branches. Commit messages should follow conventional format (e.g., "feat: add new AI model integration").
- **Code Quality**: Run linters and formatters before commits. Use ESLint for JavaScript/TypeScript, Prettier for formatting.
- **Testing**: Implement unit tests for core logic, integration tests for AI interactions. Use Jest or similar frameworks.
- **Build Process**: Use npm/yarn for dependency management. Build commands: `npm run build` for production builds, `npm run dev` for development.

## Conventions and Patterns
- **Naming**: Use camelCase for variables/functions, PascalCase for classes/components.
- **File Structure**: Organize code by feature (e.g., `src/ai-agents/`, `src/ui/`).
- **Error Handling**: Use try-catch blocks for async operations, provide meaningful error messages.
- **AI Integration**: When integrating AI models, abstract API calls into service classes for easy swapping (e.g., OpenAI, Anthropic).

## Dependencies and Integrations
- **External APIs**: Potential integrations with AI providers like OpenAI API, GitHub API for code context.
- **Libraries**: Use popular, maintained libraries (e.g., Axios for HTTP requests, Lodash for utilities).
- **Cross-Component Communication**: Use event emitters or state management (e.g., Redux, Zustand) for component interactions.

## Key Files
- `README.md`: Project description and setup instructions.
- Future: `src/index.js`: Entry point.
- Future: `package.json`: Dependency and script definitions.

## Best Practices
- Always validate AI-generated code for security and correctness.
- Document AI prompts and responses for reproducibility.
- Prioritize user experience in UI components related to AI interactions.