# version

<!-- https://github.com/drone/drone-cache-lib -->

```bash
git remote add upstream git@github.com:drone/drone-cache-lib.git

git fetch upstream

git merge master
```

## master

```bash
# 新建一个Tag
git tag v1.0.1

# 推送一个Tag ，-f 强制更新
git push -f origin v1.0.1

# 删除本地Tag
git tag -d v1.0.1
```

## dev

```bash
# 新建一个Tag
git tag v1.0.1-beagle.1

# 推送一个Tag ，-f 强制更新
git push -f origin v1.0.1-beagle.1

# 删除本地Tag
git tag -d v1.0.1-beagle.1
```

## debug

```bash
go vet ./...
```
