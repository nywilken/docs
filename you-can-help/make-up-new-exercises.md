## Implementing a Completely New Exercise

A problem must have a unique slug. This slug is used as

* the directory name within each language-specific repository
* the directory name for the folder that contains the metadata files (in this repository)
* to identify the exercise in `config.json`

### In exercism/problem-specifications

* Create `exercises/<slug>/description.md` and `exercises/<slug>/metadata.yml`.
* Bonus: `exercises/<slug>/canonical-data.json` with inputs/outputs for the test suite.
* Submit a pull request.

### In exercism/x<TRACK_ID>

* Do the same as when [porting an exercise](/you-can-help/implement-an-exercise-from-specification.md).
  Reference the PR in problem-specifications if it hasn't been merged yet,
  this **must not** be merged until the exercism/problem-specifications PR is merged.
