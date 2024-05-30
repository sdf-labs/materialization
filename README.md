[![SDF Workspace Compiles](https://github.com/sdf-labs/materialization/actions/workflows/compile-workspace.yml/badge.svg)](https://github.com/sdf-labs/materialization/actions/workflows/compile-workspace.yml)

# Official SDF Materialization Library

This SDF library handles the final step of SQL generation during SDF compilation.  These jinja macros produce the SQL queries during compilation that will then be run against the execution engine of choice. The processing of these macros happens as a final step after the actual compilation of the SDF model.

*Note: SDF is still < v1, as such certain scenarios may result in unexpected behavior. Please follow the [contributing guidelines](./CONTRIBUTING.md) and create an issue in this repo if you find any bugs or issues.*

For an in-depth guide on how to use materialization in SDF, please see the Materialization section of [our official docs](https://docs.sdf.com/guide/setup/materialization)

