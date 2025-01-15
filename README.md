# Ambiguous Return Type in Julia Function

This repository demonstrates a potential issue with ambiguous return types in Julia functions. The `myfunction` function returns a different type depending on the input. This can lead to type instability, impacting performance and potentially causing unexpected errors in larger programs.

The `bug.jl` file contains the problematic code.  The `bugSolution.jl` file demonstrates a solution to improve type stability.

## How to Run

1. Clone this repository.
2. Open a Julia REPL.
3. Navigate to the repository directory.
4. Run `include("bug.jl")` and `include("bugSolution.jl")` to see the original and improved code in action.