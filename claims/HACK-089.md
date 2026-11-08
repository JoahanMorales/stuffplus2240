# HACK-089
ID: HACK-089
State: CLAIMED
Owner: sebas-1
Branch: feat/hack-089
Worktree: /Users/sebastian/Desktop/Hackathones/stuffplus2240-wt/hack-089
Worklog: worklog/WL-1794160848-sebas-1-HACK-089-hack.oeAEVR.md
Priority: P2
Paths: stuffplus/cards.py, stuffplus/cards_tex.py, reports/cards/, tests/test_cards_tex.py
Depends: None
Verify: `python -m pytest -q --tb=short -x tests/test_cards.py tests/test_cards_tex.py`
Lease-Until: 1794163548
Updated: 1794160848
Task-Base: 66e2f36921e3572e3bc6ea88ba0e9461d20457d4
Next: emit one `.tex` per card from the `build_card` dict, compile with Tectonic, keep matplotlib only for the chart.
PR: -
Evidence: -
