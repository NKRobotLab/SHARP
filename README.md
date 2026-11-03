# SHARP

**SHARP: Semantic-Aware Hierarchical Planning for Robotic Active Object Rearrangement from Limited Eye-in-Hand Observations**

[Project website](https://nkrobotlab.github.io/SHARP/)

SHARP combines lightweight visual perception, superquadric-modulated dynamic movement primitives, and a dependency-rich scene graph to coordinate target grasping, obstacle avoidance, and active rearrangement.

This repository contains the project website and demonstration assets. Paper and arXiv links will be added when available. The research implementation will be released after publication.

## Local preview

From the repository directory, run:

```bash
python -m http.server 8765 --bind 127.0.0.1
```

Then open http://127.0.0.1:8765/ in a browser.

The site uses the existing Bulma/Nerfies template and requires no build step. The page presents the method and experiments through figures, demonstration videos, and concise descriptions.
