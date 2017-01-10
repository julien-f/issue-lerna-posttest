`lerna run test` does not execute `pretest`/`posttest` if `test` script does not exist.

Both npm and yarn do.

```
> yarn
> lerna run test
> lerna exec -- npm test
```
