## Product of Array Except Self

**Pattern:** Prefix & Suffix Products

**Approach:** For each index, the answer is **(product of everything to its left) × (product of everything to its right)**. First pass stores the left/prefix product in `output`; second pass goes right-to-left and multiplies each position by its right/suffix product.

**Time/Space:** O(n) / O(1) extra space

**Gotcha:** Don't calculate prefix/suffix separately for every index—that becomes O(n²). Store the prefix **before** multiplying by `nums[i]` so the current element is excluded.