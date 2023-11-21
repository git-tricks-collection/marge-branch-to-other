# marge-branch-to-other

Simple action to copy branch into the other

- Make sure to be in your _development_ branch:
`$ git checkout branch_with_development`

- Move you to _final_ files branch:
`$ git checkout branch_to_update`

- Rewrite _final_ with _development_ without lost versions:
`$ git merge branch_with_development`
