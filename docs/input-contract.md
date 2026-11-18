# 城市更新资料契约

全部楼宇、机构、居民群体、设备、交易及事件均为本地合成，不对应新闻所涉真实主体，不声称新闻中发生这些业务问题。seed.json及各同名Parquet保留完全相同的原始值；actions.json是尚未应用的后续资料。inventory.json仅记录物理大小、摘要及行数，不是业务结论。原始量纲、空值和时区按下文解释。

listings的episode为同次挂牌，dwelling_id为房屋，rent_cny是整月整套报价；contracts才是实际签约，lease_id唯一。housing_events给装修/拆分父子/面积变更，不预置同质标签。areas给坐标及施工/完工日期。households为更新前登记目标，income_low/high是月收入区间；followups.responded=false仍留在人群分母，补贴与租金均为元/月。comparison_requests给研究片区及可选空间尺度，split分研究及后期诊断。actions补一条远端搬迁回访，不提供指数或失访权重答案。
