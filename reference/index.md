# Package index

## All functions

- [`Action_qcthat()`](https://gilead-public.github.io/qcthat/reference/Action_qcthat.md)
  : Use a GitHub Action to manage qcthat
- [`AssignIssue()`](https://gilead-public.github.io/qcthat/reference/AssignIssue.md)
  : Assign a GitHub issue to one or more users
- [`AttachReleaseReports()`](https://gilead-public.github.io/qcthat/reference/AttachReleaseReports.md)
  : Attach QC reports to a GitHub release
- [`CommentAllReports()`](https://gilead-public.github.io/qcthat/reference/CommentAllReports.md)
  : Comment on a PR or issue with QC reports
- [`CommentIssue()`](https://gilead-public.github.io/qcthat/reference/CommentIssue.md)
  : Comment on a GitHub Issue
- [`CommentReport()`](https://gilead-public.github.io/qcthat/reference/CommentReport.md)
  : Comment on a PR or issue with a QC report
- [`CommentUAT()`](https://gilead-public.github.io/qcthat/reference/CommentUAT.md)
  **\[experimental\]** : Comment on a PR or issue with a UAT report
- [`CompileIssueTestMatrix()`](https://gilead-public.github.io/qcthat/reference/CompileIssueTestMatrix.md)
  : Create a nested tibble of issues and tests
- [`CompileTestResults()`](https://gilead-public.github.io/qcthat/reference/CompileTestResults.md)
  : Extract information from testthat results
- [`DefaultIgnoreLabels()`](https://gilead-public.github.io/qcthat/reference/DefaultIgnoreLabels.md)
  : Default labels to ignore
- [`DefaultIgnoreLabelsDF()`](https://gilead-public.github.io/qcthat/reference/DefaultIgnoreLabelsDF.md)
  : Default ignored labels as a tibble
- [`ExpectUserAccepts()`](https://gilead-public.github.io/qcthat/reference/ExpectUserAccepts.md)
  **\[experimental\]** : Does a user accept the feature?
- [`ExtractTestsFromFiles()`](https://gilead-public.github.io/qcthat/reference/ExtractTestsFromFiles.md)
  **\[experimental\]** : Extract test information from test files
- [`FetchPRIssueNumbers()`](https://gilead-public.github.io/qcthat/reference/FetchPRIssueNumbers.md)
  : Fetch all issues associated with a GitHub pull request
- [`FetchRefPRNumber()`](https://gilead-public.github.io/qcthat/reference/FetchRefPRNumber.md)
  : Fetch the pull request number for a branch or other git ref
- [`FetchRepoIssueClosers()`](https://gilead-public.github.io/qcthat/reference/FetchRepoIssueClosers.md)
  : Fetch repository issue closers
- [`FetchRepoIssues()`](https://gilead-public.github.io/qcthat/reference/FetchRepoIssues.md)
  : Fetch repository issues
- [`FetchRepoPRs()`](https://gilead-public.github.io/qcthat/reference/FetchRepoPRs.md)
  : Fetch repository pull requests
- [`GetGHOwner()`](https://gilead-public.github.io/qcthat/reference/GetGHOwner.md)
  : Find the owner of the target repository
- [`GetGHRepo()`](https://gilead-public.github.io/qcthat/reference/GetGHRepo.md)
  : Find the name of the target repository
- [`GetSessionInfo()`](https://gilead-public.github.io/qcthat/reference/GetSessionInfo.md)
  : Get session info from available reporting functions
- [`GuessIssueNumber()`](https://gilead-public.github.io/qcthat/reference/GuessIssueNumber.md)
  : Guess the relevant issue number from the GitHub event
- [`GuessMilestones()`](https://gilead-public.github.io/qcthat/reference/GuessMilestones.md)
  : Guess relevant milestone names from the GitHub event
- [`GuessPRNumber()`](https://gilead-public.github.io/qcthat/reference/GuessPRNumber.md)
  : Guess the most relevant pull request number
- [`GuessReleaseID()`](https://gilead-public.github.io/qcthat/reference/GuessReleaseID.md)
  : Guess the relevant release id from the GitHub event
- [`IsCheckingUAT()`](https://gilead-public.github.io/qcthat/reference/IsCheckingUAT.md)
  : Detect whether the user is specifically checking UAT issues
- [`LoadGHEventPayload()`](https://gilead-public.github.io/qcthat/reference/LoadGHEventPayload.md)
  : Load the GitHub event payload
- [`LoadUATIssues()`](https://gilead-public.github.io/qcthat/reference/LoadUATIssues.md)
  : Load UAT issues from disk
- [`MapIssueClosersToCommits()`](https://gilead-public.github.io/qcthat/reference/MapIssueClosersToCommits.md)
  : Add Commits list column to dfIssueClosers
- [`MapLongIssueCommits()`](https://gilead-public.github.io/qcthat/reference/MapLongIssueCommits.md)
  **\[experimental\]** : Map issues to commits in long format
- [`MapTestFilesToPotentialIssues()`](https://gilead-public.github.io/qcthat/reference/MapTestFilesToPotentialIssues.md)
  **\[experimental\]** : Map test files to potential issues
- [`PrepareTestIssueContext()`](https://gilead-public.github.io/qcthat/reference/PrepareTestIssueContext.md)
  **\[experimental\]** : Prepare test issue context for analysis
- [`QCCompletedIssues()`](https://gilead-public.github.io/qcthat/reference/QCCompletedIssues.md)
  : Generate a QC report of completed issues
- [`QCIssues()`](https://gilead-public.github.io/qcthat/reference/QCIssues.md)
  : Generate a QC report of specific issues
- [`QCMergeGH()`](https://gilead-public.github.io/qcthat/reference/QCMergeGH.md)
  : Generate a QC report of issues associated with a GitHub merge
- [`QCMergeLocal()`](https://gilead-public.github.io/qcthat/reference/QCMergeLocal.md)
  : Generate a QC report of issues probably related to changes between
  local git refs
- [`QCMilestones()`](https://gilead-public.github.io/qcthat/reference/QCMilestones.md)
  : Generate a QC report of a specific milestone or milestones
- [`QCPR()`](https://gilead-public.github.io/qcthat/reference/QCPR.md) :
  Generate a QC report of issues associated with a GitHub pull request
- [`QCPackage()`](https://gilead-public.github.io/qcthat/reference/QCPackage.md)
  : Generate a QC report for a package
- [`ReadJSONAsIssueTestMatrix()`](https://gilead-public.github.io/qcthat/reference/ReadJSONAsIssueTestMatrix.md)
  : Read a JSON file as an IssueTestMatrix
- [`SaveAsJSON()`](https://gilead-public.github.io/qcthat/reference/SaveAsJSON.md)
  : Save an object as JSON
- [`SaveUATIssues()`](https://gilead-public.github.io/qcthat/reference/SaveUATIssues.md)
  : Save UAT issues to disk
- [`SetupGHLabels()`](https://gilead-public.github.io/qcthat/reference/SetupGHLabels.md)
  : Setup qcthat labels in a GitHub repository
- [`Skill_TagTestsWithIssues()`](https://gilead-public.github.io/qcthat/reference/Skill_TagTestsWithIssues.md)
  **\[experimental\]** : Use an AI skill to tag tests with issues
- [`TriggerUAT()`](https://gilead-public.github.io/qcthat/reference/TriggerUAT.md)
  **\[experimental\]** : Trigger the UAT cycle for closed issues
- [`UpdateIssue()`](https://gilead-public.github.io/qcthat/reference/UpdateIssue.md)
  : Update a GitHub issue
- [`print(`*`<qcthat_Object>`*`)`](https://gilead-public.github.io/qcthat/reference/printing.md)
  [`format(`*`<qcthat_Object>`*`)`](https://gilead-public.github.io/qcthat/reference/printing.md)
  : Printing qcthat objects
- [`use_qcthat()`](https://gilead-public.github.io/qcthat/reference/use_qcthat.md)
  : Set up qcthat for a package
