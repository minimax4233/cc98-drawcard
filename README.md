# cc98-drawcard
需要在**内网**环境下使用。

使用了 v3.1 版本加入了入口和修改输出

# 功能：
只会抽11抽
可以根据输入的魔力值自动抽取最大的次数。

# 使用
1. 先在 cc98.json 填入自己的帐号密码。
1. `python3 drawCard.py` 不输入参数会提示输入次数
2. `python3 drawCard.py 次数` <=5000 会被认为是次数
3. `python3 drawCard.py 魔力值` > 5000 会被之为是魔力值，然后会自动计算可以抽取的次数。
