# Project instructions

This project uses Nauro to carry project judgment between agent sessions.

Before answering a technical design request, call `check_decision` with the approach you are considering. If it returns a related decision, read that decision in full with `get_decision` before answering.

Treat Nauro as read-only. Do not call `propose_decision`, `flag_question`, or `update_state`. Do not change files or project state.
