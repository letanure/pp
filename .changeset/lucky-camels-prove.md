---
"pp": major
---

Default build system

## WHAT

The build system has been updated to use Vite for both development and production builds. This change affects how the project is built and served.

## WHY

The change was made to leverage Vite's faster and leaner development experience, which includes faster hot module replacement (HMR) and optimized production builds.

## HOW

1. **Install the new dependencies**:

   ```sh
   npm install
   ```

2. **Update your build scripts**:

   Ensure your build scripts in `package.json` are updated to use Vite.

3. **Update your development workflow**:

   Follow the updated steps in the `README.md` to start the development server, build the project, and run tests.

4. **Check for any additional changes**:

   Review the `README.md` for any additional changes or steps required for the new build system.
