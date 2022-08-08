
# add this in the scripts of package.json
```
 "copy:assets": "copyfiles -u 1 ./src/assets/**/* public",
 "watch:assets": "onchange \"/src/assets/**/*\" -- npm run copy:assets",
```

# also change this
```
  'src/*.html'
```
# to this 
```
  \"src/*.html\"
```
- finally pay attention to the link of the css
