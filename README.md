# static-precompress
Simple script to precompress static assets with gzip and brotli for faster delivery with nginx when using http_gzip_static and ngx_brotli modules.  
Requires that the `gzip(1)` and `brotli(1)` executables can be found in `$PATH`.

# Usage
`static-precompress directory`
Where `directory` is the name of a directory containing files for a webpage. Compressed files will be put alongside their original files.

# Known issues
No error handling whatsoever.

# LICENSE
2-Clause BSD
