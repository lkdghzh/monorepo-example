# monorepo-example
lerna demo

## lerna init
```

lerna init

```
## lerna create subpkg
```
lerna create clone
lerna create commit
lerna create push
```
## lerna run test
```
lerna run test
➜  monorepo-example git:(master) ✗ lerna run test
lerna notice cli v4.0.0
lerna info Executing command in 3 packages: "npm run test"
lerna info run Ran npm script 'test' in 'clone' in 0.3s:
run tests from clone
lerna info run Ran npm script 'test' in 'commit' in 0.3s:
run tests from commit
lerna info run Ran npm script 'test' in 'push' in 0.3s:
run tests from push
lerna success run Ran npm script 'test' in 3 packages in 0.4s:
lerna success - clone
lerna success - commit
```