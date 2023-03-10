# 目录

## 第1章 计算机系统漫游
### 1．1 信息就是位十上下文
### 1．2 程序被其他程序翻译成不同的格式
### 1．3 了解编译系统如何工作是大有益处的
### 1．4 处理器读并解释储存在存储器中的指令
### 1．5 高速缓存
### 1．6 形成层次结构的存储设备
### 1．7 操作系统管理硬件
### 1．8 利用网络系统和其他系统通信
### 1．9 下一步
### 1．10 小结
## 第1部分 程序结构和执行
## 第2章 信息的表示和处理
### 2．1 信息存储
### 2．2 整数表示
### 2．3 整数运算
### 2．4 浮点
### 2．5 小结
## 第3章 程序的机器级表示
### 3．1 历史观点
### 3．2 程序编码
### 3．3 数据格式
### 3．4 访问信息
### 3．5 算术和逻辑操作
### 3．6 控制
### 3．7 过程
### 3．8 数组分配和访问
### 3．9 异类的数据结构
### 3．10 对齐(alignment)
### 3．11 综合：理解指针
### 3．12 现实生活：使用gdb调试器
### 3．13 存储器的越界引用和缓冲区溢出
### 3．14 *浮点代码
### 3．15 *在c程序中嵌入汇编代码
### 3．16 小结
## 第4章 处理器体系结构
### 4．1 y86指令集体系结构
### 4．2 逻辑设计和硬件控制语言hcl
### 4．3 y86的顺序(sequential)实现
### 4．4 流水线的通用原理
### 4．5 y86的流水线实现
### 4．6 小结
## 第5章 优化程序性能
### 5．1 优化编译器的能力和局限性
### 5．2 表示程序性能
### 5．3 程序示例
### 5．4 消除循环的低效率
### 5．5 减少过程调用
### 5．6 消除不必要的存储器引用
### 5．7 理解现代处理器
### 5．8 降低循环开销
### 5．9 转换到指针代码
### 5．10 提高并行性
### 5．11 综合：优化合并(combing)代码的效果小结
### 5．12 转移预测和预测错误处罚
### 5．13 解存储器性能
### 5．14 现实生活：性能提高技术
### 5．15 确认和消除性能瓶颈
### 5．16 小结
## 第6章 存储器层次结构
### 6．1 存储技术
### 6．2 局部性
### 6．3 存储器层次结构
### 6．4 高速缓存存储器
### 6．5 编写高速缓存友好的代码
### 6．6 综合：高速缓存对程序性能的影响
### 6．7 综合：利用程序中的局部性
### 6．8 小结
## 第2部分 在系统上运行程序
## 第7章 链接
### 7．1 编译器驱动程序
### 7．2 静态链接
### 7．3 标文件
### 7．4 可重定位目标文件
### 7．5 符号和符号表
### 7．6 符号解析
### 7．7 重定位
### 7．8 可执行目标文件
### 7．9 加载可执行目标文件
### 7．10 动态链接共享库
### 7．11 从应用程序中加载和链接共享库
### 7．12 *与位置无关的代码(pic)
### 7．13 处理目标文件的工具
### 7．14 小结
## 第8章 异常控制流
### 8．1 异常
### 8．2 进程
### 8．3 系统调用和错误处理
### 8．4 进程控制
### 8．5 信号
### 8．6 非本地跳转
### 8．7 操作进程的工具
### 8．8 小结
## 第9章 测量程序执行时间
### 9．1 计算机系统上的时间流
### 9．2 通过间隔计数(interval counting)来测量时间
### 9．3 周期计数器
### 9．4 用周期计数器来测量程序执行时间
### 9．5 基于gettimeofday函数的测量
### 9．6 综合：一个实验协议
### 9．7 展望未来
### 9．8 现实生活：k次最优测量方法
### 9．9 得到的经验教训
### 9．10 小结
## 第10章 虚拟存储器
### 10．1 物理和虚拟寻址
### 10．2 地址空间
### 10．3 虚拟存储器作为缓存的工具
### 10．4 虚拟存储器作为存储器管理的工具
### 10．5 虚拟存储器作为存储器保护的工具
### 10．6 地址翻译
### 10．7 案例研究：pentium／linux存储器系统，
### 10．8 存储器映射
### 10．9 动态存储器分配
### 10．10 垃圾收集
### 10．11 c程序中常见的与存储器有关的错误
### 10．12 扼要重述一些有关虚拟存储器的关键概念
### 10．13 小结
## 第3部分 程序间的交互和通信
## 第11章 系统级i／o
### 11．1 unix i／o
### 11．2 打开和关闭文件
### 11．3 读和写文件
### 11．4 用rio包进行健壮地读和写
### 11．5 读取文件元数据
### 11．6 共享文件
### 11．7 i／o重定向
### 11．8 标准i／o
### 11．9 综合：我该使用哪些i／o函数?
### 11．10 小结
## 第12章 网络编程
### 12．1 客户端-服务器编程模型
### 12．2 网络
### 12．3 全球ip因特网
### 12．4 套接字接口
### 12．5 web服务器
### 12．6 综合：tinyweb服务器
### 12．7 小结
## 第13章 并发编程
### 13．1 基于进程的并发编程
### 13．2 基于i／o多路复用的并发编程
### 13．3 基于线程的并发编程
### 13．4 多线程程序中的共享变量
### 13．5 用信号量同步线程
### 13．6 综合：基于预线程化的并发服务器
### 13．7 其他并发性问题
### 13．8 小结
## 附录a 处理器控制逻辑的hcl描述
### a．1 hcl参考手册
### a．2 seq
### a．3 seq+
### a．4 pipe
## 附录b 错误处理
### b．1 unix系统中的错误处理
### b．2 错误处理封装函数
### b．3 csapp．h头文件
### b．4 csapp．c源文件
## 参考文献
## 索 引