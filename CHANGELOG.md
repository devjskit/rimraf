# 1.0

-   Allow ENOENT in sync method
-   Throw when no callback is provided
-   Make opts.gently an absolute path
-   use 'stat' if 'lstat' is not available
-   Consistent error naming, and rethrow non-ENOENT stat errors
-   add fiber implementation
