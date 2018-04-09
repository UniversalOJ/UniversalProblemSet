# 通用（在线评测）试题（集）交换格式
# Universal (Online Judge) Problem(set) Exchange Format

UOJ Prefers Extreme Freedom.   ——Mascoskray
一种面向现代化、面向世界、面向未来的算法题目交换格式。（雾）  ——Ceba
An algorithm-problem exchange format for the modernization, the world and the future. (with a huge area of fog)  from cebarobot


## 技术规格
  - 使用 YAML/JSON 来标记试题的各个部分。
  - 能够提供单文件和分散文件来存储试题数据。
  - 能够方便的转换，便于 API 读写调用。
  - 预留升级条件，便于日后扩展升级。

## 文件格式及其衍生格式扩展名
  - .upef (Universal Problem Exchange Format): 试题描述文件。为纯文本格式，采用 YAML 标记语言，试题数据以及附加文件单独作为文件存放。
  - .upes (Universal Problem Exchange Single): 试题单个文件。为描述文件和附加文件的单文本文件形式。在文本文档内包含试题数据和附加代码等。
  - .upea (Universal Problem Exchange Archive): 试题归档文件。为描述文件和附加文件的打包形式，采用 tar 方式压缩，便于传输以及解包读写文件。
  
  具体文件格式请参照附录中的示例。
  
## 其它说明
  目前的格式标准还只是最初构想，可能有不完善的地方甚至包括重大缺陷。希望这是一个良好的开始，如果你有什么意见或建议，抑或是想参与贡献，尽管联系我们，我们非常欢迎。
