
[Using GitHub CLI and Git in GitHub Codespaces](https://blog.jongallant.com/2021/06/codespaces-gh-cli-git-credentials/)

```
git config --global credential.https://github.com.helper ''
git config --global 'credential.https://github.com' '!gh auth git-credential'
```