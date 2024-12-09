# Llama C++ playground

Setup:

```sh
apt install ninja-build
mkdir third_party
wget -P third_party https://github.com/nlohmann/json/raw/refs/tags/v3.11.3/single_include/nlohmann/json.hpp
```

## VSCode

`.vscode/c_cpp_properties.json`:

```json
{
  "configurations": [
    {
      "name": "default",
      "cppStandard": "c++20",
      "intelliSenseMode": "linux-gcc-x64",
      "compilerPath": "/usr/bin/gcc",
      "includePath": ["${workspaceFolder}/third_party"]
    }
  ],
  "version": 4
}
```
