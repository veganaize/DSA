DSA Coding Interview
====================

_Think out loud the entire time -- even when stuck!_


1. __*CLARIFICATION*__
   * Read / repeat the question out loud
   * Rapidly offer up concise examples _(as little as possible; as much as necessary)_:
     - Expected cases
     - Edge cases
     - Error cases ?
   * Discover all constraints & make concise note of them:
     - Input(s) & Output(s):
       - Minimums & Maximums (structure size, element size, negative values, empty)
       - (Pre)sorted ?
       - Duplicates ?
       - Types (null, unicode, floating-point)
       - Format (array, map, linked list, tree)
2. __*APPROACH*__
   * Avoid any form of pseudocode
   * Propose high-level solution(s):
     - Determine naive / brute force time & space complexity
     - Work toward an optimal solution (would interviewer prefer space efficiency traded out for better time, or vice versa?)
     - State time & space complexities
   * Get buy-in from interviewer
4. __*IMPLEMENTATION*__
   * Ask permission before writing _any_ code
   * Implement the agreed upon solution:
     - Import / include all external dependencies
     - Write clean code:
       - Comment inline code (blocks) for later reviewers
       - Good naming (not too short, not too long)
       - Consistent whitespace / indentation
       - Create appropriate helper functions:
         - To break down into smaller sub-problems
         - To keep code DRY
   * Mention line numbers when jumping around
   * Stuck?
     - Do a quick dry run
     - Revisit high-level (drawing board) solution
   * Test code:
     - Fix bugs on the fly
     - Don't say "done" until absolutely sure code is error free & runs properly
     - Dry run _at least_ one example:
       - Test actual implementation, line by line
       - Use comments to track state
     - Consider expected, edge & error cases:
       - Mention what else you'd test for, even if you don't do it now
