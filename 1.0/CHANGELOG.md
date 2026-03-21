Kv Format 1.0 Specification CHANGELOG
=====================================

[1.0 RC4] - 2026-03-21
----------------------

### Changed

- Added footnote in Section 2.2 about valid keys
  (valid POSIX variable names with no reservations).


[1.0 RC3] - 2026-03-16
----------------------

### Changed

- Section 6.2 (MIME Types) completely rewritten, allowing both
  application/ and text/ MIME types


[1.0 RC2] - 2026-03-16
----------------------

### Changed

- Removed the "line number zero" requirement for shebang lines.

- Relaxed the implementation versioning scheme requirement
  (from MUST to SHOULD)

- Added rationale why this versioning scheme may be desired
  even with languages supporting feature gates (e.g., Rust)

- Added footnote with rationale on EOLs on final line

- Added an edge case clarifying error to raise in case a key consists
  of whitespace characters only
