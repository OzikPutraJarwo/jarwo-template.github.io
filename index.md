mkdir halaman-github
cd halaman-github
echo "Hello World! Welcome to my website" >> index.md
git init
git add index.md
git commit -m "first commit"
git remote add origin https://github.com/OzikPutraJarwo/jarwo-template.github.io.git
git push -u origin master
