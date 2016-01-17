# ascii-errorpages
Fancy command-line styled errorpages with errorcodes in ASCII art. The script used to create a cat-like typer is quite dirty, so don't expect something amazing.

# How to use
Clone the repository and configure your web server to use the custom error pages. Change `/path/to/files/` to the destination folder of the errorpages.

Here's an example in nginx:
```location /error/ {
    alias /path/to/files/;
}

error_page 400 /error/400.html;
error_page 401 /error/401.html;
error_page 403 /error/403.html;
error_page 404 /error/404.html;
error_page 405 /error/405.html;
error_page 406 /error/406.html;
error_page 407 /error/407.html;
error_page 408 /error/408.html;
error_page 409 /error/409.html;
error_page 410 /error/410.html;
error_page 411 /error/411.html;
error_page 412 /error/412.html;
error_page 413 /error/413.html;
error_page 414 /error/414.html;
error_page 415 /error/415.html;
error_page 416 /error/416.html;
error_page 417 /error/417.html;
error_page 419 /error/419.html;
error_page 421 /error/421.html;
error_page 422 /error/422.html;
error_page 423 /error/423.html;
error_page 424 /error/424.html;
error_page 426 /error/426.html;
error_page 428 /error/428.html;
error_page 429 /error/429.html;
error_page 431 /error/431.html;
error_page 500 /error/500.html;
error_page 501 /error/501.html;
error_page 502 /error/502.html;
error_page 503 /error/503.html;
error_page 504 /error/504.html;
error_page 505 /error/505.html;
error_page 506 /error/506.html;
error_page 507 /error/507.html;
error_page 508 /error/508.html;
error_page 510 /error/510.html;```
