# CodePond
This is how I quickly setup my github Codespaces environment from scratch.

First, run this in the console!
```bash
curl -fsSL https://deno.land/install.sh | sh
export PATH="/home/codespace/.deno/bin:$PATH"
deno install --allow-net --allow-read https://deno.land/std@0.106.0/http/file_server.ts
```

Then, run this in any folder to host a static web-server.
```bash
file_server
```
