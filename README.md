# trunk-based-template

A trunk based flow template for Github Actions

To Deploy in dev

```bash
git tag -f dev
git push --tags -f
```

To deploy in QA, merge a PR to main

To deploy in prod, tag vX.Y.Z on main
