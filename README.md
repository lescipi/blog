[Link to blog](https://lescipi.github.io)

## Deployment on Github
* cd ../blog
* git rm -r public
* git submodule add -f -b master https://github.com/lescipi/lescipi.github.io.git public
* hugo
* cd public
* git add .
* git commit -m "Build website"
* git push origin master
* cd ..


## Local development setup (Windows)
-   Download scoop in powershell `iwr -useb get.scoop.sh | iex`
-   Download hugo `scoop install hugo-extended`