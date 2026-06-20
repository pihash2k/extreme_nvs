# Results with Auxiliary View

Each subfolder is one example shown in the carousel. Add new examples by creating a new numbered folder.

## Expected files per folder

```
results_auxiliary/
  example1/
    input.png       — the reference/input image
    auxiliary.png   — the auxiliary image (different instance, same category)
    output.mp4      — the novel view synthesis output video
  example2/
    ...
```

## Adding a new example

1. Create a new folder: `results_auxiliary/example3/`
2. Add `input.png`, `auxiliary.png`, `output.mp4`
3. In `index.html`, find `AUX_RESULTS_EXAMPLES` and append:
   ```js
   { folder: 'results_auxiliary/example3' },
   ```
