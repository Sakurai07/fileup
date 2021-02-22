# fileup
upload files from the terminal

# how to?

# Upload
```
curl --upload-file ./file.txt https://fileup.he1ios.repl.co
**or**
curl --upload-file file.txt https://fileup.he1ios.repl.co
```

# Encrypt
```
cat /tmp/hello.txt|gpg -ac -o-|curl -X PUT --upload-file "-" https://fileup.he1ios.repl.co/test.txt
```

# Download and decrypt
```
curl https://fileup.he1ios.repl.co/1lDau/test.txt|gpg -o- > /tmp/hello.txt
```

# uploading to virustotal
```
curl -X PUT --upload-file nhgbhhj https://fileup.he1ios.repl.co/test.txt/virustotal
```

# Deleting
```
curl -X DELETE <X-Url-Delete Response Header URL given when uploaded>
```
# Installation?
You just need curl nothing else

# Credits:
Transfer.sh - older version
properly appointed in credits as the website layout is theirs
