# pr-custom-review-test
This is playground to test GitHub Action [pr-custom-review](https://github.com/paritytech/pr-custom-review)
Action has one hardcoded built in condition looking for changes in PR diff using RegExp:

`/🔒.*(\n^[\+|\-].*)|^[\+|\-].*🔒/gm`

The rest can be found and changed if needed in GHA config file `./.github/pr-custom-review-config.yml`

Feel free to make some changes and create PR's to test how GHA [pr-custom-review](https://github.com/paritytech/pr-custom-review) works.

