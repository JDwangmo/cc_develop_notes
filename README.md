# cc_develop_notes
record some useful notes in c++ development

### 1. g++编译检错
1. g++ 编译的时候加上-Wextra, 会提示warning, 如 g++ -o main main.cc -Wextra

### 2. 编程注意事项:
1. 检查有没有 有符号类型 和 无符号类型 的比较
2. 因为构造函数不能返回报错信息, 所以建议不再构造函数中不创建数组, 另外使用一个 init 函数初始化;
3. 类中写好free和init函数
