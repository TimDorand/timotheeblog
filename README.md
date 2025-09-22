# Personnal blog

This is the code of my personnal website. I'm using the library Hugo (JS).

# Push updates and pull them
locally 
```
hugo -D && git add . && git commit -m "update sept 25" && git push origin main

```


on server 
```
ssh server
sudo su
cd /var/www/timotheeblog
git pull
```

## Troubleshooting
# Remove Hugo module cache
rm -rf ~/Library/Caches/hugo_cache/
# Remove existing theme
rm -rf themes/PaperMod

git clone https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
hugo mod get -u github.com/adityatelange/hugo-PaperMod
hugo mod tidy