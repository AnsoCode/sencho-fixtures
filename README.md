# Sencho test fixtures

This repo is used by automated UI stress tests for the Git Source feature. Branches:
- master: simple compose.yaml + .env at root
- nested: compose at apps/web/compose.yaml
- invalid-compose: intentionally broken yaml
- lfs-pointer: compose file that looks like a Git LFS pointer (tests the detector)
- submodule: includes .gitmodules
- deploy-fail: valid compose referencing a nonexistent image
