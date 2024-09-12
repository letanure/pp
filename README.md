# Project Name: pp

## Overview
This project is a basic setup using Vite for development and build processes, along with TypeScript for type checking and Biome for linting and formatting.

## Scripts
- **dev**: Starts the development server using Vite.
- **build**: Compiles TypeScript and builds the project using Vite.
- **preview**: Previews the built project using Vite.
- **lint**: Lints the project using Biome.
- **format**: Formats the code using Biome.

## Development Dependencies
- **@biomejs/biome**: A tool for linting and formatting.
- **typescript**: A language for application-scale JavaScript.
- **vite**: A build tool that aims to provide a faster and leaner development experience for modern web projects.
- **lefthook**: A tool for managing Git hooks.

## Getting Started
1. **Install dependencies**:
   ```sh
   npm install
   ```

2. **Install Lefthook**:
   ```sh
   npx lefthook install
   ```

3. **Start the development server**:
   ```sh
   npm run dev
   ```

4. **Build the project**:
   ```sh
   npm run build
   ```

5. **Preview the built project**:
   ```sh
   npm run preview
   ```

6. **Lint the project**:
   ```sh
   npm run lint
   ```

7. **Format the code**:
   ```sh
   npm run format
   ```

## Git Hooks
This project uses Lefthook to manage Git hooks.

### Pre-commit Hook
Runs Biome to check and fix issues in staged files before committing.

## License
This project is licensed under the MIT License.
