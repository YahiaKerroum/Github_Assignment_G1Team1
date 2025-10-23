# Github_Assignment_G1Team1

# Website Link : https://yahiakerroum.github.io/Github_Assignment_G1Team1/

# Team Members and Their Emails:

Mohammed Yassine Henni - mohammed.yassine.henni@ensia.edu.dz

Meriem Ghedabnia - meriem.ghedabnia@ensia.edu.dz

Yahia Kerroum - yahia.kerroum@ensia.edu.dz

Nada Kechoud - nada.kechoud@ensia.edu.dz

Douniazed Blaada - douniazed.blaada@ensia.edu.dz

Rayane Toumi - rayane.toumi@ensia.edu.dz

# Team Retrospective Analysis

## Most Significant Technical Challenge: Branch Management and Merge Direction Conflicts

The biggest technical challenge we faced during our collaboration was merge direction errors and branch discipline issues. Several team members often tried to merge feature branches directly into the main branch instead of the develop branch. This disrupted our intended Git workflow and happened in five different pull requests, showing gaps in our understanding of branching strategies.

**Root Causes:**
- GitHub's default merge target is main
- Unfamiliarity with changing pull request destinations
- Team members creating PRs without switching the target branch from main to develop

**Impact:**
- Approved but incorrectly targeted merges needed immediate reversal
- Cycle of creating and reverting pull requests
- Wasted development time and confusion in the codebase

## Specific Merge Conflict Resolution: Reverting Main Branch Merges

A specific merge conflict happened when a developer merged their feature branch into main instead of develop. Our resolution followed this structured approach:

### Identification
- Detected the error during pull request reviews
- Noticed the target branch was set to main instead of develop

### Communication
- Notified the team immediately via chat
- Stopped further incorrect merges to prevent a cascade of issues

### Revert Process
- Used GitHub's revert feature
- Created a new commit that reversed changes while keeping a history
- Maintained a clean commit timeline

### Education
- Provided step-by-step guidance for creating correct PRs
- Showed how to manually select the develop branch in the GitHub interface
- Conducted team knowledge-sharing sessions

### Prevention
- Set up a review checklist that requires target branch verification
- Implemented a pre-approval step for confirming branch destinations
- Created documentation for future reference

## Pull Request and Peer Review Efficacy

### Initial Challenges
- The review process did not catch basic branch targeting errors
- Highlighted the need for more thorough reviews
- Revealed gaps in our workflow procedures

### Positive Outcomes
- Multiple approvals helped prevent ongoing incorrect merges
- Peer review ensured that at least two team members examined each contribution
- The collaborative process created a natural record of changes

### Lessons Learned
- **Expand Review Scope**: Focus on procedural compliance as well as code approval
- **Knowledge Distribution**: PRs helped spread understanding across the team
- **Quality Enhancement**: Despite initial workflow issues, we produced a stronger final product
- **Process Improvement**: Identified areas to optimize our workflow

### Future Improvements
- Implement automated rules for branch protection
- Enhance the review checklist with specific branch verification steps
- Conduct regular Git workflow refresher sessions
- Establish clearer contribution guidelines for team members
