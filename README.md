# Mergify PoC

Public repo for PoC work with respect to merge_queues and Mergify

### Configuration

The Mergify configuration is defined in the `.github/mergify.yml`

### Queues

There are two merge queues defined; a hotfix queue and the default queue. Queues
are executed in order and having a hotfix queue enables high priority PRs to
easily get scheduled before other PRs.

### Scope

- merge queues
- policy enforcement
- bulldozer
- What do GitHub interactions look like
- What happens with the merge button

#### Merge Queue

- Merge Conflict
- speculative checks
  - failing PR front of queue
  - failing PR last in queue
  - requeue
  - removing a PR from a queue
  - can you jump queue
    - Hotfix
