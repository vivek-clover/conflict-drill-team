# conflict-drill-team

**Date:** June 26, 2026
**Participants:** Member A (Driver 1), Member B (Driver 2), Member C (Observer)
 
### 1. Cause of Conflict
Both Member A and Member B modified line 2 of `utils.py` simultaneously. Member A merged their changes into the main branch first, causing a conflict when Member B attempted to pull the updated main branch.
 
### 2. Commands Used
- `git checkout -b <branch>` (Branch creation)
- `git pull origin main` (Triggered the conflict on Member B's branch)
- `git add` & `git commit` (To finalize the resolution)
- `git push origin <branch>` (To update the PR)
 
### 3. Resolution Process
We used the VS Code Merge Editor to inspect both incoming changes. Instead of choosing just one side, we manually combined the logic from both Member A and Member B to ensure no functionality was lost. After resolving the conflicts in the file, we staged, committed, and pushed the clean version.
