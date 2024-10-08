# 自用抢课脚本

## 使用方法

1. 修改代码中的参数, 具体说明见代码注释.
2. 登录教务系统, 进入学生选课中心.
3. 在选课之前, 提前 5s, 按 `ctrl+shift+j` 打开控制台, 将代码复制进去, 回车运行.
4. 选课开始时, 手动进行选课, 以防脚本失效.
5. 在控制台中输入 `stop()` 停止脚本.

## 注意事项

- 目前 (2023-1-4), 教务系统有一个开放给 macOS 系统使用的端口 `4430`, 但实际上在任何系统上都可以使用. 在这个端口上**可能**更容易抢到课.
- 请注意在抢到课程或者脚本失效时及时停止脚本.
- 请不要设置太短的时间间隔, 否则可能会导致教务系统崩溃.
- 理论上, 该脚本可以适用于任何使用强智教务系统的学校, 但只在北京邮电大学进行了测试.
