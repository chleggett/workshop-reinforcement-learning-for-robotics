# Charles's working notes

Started 2026-11-23 from Make: Vol. 99, "Reinforcement Learning for Robotics" (Shawn Hymel).
Article PDF: Google Drive, Personal/RL Robots.

## What this repo is

- Two paths, picked by robot kit: `docs/bala2-tutorial.md` (M5Stack Bala2 Fire, the one in the article) and `docs/bala-c-tutorial.md` (Bala-C Plus).
- Each tutorial has three parts: Training, Deployment, Going Further.
- The environment is a Docker image (`Dockerfile.cpu`): a webtop desktop with Python 3.12, PyTorch, MuJoCo (the physics simulator), Gymnasium, JupyterLab, TensorBoard and ONNX.
- `workspace/mechanical`: the robot's CAD model; `workspace/software`: training notebooks and code.

## Plan

The checklist lives in the Project Report (tick items there):
https://claude.ai/artifact/CHiKzZPf4KpFJDARqpttea

Training runs in Google Colab: open `workspace/software/python/rl_train_bala2.ipynb`.
Three phases: balance only; domain randomization; randomization for the physical world.

## Log

- 2026-11-23: Forked, cloned in a Claude cloud session, notes started.
- 2026-11-23: Read the article; checklist moved to the Project Report.
