DSA Coding Interview
====================

_Think out loud the entire time -- even when stuck!_


1. __*CLARIFICATION*__
   * Read / repeat the question out loud
   * Offer up concise examples (as little as possible; as much as necessary):
     - Expected cases
     - Edge cases
     - Error cases ?
   * Discover all constraints & make note of them:
     - Input(s) & Output(s):
       - Minimums & Maximums (structure size, element size, negative values, empty)
       - (Pre)sorted ?
       - Duplicates ?
       - Types (null, unicode, floating-point)
       - Format (array, map, linked list, tree)
2. __*APPROACH*__
   * Avoid any form of pseudocode
   * Propose high-level solution(s):
     - Determine brute force / naive time & space complexity
     - Work toward an optimal solution (would interviewer prefer space efficiency traded out for better time, or vice versa?)
     - State time & space complexities
   * Get buy-in from interviewer
4. __*IMPLEMENTATION*__
   * Ask permission before writing _any_ code
   * Implement the agreed upon solution:
     - Include / import all external dependencies
     - Write clean code:
       - Comment inline code (blocks) for later reviewers
       - Good naming (not too short, not too long)
       - Consistent whitespace / indentation
       - Use appropriate helper functions:
         - Break into sub-problems
         - Keep code DRY
   * Return to drawing board (high-level solution) when stuck
   * Test code:
     - Don't say it's "done" until absolutely sure it's error free & runs properly
     - Dry run at least one example -- using comments to track state
     - Test actual implementation, line by line
     - Consider expected, edge & error cases
     - Fix bugs on the fly
