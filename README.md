# development-policy
saturn-engine team's development policy &amp; rules

## git branch strategy
1. Do not use force push.
2. Each branch is divided as follows:
  1. main branch
    * This is the branch where released versions are stored.
  3. develop branch
    * This is the branch where development-in-progress is stored.
    * Development is carried out by creating new branches from this branch.
  4. feature branch
    * This is a branch for new feature development.
    * Please name it like feature/{feature_name}.
  6. fix branch
    * This is a branch for bug fixes.
    * Please name it like fix/{fix_description}.
3. When developing, please create a corresponding branch from the develop branch and develop on the created branch.
4. Please create a pull request for what you have developed and merge it into the develop branch.
5. Pull requests require approval from at least one development team member.
