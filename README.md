# Personnal blog

This is the code of my personnal website. I'm using the library Hugo (JS).

# Push updates and pull them
locally 
```
hugo -D && git add . && git commit -m "update march 25" && git push origin main

```


on server 
```
ssh server
sudo su
cd /var/www/timotheeblog
git pull
```