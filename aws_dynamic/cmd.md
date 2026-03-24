strip perms:
```
icacls "tempewdakey.pem" /inheritance:r
```

add new perms:
```
icacls "tempewdakey.pem" /grant:r "%username%":"(R)"
```

github commands
```
# 1. Pull the dynamic code down
git clone https://github.com/heroku/node-js-getting-started.git

# 2. Go into the new folder
cd node-js-getting-started

# 3. Install the Express and EJS dependencies
npm install

# 4. Spin up the server
npm start
```
