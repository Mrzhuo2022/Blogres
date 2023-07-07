## Blogres

### Use with __[jsdelivr](https://github.com/jsdelivr/jsdelivr)__.
### Commonly Use
`https://fastly.jsdelivr.net/gh/Mrzhuo2022/Blogres@latest/images/pixelgirl.webp`




______________
__Load any GitHub release, commit, or branch:__
`/gh/user/repo@version/file`
__Load exact version:__
```
/gh/jquery/jquery@3.1.0/dist/jquery.min.js
/gh/jquery/jquery@32b00373b3f42e5cdcb709df53f3b08b7184a944/dist/jquery.min.js
```
__Use a version range instead of an exact version (only works with valid semver versions):__
```
/gh/jquery/jquery@3/dist/jquery.min.js
/gh/jquery/jquery@3.1/dist/jquery.min.js
```
> NOTE If you use this feature and a file you requested is not available in the newest release, the link will keep working thanks to our version-fallback feature. We'll continue to serve the file from older release instead of failing with a 404 error.

__Omit the version completely or use "latest" to load the latest one (only works with valid semver versions): (Dev environment only)__
```
/gh/jquery/jquery@latest/dist/jquery.min.js
/gh/jquery/jquery/dist/jquery.min.js
```
> NOTE Requesting the latest version (as opposed to "latest major" or "latest minor") is dangerous because major versions usually come with breaking changes. Only do this if you really know what you are doing.

__Add ".min" to any JS/CSS/SVG file to get a minified version - if one doesn't exist, we'll generate it for you. All generated files come with source maps and can be easily used during development:__
`/gh/jquery/jquery@3.2.1/src/core.min.js`
> NOTE Minifying a large file can take several seconds. However, we store all generated files in our permanent storage, so this delay only applies to the first few requests.

__Get a directory listing:__
```
/gh/jquery/jquery@3.1.0/
/gh/jquery/jquery@3.1.0/dist/
```
