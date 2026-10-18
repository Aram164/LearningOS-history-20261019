## 2024-10-18 - Fast paths for recursive traversal
**Learning:** In highly recursive functions processing data structures (like YAML ASTs), using exact type matching (`type(value) is X`) for common primitives and containers as a fast path significantly reduces overhead compared to immediate `isinstance` checks and lazy imports.
**Action:** Establish fast paths for primitives (str, int, float, bool) and standard containers (dict, list) using `type() is` before falling back to `isinstance()` or executing expensive operations like inline imports in recursive functions.
