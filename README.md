# ImproveAnyTask

Official project page for **ImproveAnyTask: An Autonomous Post-Training Harness for Iterative Model Self-Improvement**.

ImproveAnyTask is an autonomous post-training harness that iteratively diagnoses model errors, selects research-backed update directions, and executes task-specific model updates under a fixed compute budget.

## Project page

[https://improveanytask.github.io/](https://improveanytask.github.io/)

## Results

Across 11 benchmarks, ImproveAnyTask achieves mean gains of 18.29 and 11.97 percentage points on Qwen3.5-4B-Base and Qwen3.5-4B-Instruct, respectively, with a maximum gain of 41.96 points.

## Citation

Citation metadata is provided in [`CITATION.cff`](CITATION.cff). The arXiv entry will be linked after public release.

ImproveAnyTask organizes task-specific adaptation into three stages:

1. **Error Attribution** identifies the highest-impact model weakness.
2. **Update Direction** compares research-backed improvement strategies.
3. **Executable Model Updates** translates the selected strategy into data and post-training.

Across 11 benchmarks, the harness achieves mean gains of 18.29 and 11.97 percentage points on Qwen3.5-4B-Base and Qwen3.5-4B-Instruct, respectively, under a 24-hour optimization budget.

## Project page

This repository is configured as a static GitHub Pages site. Open `index.html` locally to preview it.

## Links

- Project page: <https://improveanytask.github.io/>
- Paper: arXiv link pending
