# Introduction

Hi,

It's personal website for Pratama Bayu Widagdo.

# Requirements

1. Node
    ```
    npm install -g firebase-cli
    ```
2. Jekyll
3. Firebase
    ```
    cd yourproject/
    firebase init
    ```

# Setup
```
# login to get token for use in CI server
firebase login:ci
```

# Development
```
bundle exec jekyll serve
```

# Deployment

```
bundle exec jekyll build --verbose

firebase deploy --only hosting

# for deploy using token
#firebase deploy --only hosting --token $FIREBASE_TOKEN
```