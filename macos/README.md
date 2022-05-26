# macOS

## Accept Xcode's terms of service agreement to use `git`

```
sudo xcodebuild -license accept
```

## Delete all `.DS_Store` files

```
find . -name ".DS_Store" -delete
find . -name ".DS_Store" -print -delete
find . -name ".DS_Store" -type f -print -delete
```

