Basic tests for the generators feature.
The following cases are covered:
- Generator files are executed and generated files are deployed 
  into the respective folder.
- The folder is passed correctly to plugin.
- Generators are executed in alphabetical order.
- Generators with non-zero exit code are are mentioned in the output
  and do not stall the execution.