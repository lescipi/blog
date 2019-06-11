[blog](https://lescipi.github.io)

cd ../blog
git rm -r public
git submodule add -f -b master https://github.com/lescipi/lescipi.github.io.git public
hugo
cd public
git add .
git commit -m "Build website"
git push origin master
cd ..