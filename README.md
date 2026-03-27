1. Open CMD (Command Prompt) or PowerShell.
2. Type julia and press Enter.
3. Once inside Julia (you will see the julia> prompt), copy and paste the following block of code:
using Pkg; Pkg.add(["LinearAlgebra", "Statistics", "Plots", "Unitful", "CSV", "DataFrames", "XLSX"])

Important: Data File Placement
For the power flow algorithm to execute correctly, you must ensure the network data file is properly located:
File Name: Oklahoma.csv
Location: This file must be placed in the same folder as your Julia program file (.jl).
