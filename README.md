# deletium

## How to contribute

This is a collaborative educational project. Show some respect to
previous additions before updating with your contribution.

First, [create a github account](https://github.com/join) and ask to
be added as a collaborator.

```
git clone git@github.com:deletium/deletium.git
cd deletium
git reset HEAD~1
git checkout .
rm docs/*
cp theFileYouWantToServe.html docs/index.html
git add docs/index.html
git commit -m"some note about your change"
git push -f origin master
```

## How to view
Go to [https://deletium.com](https://deletium.com)
