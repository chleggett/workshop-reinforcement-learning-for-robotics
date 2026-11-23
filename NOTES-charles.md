# Charles's working notes

Started 2026-11-23 from Make: Vol. 99, "Reinforcement Learning for Robotics" (Shawn Hymel).
Article PDF: Google Drive, Personal/RL Robots.

## What this repo is

- Two paths, picked by robot kit: `docs/bala2-tutorial.md` (M5Stack Bala2 Fire, the one in the article) and `docs/bala-c-tutorial.md` (Bala-C Plus).
- Each tutorial has three parts: Training, Deployment, Going Further.
- The environment is a Docker image (`Dockerfile.cpu`): a webtop desktop with Python 3.12, PyTorch, MuJoCo (the physics simulator), Gymnasium, JupyterLab, TensorBoard and ONNX.
- `workspace/mechanical`: the robot's CAD model; `workspace/software`: training notebooks and code.

## Plan

- [ ] Read the rest of the article (16 pages)
- [ ] Watch the playlist's first video
- [ ] Run the Docker image (on the Mac, or ask Claude about a cloud option)
- [ ] Training section of the Bala2 tutorial, in simulation
- [ ] Decide on the hardware kit (optional)
- [ ] Deployment (only with the kit)

## Log

- 2026-11-23: Forked, cloned in a Claude cloud session, notes started.
