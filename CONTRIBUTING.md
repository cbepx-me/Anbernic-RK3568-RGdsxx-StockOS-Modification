# Contributing

Thanks for your interest in improving **Anbernic H700 RG-xx StockOS Modification**!

## How to Contribute

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request.

## Guidelines

- Keep code compatible with Python 3.8+ and the device environment.
- Do not include large binary files in the main repo; use Releases for upgrade packages.
- Test on real hardware if possible, or clearly state the test environment.
- Follow the existing code style and logging conventions.
- For UI changes, provide screenshots if possible.

## Reporting Issues

Use the GitHub Issue templates. Include:
- Device model and board ID
- Stock OS version / build date
- Steps to reproduce
- Log file (`update.log`, `launcher.log`, `software_center.log`)

## Pull Request Checklist

- [ ] Code builds / runs on target device.
- [ ] No unnecessary files added.
- [ ] README or docs updated if needed.
- [ ] Tested with at least one supported device.

## Code of Conduct

By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).
