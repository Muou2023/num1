以下是获取当前时区的时间的Python代码：

```python
import datetime
import pytz

# 获取当前时区
tz = pytz.timezone('Asia/Shanghai')

# 获取当前时间
current_time = datetime.datetime.now(tz)

# 打印当前时间
print('当前时间为: ', current_time)
```

你可以根据自己所在的时区修改 `tz` 变量的值。在示例代码中，我使用的是“Asia/Shanghai”时区。
