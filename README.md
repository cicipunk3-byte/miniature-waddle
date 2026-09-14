# miniature-waddle

## Copy a local Git repository

If you want to copy a repository that already exists on your machine, use one of these:

- Full repo backup (includes all refs):

```bash
git clone --mirror /path/to/local/repo /path/to/backup/repo.git
```

- New working copy:

```bash
git clone /path/to/local/repo /path/to/new-working-copy
```