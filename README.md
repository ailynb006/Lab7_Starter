1) I would fit my automated tests within a Github action that runs whenever code is pushed. This option is since it make sure that bugs are caught immediately and that tests aren't forgotten, keeping broken code out of the repo.
2) No since E2E tests are meant to simulate a user's actions, not check for logic or correctness.
3) 





