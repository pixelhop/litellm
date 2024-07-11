## Updating our fork

If you haven't already add the upstream repo as a remote

```
git remote add upstream git@github.com:BerriAI/litellm.git
```

```
git checkout staging
git fetch upstream
git merge upstream/main
```