# gh-pages

## Deploy

```bash
# commit changes in twitchmultivod-master
yarn build
cd ../twitchmultivod-gh-pages
cp -r ../twitchmultivod-master/build/ .
git add .
git commit -m "[HELPFUL MESSAGE HERE]"
```
