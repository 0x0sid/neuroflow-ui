# neuroflow-ui

Static front end for Neuroflow. No build step: `index.html` is self-contained (data embedded).

Deploy on Vercel: Import Git Repository -> Framework Preset "Other" -> leave build/output empty -> Deploy.

Regenerate `index.html` from the backend repo: `python scripts/build_dashboard.py`, then copy `ui/dashboard.html` here as `index.html`.
Data shown is synthetic (BrainFlow) and public (PhysioNet MMI, ODC-By); no participant data.
