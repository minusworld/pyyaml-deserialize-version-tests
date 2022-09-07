To run the tests:

```
> pipenv install --dev
> pipenv shell
> tox > output.txt
```

This will yield raw Tox output. You'll need to look through the results to see which version+API failed on which test.