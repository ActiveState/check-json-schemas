The `check-json-schemas` tool validates that all the JSON files in a directory
contain a schema that
[github.com/xeipuuv/gojsonschema](github.com/xeipuuv/gojsonschema) can load
and validate documents against.

    -dir string
        The directory containing the schemas to validate.
    -help
        Show usage information.
    -verbose
        Print verbose output.

If if finds any invalid files it will set the exit status to 1. Otherwise it
is 0.
