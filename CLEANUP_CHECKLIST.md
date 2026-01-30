# Files to Remove from GitHub

## Build Artifacts (already in .gitignore)
- dist/
- build/
- *.egg-info/
- models/

## Development Files (keep local, not on GitHub)
- ml_data/
- notebooks/
- test/
- test_new_shield.py
- scripts/ (except 5 essential ones)

## Redundant/Outdated Documentation
- HOW_DATASET_GENERATION_WORKS.md (dev-only)
- ML_IMPLEMENTATION_SUMMARY.md (dev-only)
- QUICK_START_ML.md (dev-only)
- SECURITY_LEVELS.md (old API, outdated)
- ROADMAP.md (outdated)
- dataset_card.md (HuggingFace only)
- model_card.md (HuggingFace only)
- API_REFERENCE.md (outdated)
- BEST_PRACTICES.md (merge into README)

## Keep These
✅ README.md
✅ QUICKSTART.md
✅ LICENSE
✅ PHASE1_README.md
✅ PHASE3_README.md
✅ PUBLISHING.md
✅ pyproject.toml
✅ setup.py
✅ MANIFEST.in
✅ .gitignore
✅ .github/
✅ promptshield/ (source code)
✅ examples/ (user-facing examples)
