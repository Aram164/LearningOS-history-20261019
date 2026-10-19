## 2025-02-23 - Fast paths in highly recursive functions
**Learning:** In highly recursive functions like YAML normalization, common paths (exact type checking primitives and standard containers like dicts/lists) should be processed before expensive operations such as inline imports (`import datetime`) and `isinstance()` checks to prevent compounded performance degradation.
**Action:** Establish a fast path using exact type checks (`type(value) is X`) for common primitives and containers before executing expensive fallback operations.
