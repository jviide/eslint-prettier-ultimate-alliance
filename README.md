# eslint-prettier-ultimate-alliance

An example repository for using ESLint and Prettier together. Features:

 * ESLint with Prettier enabled: Prettier formatting errors are now ESLint warnings.

 * Support for both JavaScript and TypeScript files: The [.eslintrc.json](./.eslintrc.json) file has its own section for TypeScript overrides.

 * NPM script for running the linter: Just run `npm run lint`. Also a

 * [Workspace settings for VSCode](./.vscode/settings.json): Sets Prettier-enabled ESLint as the formatter for JS/TS files, and Prettier as the default formatter for all others (e.g. JSON). The related VSCode extensions are marked as [recommended extensions](./vscode/extensions.json) for this workspace.

   **Tip:** This can be quite effective combo if you enable the "format on save" feature for VSCode.

 * A [devcontainer setup](https://code.visualstudio.com/docs/remote/containers) 'cause that's how I roll, friend. You don't have to use this, though.
