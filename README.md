# aw0x-id-integration

Disposable integration target for `aw0x.id`.

This repository exists solely so that `aw0x.id` v0.4 provider-binding and trusted
GitHub operation adapter work can be exercised against a real, throwaway repository.

- **It must contain no secrets.** No production secret values, no Actions secrets,
  no credentials of any kind.
- It contains no production code and carries no availability guarantee.
- Feature branches and pull requests here are expected to be created and discarded
  repeatedly by automated integration runs.
- The canonical source repository `aw0x1/aw0x.id` is never used as a live mutation target.
