# Reproducible bug 

## [gatsby-plugin-remove-trailing-slashes] doesn't seem to actually remove trailing slashes 

Install this starter (assuming Gatsby is installed) by running from your CLI:
```
gatsby new bug-trailing-slashes https://github.com/skube/bug-gatsby-trailing-slashes
```
Then:
```
cd bug-trailing-slashes
gatsby develop
```

Navigate to `http://localhost:8000/two/`

**Expected results**
Gatsby would automatically resolve to `http://localhost:8000/two`

**Acutal results**
Stays same as `http://localhost:8000/two/`