# GitHub Actions Snippets

This Neovim plugin provides useful snippets for creating GitHub Actions workflows.

## Installation

### Using `packer.nvim`

Add the following to your `init.lua` or `init.vim`:

```lua
use 'yourusername/nvim-gh-actions-snippets'
```

### Using `lazy.nvim`

Add the following to your `init.lua` or `init.vim`:

```lua
{
  'sunnybharne/nvim-gh-actions-snippets',
  lazy = true,
}
```

## Usage

After installing the plugin, you can use the provided snippets in your Neovim editor. The snippets are available for the following files:

### Snippets

#### `basic_workflow.lua`

This file contains snippets for creating basic GitHub Actions workflows. It includes templates for defining jobs, steps, and actions within a workflow.

#### `on_trigger.lua`

This file contains snippets for defining triggers in GitHub Actions workflows. It includes templates for common triggers such as `push`, `pull_request`, and `schedule`.

#### `utils.lua`

This file contains utility snippets for GitHub Actions workflows. It includes templates for common actions and reusable steps.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License.

