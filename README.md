# tinycurl
Lightweight. Simple. `bash` &amp; `curl` in a container for debugging or scripting.

```
# TO TEST (easy): 
docker run -it quay.io/jimangel/tinycurl

# TO BUILD:
# docker build --no-cache -t tinycurl:latest .

# TO SCRIPT:
# docker run -it quay.io/jimangel/tinycurl:latest /usr/local/bin/bash -c "cd var/; ls; echo 'hello'; curl -L google.com; echo 'done'"

```
