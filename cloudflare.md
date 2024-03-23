# instructions to get this working on cloudflare
```
nvm install 18.17.1
nvm use 18.17.1
brew install yarn
yarn set version 3.6.3
yarn install 
# add missing dependencies
yarn install @emotion/cache @emotion/serialize @emotion/utils

git checkout -b cloudflare
git add yarn.lock
git commit -m "updating yarn.lock when using Cloudflare supported versions"
git push --set-upstream origin cloudflare
```