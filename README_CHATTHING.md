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

Often you will need to fix conflicts in the configs.

Verify everything is still working by running:

```
docker-compose up
```

and test the API