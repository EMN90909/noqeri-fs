# API reference

Filesystem operations are host-provided and deliberately thin. The library validates relative paths, rejects NUL/backslash/traversal, limits text writes to 8 MiB, and exposes the host status code without guessing OS-specific errors.

