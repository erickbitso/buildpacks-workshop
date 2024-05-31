# wget-extension Buildpacks.io extension
This is a sample extension that installs wget.

Can only be used if environment variable BP_WGET is set

## Usage
Invoked as part of the my-builder builder, however can also be invoked explicitly:

```
pack build myapp --path app/ --builder localhost:5000/my-builder:latest --extension extensions/wget-extension --env BP_WGET="true"
```
