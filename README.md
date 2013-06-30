
# grunt-starter

### Starting a new grunt project

Now starting a grunt project from scratch is easy.

```shell
# clone the repo
git clone git@github.com:briangonzalez/grunt-starter.git   

# install all dependencies defined in package.json    
npm install         
````

### Pre Push Hook
This project comes preloaded with a git __pre-push__ hook which runs `grunt` prior to `git push`. This is useful to ensure your code is packaged before if makes it into the wild.