# tsc-incremental-issue
Repro repo for [VsTsc build issue with incremental TypeScript build](https://github.com/microsoft/TypeScript/issues/41969)

1. Build the project
    1. There will be a tsc build error, which is valid
1. Build the project again
    1. It will build successfully, which is not valid. It should fail again
