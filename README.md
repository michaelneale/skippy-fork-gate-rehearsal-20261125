# Disposable fork approval rehearsal

Synthetic C compile/test on a disposable GitHub-hosted runner, then protected
workflow-run admission and maintainer environment approval for forks.
Same-repository branches bypass the approval stage. The final stage prints a
marker only: no lab runners, production secrets, product code or deployments.

This experiment uses the first_time_contributors_new_to_github policy so
established external accounts can start basics automatically. GitHub may still
require its initial approval for new accounts. Native approval remains separate.
