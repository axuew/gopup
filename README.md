## gopup (python3)

#### 建议安装方法
    pip install gopup

#### 升级方法
    pip install gopup --upgrade

GoPUP 支持Python 3.7+，旨在使获取数据尽可能方便，主要用于学术研究目的。

GoPUP 项目所采集的数据皆来自公开的数据源，不涉及任何个人隐私数据和非公开数据。 同时本项目提供的数据接口及相关数据仅用于学术研究，任何个人、机构及团体使用本项目的数据接口及相关数据请注意商业风险。

文档：[中文文档](http://doc.gopup.cn) 

#### 快速开始

```
import gopup as gp
df = gp.weibo_index(word="疫情", time_type="1hour")
print(df)
```

####  数据仓库

- 指数数据
    - 微博指数数据
    - 百度指数数据
        - 百度搜索数据
        - 百度资讯指数
        - 百度媒体指数
        - 百度需求图谱
        - 百度人群画像年龄分布
        - 百度人群画像性别分布
        - 百度人群画像兴趣分布
    - 头条指数数据
        - 头条指数数据
        - 头条相关性分析
        - 头条情感分析
        - 头条地域分析
        - 头条城市分析
        - 头条年龄分析
        - 头条性别分析
        - 头条用户阅读兴趣分类
    - 谷歌指数数据
        - 谷歌指数数据
        - 谷歌事实查证
- 宏观数据
    - 中国宏观数据
        - 中国宏观杠杆率数据
        - 货币汇率数据
    - 利率数据
        - Shibor数据
        - Shibor报价数据
        - Shibor均值数据
        - LPR数据
- 新经济公司
    - 千里马公司
    - 独角兽公司
    - 倒闭公司
    - 商业特许经营公司
- 信息数据
    - 新闻联播文字稿
- 生活数据
    - 中国油价数据
        - 汽柴油历史调价信息
        - 调价日的地区油价历史数据
    - 诗词数据
        - 唐代诗人
        - 唐诗数据
    - 影视数据
        - 实时电影票房数据
        - 单日电影票房数据
        - 单日影院票房数据
        - 实时电视剧播映指数
        - 实时综艺播映指数
        - 艺人商业价值
        - 艺人流量价值
    - 全国高等学校名单
        - 全国普通高等学校名单
        - 全国成人高等学校名单
- 疫情数据
    - 网易疫情数据
    - 丁香园疫情数据
    - 疫情历史数据
    - 百度疫情数据
    - 百度迁徙数据
    
    
#### 版本更新
    
    0.2.7
    诗词数据：唐代诗人、唐诗数据
    迭代百度搜索指数、百度资讯指数、百度媒体指数
    
    0.2.6
    中国油价数据：汽柴油历史调价信息、调价日的地区油价历史数据
    KOL微博数据：微博账户数据、微博运营数据  
    
    0.2.5.1108
    宏观经济：货币汇率数据
    
    0.2.5
    百度指数数据：百度需求图谱、百度人群画像年龄分布、百度人群画像性别分布、百度人群画像兴趣分布
    
    0.2.4
    全国高等学校名单：全国普通高等学校名单、全国成人高等学校名单
    
    0.2.3
    头条指数数据：头条指数数据、头条相关性分析、头条情感分析、头条地域分析、头条城市分析、头条年龄分析、头条性别分析、头条用户阅读兴趣分类
    谷歌指数数据：谷歌指数数据、谷歌事实查证
    
    0.1.9
    影视数据：电影票房数据、影院票房、电视剧播映指数、综艺播映指数、艺人商业价值、艺人流量价值
    
    0.1.8
    新经济公司：千里马公司、独角兽公司、倒闭公司、商业特许经营公司
    
    0.1.4
    利率数据：Shibor数据、Shibor报价数据、Shibor均值数据、LPR数据
    
    0.1.1
    宏观经济：中国宏观经济
    
    0.1.0 
    规范说明文档格式
    指数数据：微博指数、百度指数
    疫情数据：网易疫情数据、丁香园疫情数据、百度疫情数据、百度迁徙数据、疫情历史数据  