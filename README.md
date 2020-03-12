### Steps to publish a package

#### 1. Create a "upm" branch:

```
git subtree split --prefix=Assets/UnityUpmTest --branch upm
```

#### 2. Create a new tag:

```
git tag 1.0.0 upm
```

####3. Push to remote:

```
git push origin upm --tags
```
