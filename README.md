# tinycurl
Lightweight. Simple. `bash` &amp; `curl` in a container for debugging or scripting.

```
# TO TEST (easy): 
docker run -it --rm quay.io/jimangel/tinycurl

# TO BUILD:
# docker build --no-cache -t tinycurl:latest .

# TO SCRIPT:
# docker run -it --rm quay.io/jimangel/tinycurl:latest /bin/sh -c "cd var/; ls; echo 'hello'; curl -L google.com; echo 'done'"

```
