1. Get the Libraries: `$ ./wget-all`
2. Add them to your project: `$ cp -R public/ /my/rails/project/public/`
3. Done

### Updating Library Paths

Edit wget-all to include (or not include) the libraries you want to download.

### Why does this exist?

I found myself downloading the most up-to-date copies of the same libraries
multiple times. Instead of doing it this time, I wrote a script. 

Also, it downloads everything in parallel. Far out.


