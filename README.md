# ISO/IEC 42001 Lead Auditor Complete Practice Suite

The suite contains 480 questions:

- `core.html`: 240 core questions from Sets 1 to 3
- `scenarios.html`: 12 case studies with 60 linked questions
- `expert.html`: 180 expert composite questions from Sets 5 to 7
- `index.html`: launcher for all three apps

## Update an existing GitHub Pages repository

1. Extract this ZIP.
2. Upload every extracted file to the root of your existing repository.
3. Replace the existing files when prompted.
4. Keep GitHub Pages configured for `main` and `/(root)`.
5. After deployment, perform one hard refresh to activate the new cache:
   - macOS: Command + Shift + R
   - Windows: Ctrl + Shift + R

Each app stores its own rotation and learning data locally in the browser.


## Navigation update

Every test bank now has a persistent **Banks** button in the top navigation. It returns to the suite selector from Safari, an installed iPhone web app, or a desktop browser. An active attempt is saved before switching banks and can be resumed later.


## Expert font update

The Expert Sets now use the same sans-serif typeface for the question scenarios and answer options. The persistent **Banks** navigation remains included.

After replacing the GitHub files, perform one hard refresh or reopen the installed iPhone app so the updated cache is loaded.


## iPhone navigation v4

Each test bank now includes two navigation paths:

- a **Banks** button in the top bar; and
- a fixed bottom navigation bar on iPhone-sized screens and installed Home Screen apps.

The bottom bar contains **Banks** and **Current bank home** and remains visible throughout a test.

The service worker now activates immediately and retrieves HTML pages from the network first, reducing the chance that an installed iPhone app continues to show an older cached interface.


## Mixed Master Bank v5

The suite now includes `mixed.html`, which draws from all 480 unique questions:

- 240 core questions
- 60 linked scenario questions
- 180 expert composite questions

Session-distribution options:

- **Proportional:** approximately 50% core, 12.5% scenario and 37.5% expert
- **Equal split:** approximately one-third from each bank
- **Expert-weighted:** approximately 30% core, 20% scenario and 50% expert

The mixed bank has separate smart no-repeat rotation for each source bank, adaptive revision, Study and Exam modes, bank and domain performance reporting, missed-question retakes, and persistent iPhone navigation.


## Long-Form Scenario Bank v6

The Scenario Bank now contains 12 original multi-paragraph cases, each followed by exactly five linked questions with three answer options.

The structure is modelled on the uploaded training sample while keeping the practice content original. The Mixed Master Bank has also been updated so its 60 scenario questions use the revised long-form context.
