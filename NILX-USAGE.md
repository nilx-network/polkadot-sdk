# How to sync with upstream polkadot-sdk

## Track new branch

```bash
git pull upstream master
git push origin master

git fetch upstream <release-polkadot-vx.x.x>
git checkout -b <release-polkadot-vx.x.x> upstream/<release-polkadot-vx.x.x>
git checkout -b <nilx-vx.x.x> <release-polkadot-vx.x.x>
```

## Cherry pick
