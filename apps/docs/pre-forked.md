# Pre-Forked

Here's a list of files that are required in automating builds. Copy them to repository clone folder and push those changes.

I only did a minor changes to the original files and prepared them.

**Note: This is only for those who haven't or can't fork my repository. Strictly recommend backing up your repository before proceeding.**

| Path (Relative from clone root) | Reason |
|---------------------------------|--------|
| [`.github/workflows/update.yml`](/.github/workflows/update.yml) | Required in automation |
| [`.github/workflows/apps.yml`](/.github/workflows/apps.yml) | Required in automation |
| [`.github/workflows/build-apk.yml`](/.github/workflows/build-apk.yml) | Required in automation |
| [`apps/*`](/apps/) | Required in automation |
| [`latest-parsed-version.md`](/latest-parsed-version.md) | Required in automation |
| [`README.md`](/README.md) | Hyperlinks to files in `apps/` folder which provide information |
| [`apks/README.md`](/apks/README.md) | Hyperlinks to files in `apps/` folder which provide information |