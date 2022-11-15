# To compile
```
npm i
npm run build
```

All stylesheets are tied together at index.css and all jade templates are tied together similiarly at index.jade.  

# To save and deploy after changes
```
git checkout master
npm run git
```
This will commit and push all changed files with an automated message, cd up 1 dir and run `npm run update`. 

Assumed this was cloned within the parent github pages repo using the `--recursive` flag. 
