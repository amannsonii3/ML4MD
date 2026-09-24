# ML4MD: random-noise warm-up for uncertainty calibration

Warm-up experiments on balanced Matbench `mp_is_metal` (metal vs non-metal)
classification for three models. Each folder is self-contained, with its own
`README.md`, `requirements.txt`, runners and plotting script.

| Folder | Model | Input | Python |
| --- | --- | --- | --- |
| [`crabnet/`](crabnet/) | CrabNet | composition | 3.10 |
| [`alignn/`](alignn/) | ALIGNN | crystal structure | 3.10 |
| [`orb/`](orb/) | ORB-v3 (from scratch) | crystal structure | 3.12 |

Each folder has `run_methods.py` (methods comparison at one warm-up dose),
`run_doses.py` (dose sweep) and `plot.py` (figures from saved CSVs). Run the
commands in each README from inside that folder, in a separate environment per
model.
