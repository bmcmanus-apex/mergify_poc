# Mergify PoC

Public repo for PoC work with respect to merge_queues and Mergify

### Configuration

The Mergify configuration is defined in the `.github/mergify.yml`

### Queues

There are two merge queues defined; a hotfix queue and the default queue.
Queues are executed in order and having a hotfix queue enables high
priority PRs to easily get scheduled before other PRs.
