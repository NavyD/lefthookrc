## v0.4.0 (2025-10-15)

### Feat

- Add commitizen pre-push job
- Add stylua format job
- flatten format jobs
- Remove old config and add yamllint in mise

### Fix

- npm-install job not working on windows
- Use relaxed config for yamllint
- Disable color in lefthook

### Refactor

- combine multiple files

## v0.3.0 (2025-10-13)

### Feat

- Add npm install hook on checkout

## v0.2.0 (2025-10-09)

### Refactor

- Add fix,format,check jobs

## v0.1.0 (2025-10-07)

### Feat

- Change job order: format,lint
- Add format and py,sh lints and remove max_line_length limits
- Add git repo jobs

### Fix

- Missing target module, package, files, or command for mypy
- not working
- Use command `gitleaks git` instead of `gitleaks dir xxx1 xxx2` to avoid scanning the entire repo
- `:` contained in the drive letter in the path will not be ignored on Windows
