# infra

## GitHub workflow

* `main` merge/push triggers new version build.
* Infers version bump from commit message:
    * contains `#major` - 1.x.x
    * contains `#minor` or starts with `feat:` - x.1.x
    * else it is a patch - x.x.1
