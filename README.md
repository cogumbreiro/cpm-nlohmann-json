# cpm-catch
[CPM](http://cpm.rocks) external for
[Nlohmann's JSON](https://github.com/nlohmann/json/) library.

## Usage

Add this line to your `CMakeLists.txt` file:
```
CPM_AddModule("cpm-catch"
  GIT_REPOSITORY "https://github.com/cogumbreiro/cpm-nlohmann-json")
```

Add this to your C++ code to use JSON:
```c++
#include <json.hpp>
```

