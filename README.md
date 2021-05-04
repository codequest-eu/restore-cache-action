# Restore Cache Action

Github Action which only restores paths from a cache and will fail on cache misses.

Useful when you have a job that primes the cache and then other jobs that just need to use it.

Based on [actions/cache](https://github.com/actions/cache).

## Usage

### Inputs

- `path` - A list of files, directories, and wildcard patterns to cache and restore. See [`@actions/glob`](https://github.com/actions/toolkit/tree/main/packages/glob) for supported patterns.
- `key` - Key for restoring the cache
