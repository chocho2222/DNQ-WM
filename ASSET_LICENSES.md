# Asset licence register

| Asset | Location | Terms |
|---|---|---|
| Original DNQ-WM software | `code/dlc/`, evaluation and training scripts | MIT |
| Modified simulator software | `code/gym_multi_car_racing/` | Upstream MIT with original notices retained; author modifications under MIT |
| Frozen experiment configurations | `configs/tits_dynamic_graph_experiments.json`, `configs/tits_dnq_attribution_ablation_20260710.json`, `reproduce/` | CC BY 4.0 |
| Author-created figures | `figures/` | CC BY 4.0 |
| DNQ-WM checkpoints | `checkpoints/dnq_wm/` | CC BY 4.0 |
| DLC baseline checkpoints | `checkpoints/dlc_baselines/` | CC BY 4.0 |
| RL baseline checkpoints | `checkpoints/rl_baselines_strict_20260926/` | CC BY 4.0 |

## Boundary

The repository ships the code and the checkpoints that the documented
reproduction commands load, together with the two configurations those commands
read. It does not contain the per-case evaluation tables, the recorded
trajectories, the training-draw checkpoints behind the bracketed ranges of the
results table, the
simulation videos, or any track geometry file, and it contains no Assetto Corsa
executables, car or track models, textures, `.kn5` files or extracted
game-resource archives. The packaged RL checkpoint metadata records procedural
training tracks.

## Licence interpretation

- The MIT licence applies to project-authored software and retained upstream MIT
  code.
- CC BY 4.0 applies only to the author-owned assets listed above.
- Each Python dependency remains under its own licence.
- Third-party trademarks, proprietary game assets and external track data are
  excluded from both project licences.
