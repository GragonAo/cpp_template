
# C++ Project Template

这是一个用于 C++ 项目的模板目录结构。此模板可以帮助你组织代码、头文件、库、文档、构建文件等。

## 目录结构

```plaintext
cpp_template/
├── README.md               # 项目说明文件
├── build/                  # 构建输出目录
├── docs/                   # 文档目录
├── include/                # 头文件目录
├── lib/                    # 第三方库目录
├── src/                    # 源代码目录
└── tests/                  # 单元测试目录
```

### 详细说明

- **README.md**: 项目的说明文件，包含项目简介、安装和使用说明。

- **build/**: 构建输出目录，存放编译生成的文件（如可执行文件、对象文件等）。你可以在这个目录中运行构建系统，如 `cmake` 或 `make`，以生成项目的构建文件。

- **docs/**: 文档目录，包含项目的文档文件，例如使用说明、设计文档和 API 文档等。

- **include/**: 头文件目录，包含所有的 `.h` 或 `.hpp` 文件。这些文件定义了项目的接口和数据结构，供源代码和其他项目使用。

- **lib/**: 第三方库目录，包含项目依赖的第三方库或模块。你可以将第三方库的头文件和库文件放在这个目录下。

- **src/**: 源代码目录，包含所有的 `.cpp` 或 `.c` 文件。这里是项目的主要实现部分，你的代码逻辑和算法都在这里实现。

- **tests/**: 单元测试目录，包含所有测试代码。你可以在这个目录中编写和组织你的测试用例，确保代码的正确性和健壮性。

## 构建和运行项目

### 使用 CMake 构建项目

1. 创建构建目录：

   ```sh
   mkdir build
   cd build
   ```

2. 运行 CMake 以生成构建文件：

   ```sh
   cmake ..
   ```

3. 编译项目：

   ```sh
   make
   ```

4. 运行生成的可执行文件：

   ```sh
   ./your_executable
   ```