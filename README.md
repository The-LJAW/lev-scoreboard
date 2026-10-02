# The LEV Scoreboard

Every compound the NIA Interventions Testing Program (ITP) has tested for mouse lifespan: what happened in each sex, the primary paper behind every number, and LEV Institute's separate grade of the human evidence.

**Live site:** https://the-ljaw.github.io/lev-scoreboard/

This repository holds the public build only (`index.html` plus `data/`). It is generated from the editorial master copy with `python3 tools/build.py --public`, which publishes only approved human-evidence grades. Don't edit these files by hand; edit the master `data/scoreboard.json`, rebuild, and replace them.

- `data/scoreboard.json`: the full public dataset (compounds, ITP test rows, sources, definitions)
- `data/compounds.csv`: one row per compound
- `data/cohorts.csv`: one row per ITP test

Not medical advice. LEV Institute is not affiliated with the National Institute on Aging or its Interventions Testing Program.
