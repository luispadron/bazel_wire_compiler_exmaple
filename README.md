# bazel_wire_compiler_example

An example of using Wire with Bazel for Swift proto compilation.

## Examples

- Running the compiler:

```sh
bazel run //:WireCompiler -- \
    --swift_out=$(pwd) \
    --proto_path=$(pwd)/Protos
```
