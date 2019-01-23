# Atom Configuration

## Save Configuration
1. Backup your packages. Open powershell and navigate to the `~/.atom/` folder.
From there, run `apm list --installed --bare > ~/.atom/package.list`.
2. Commit changes.

## Restore Configuration
1. Clone / pull the repo inside your `~/.atom/` folder. You will need to overwrite existing files somehow if they already exist. Your configuration is now restored.
2. Restore your packages. Open powershell and navigate to the `~/.atom/` folder.
From there, run `apm install --packages-file ~/.atom/package.list`.
