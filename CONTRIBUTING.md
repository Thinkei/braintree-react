# Deploy checklist

- `npm test`
- Update [CHANGELOG.md](CHANGELOG.md)
- Bump version in `package.json`
- `git add package.json`
- `git commit -m "Version 0.0.0"`
- `git tag -m "0.0.0" 0.0.0`
- `git push`
- `git push --tags`
- `npm publish`
