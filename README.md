# webblendus-redirect

Serves webblendus.com on GitHub Pages and sends every visitor to the same path on https://webblend.us.

- `index.html` and `404.html` do the redirect (every path lands on one of them).
- `CNAME` holds the custom domain.

DNS lives at Namecheap: four A records for `@` pointing at GitHub Pages and a CNAME for `www` pointing at `the-edward-exe.github.io`. The email records there are separate and untouched.
