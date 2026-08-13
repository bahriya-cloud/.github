# bahriya-cloud/.github

The GitHub **organisation profile** for [bahriya-cloud](https://github.com/bahriya-cloud).
GitHub renders `profile/README.md` from a public repository named `.github` as the
landing page of the organisation.

## Publishing

```bash
# one-time: create the public repo in the org
gh repo create bahriya-cloud/.github --public --description "Bahriya organisation profile"

git init && git add profile/ README.md
git commit -m "Organisation profile"
git branch -M main
git remote add origin git@github.com:bahriya-cloud/.github.git
git push -u origin main
```

The org page at <https://github.com/bahriya-cloud> updates as soon as the push lands.

## Updating

Edit `profile/README.md` and push. The logo is committed at `profile/bahriya-logo.svg`
(copied from `website/public/brand/bahriya.svg`) so the page never depends on the
website being reachable; if the brand asset changes, re-copy it here.
