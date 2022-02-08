# Use-cases

## **LakeFS**

### **LakeFS enhances processing workflows at each step of the data lifecycle**

- **In Development**
  - Experiment - try new tools, upgrade versions, and evaluate code changes in isolation. By creating a branch of the data you get an isolated snapshot to run experiments over, while others are not exposed. Compare between branches with different experiments or to the main branch of the repository to understand a change’s impact.
  - Debug - checkout specific commits in a repository’s commit history to materialize consistent, historical versions of your data. See the exact state of your data at the point-in-time of an error to understand its root cause.
  - Collaborate - avoid managing data access at the two extremes of either
    - 1) treating your data lake like a shared folder
    - 2) creating multiple copies of the data to safely collaborate. Instead, leverage isolated branches managed by metadata (not copies of files) to work in parallel.

- **During Deployment**
  - Version Control - retain commits for a configurable duration, so readers are able to query data from the latest commit or any other point in time. Writers atomically introduce new data preventing inconsistent data views.

- **Test**
  - define pre-merge and pre-commit hooks to run tests that enforce schema and validate properties of the data to catch issues before they reach production.

- **In Production**
  - Roll Back - recover from errors by instantly reverting data to a former, consistent snapshot of the data lake. Choose any commit in a repository’s commit history to revert in one atomic action.
  - Troubleshoot - investigate production errors by starting with a snapshot of the inputs to the failed process. Spend less time re-creating the state of datasets at the time of failure, and more time finding the solution.
  - Cross-collection Consistency - provide consumers multiple synchronized collections of data in one atomic, revertable action. Using branches, writers provide consistency guarantees across different logical collections - merging to the main branch only after all relevant datasets have been created or updated successfully.
