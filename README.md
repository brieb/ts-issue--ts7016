```
$ rm -rf build && yarn tsc -b tsconfig.soln.json 
yarn run v1.22.4
$ .../node_modules/.bin/tsc -b tsconfig.soln.json
projects/proj-03/index.ts:1:20 - error TS7016: Could not find a declaration file for module ':proj-02/foo'. '.../ts-issue--TS7016/projects/proj-02/foo.js' implicitly has an 'any' type.

1 import proj02 from ":proj-02/foo";
                     ~~~~~~~~~~~~~~


Found 1 error.

error Command failed with exit code 2.
```
