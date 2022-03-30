# action-create-release-txt
Creates release.txt with git ref in /public directory

Example:
```
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: speareducation/action-save-test-results
        with:
          target: ./public/release.txt
```

