BRIEFLY — REDESIGNED OFFLINE WEBSITE

Quick start
Extract the ZIP and open briefly-improved.html in a current browser.
No installation, credentials, backend, internet access, or API keys required.
Your original index.html has not been modified.

Brand retained
Briefly name, Powered by Shreyy attribution, navy/blue/purple palette,
and original embedded Kaushan Script / Acme fonts. Body uses local system
fonts instead of the original network-dependent Roboto font request.

Architecture
Single distributable HTML; separated editable source files included.
A local Web Worker performs deterministic analysis. No backend is used:
this is intentional for an offline, credential-free deployment.
Run python briefly-source/build.py after source edits to rebuild the HTML.

Rubric improvements
Innovation: explainable source-linked priority signals and session task tracking.
Code quality: modular analysis/rendering/import/export, validation and tests.
UI/UX: responsive workspace, empty states, keyboard tabs and focus management.
Architecture: isolated worker, bounded imports, paginated message rendering.
Security: strict hashed CSP, network disabled, textContent rendering, no storage.

Limits
Rule-based extractive analysis is not an LLM. Task/decision extraction can miss
items or produce false positives. Relative dates stay as written. Owner
extraction supports explicit @mentions and first-person commitments only.
Replies do not automatically imply task completion.
No rubric score, formal accessibility certification, or cross-browser security
audit is claimed. Backend rubric criteria requiring an actual server cannot
be fulfilled by an intentionally self-contained offline site.

Verification
13 checks passed in local Chromium, including 390px and desktop rendering,
imports, exports, tasks, search, reset, and injection safety. See verification.json.
