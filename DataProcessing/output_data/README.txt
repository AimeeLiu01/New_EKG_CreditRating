ListedCoID [上市公司ID] - 国泰安内部编制的上市公司ID。
SecurityID [证券ID] - 国泰安内部编制的证券ID。
Symbol [股票代码] - 上交所和深交所上市的证券代码。
ShortName [股票简称] - 上交所和深交所上市的股票简称。
EndDate [年度区间] - YYYY-MM-DD。
IndustryName [行业名称] - 2012版证监会行业分类名称。
IndustryCode [行业代码] - 2012版证监会行业分类代码。
RegisterAddress [注册具体地址] - 以交易所公布的信息为准。
OfficeAddress [公司办公地址] - 以交易所公布的信息为准。
SocialCreditCode [统一社会信用代码] - 以交易所公布的信息为准。
Sigchange [重大变更] - 报告期间内因收购、出售资产或吸收合并等引起公司重大资产或主营业务发生变更的说明。
FullName [中文全称] - 以交易所公布的信息为准。
LegalRepresentative [法人代表] - 以交易所公布的信息为准。
EstablishDate [公司成立日期] - 以交易所公布的信息为准。
RegisterCapital [注册资本] - 以报告中公司简介信息为准。
Website [公司网址] - 以交易所公布的信息为准。
BusinessScope [经营范围] - 经营范围及主要产品或提供劳务。

F010101A [流动比率] - 流动资产／流动负债；当分母未公布或为零时，以NULL表示
F010201A [速动比率] - （流动资产－存货）／流动负债；当分母未公布或为零时，以NULL表示
F010401A [现金比率] - 现金及现金等价物期末余额／流动负债；当分母未公布或为零时，以NULL表示
F010702B [利息保障倍数B] - （净利润+财务费用）／财务费用；分子各项目为空时，以零值代替。当分母未公布或为零或小于零时，以NULL 表示。
F011201A [资产负债率] - 负债合计／资产总计分子为空，零值代替；分母为空或是零值，结果以NULL表示。
F011301A [长期借款与总资产比] - 长期借款／资产总计分子为空，零值代替；分母为空或是零值，结果以NULL表示。

F030801A [固定资产比率] - 固定资产净额／资产合计；当分母未公布或为零时，以NULL表示；
F030901A [无形资产比率] - 无形资产净额／资产总计；当分母未公布或为零时，以NULL表示；
F031201A [留存收益资产比] - （盈余公积+未分配利润）／资产总额；当分母未公布或为零时，以NULL表示；



F050202B [总资产净利润率（ROA）B] - 净利润／总资产平均余额；当分母未公布或为零时，以NULL表示：总资产平均余额=资产合计期末余额+资产合计期初余额）/2
F051101B [息税前利润与资产总额比] - 息税前利润／资产总额；当分母未公布或为零或小于零时，以NULL表示
F051201B [投入资本回报率] - （净利润+财务费用） ／（资产总计-流动负债+应付票据+短期借款+一年内到期的非流动负债）。当分母未公布或为零或小于零时，以NULL表示。
F051401B [营业利润率] - 营业利润／营业收入；当分母未公布或为零时或小于零时，以NULL表示。
F051501B [营业净利率] - 净利润／营业收入；当分母未公布或为零或小于零时，以NULL表示
F052401B [息税前营业利润率] - （净利润+所得税费用+财务费用）/（营业收入）；当分母未公布或为零或小于零时，以NULL表示


F070101B [财务杠杆] - （净利润+所得税费用+财务费用）/（净利润+所得税费用）；当分母未公布或为零、财务费用小于零时，以NULL表示
F070201B [经营杠杆] - （净利润+所得税费用+财务费用+固定资产折旧、油气资产折耗、生产性生物资产折旧+无形资产摊销+长期待摊费用摊销）/（净利润+所得税费用+财务费用）；当分母未公布或为零、财务费用小于零时，以NULL表示
F070301B [综合杠杆] - （净利润+所得税费用+财务费用+固定资产折旧、油气资产折耗、生产性生物资产折旧+无形资产摊销+长期待摊费用摊销）/（净利润+所得税费用）；当分母未公布或为零、财务费用小于零时，以NULL表示；或者：财务杠杆*经营杠杆；


F040202B [应收账款周转率B] - 营业收入／应收账款平均占用额；当分母未公布或为零或小于零时、分子小于零时以NULL表示；应收账款平均占用额=（应收账款期末余额+应收账款期初余额）/2
F040502B [存货周转率B] - 营业成本／存货平均占用额；当分母未公布或为零或小于零时、分子小于零时以NULL表示；存货平均占用额=（存货期末余额+存货期初余额）/2
F041702B [总资产周转率B] - 营业收入／平均资产总额；当分母未公布或为零或小于零时、分子小于零时以NULL表示；平均资产总额=（资产合计期末余额+资产合计期初余额）/2



F080101A [资本保值增值率A] - （所有者权益合计）本期期末值/（所有者权益合计）本期期初值；当分母未公布或为零或小于零时，以NULL表示
F080301A [资本积累率A] - （所有者权益合计本期期末值—所有者权益合计本期期初值）/所有者权益合计本期期初值）；当分母未公布或为零或小于零时，以NULL表示
F080601A [总资产增长率A] - （资产总计本期期末值—资产总计本期期初值）/（资产总计本期期初值）；当分母未公布或为零或小于零时，以NULL表示
F081202B [营业利润增长率B] - （营业利润本年本期金额—营业利润上年同期金额)/（营业利润上年同期金额）；当分母未公布或为零或小于零时，以NULL表示；
F081602C [营业收入增长率B] - （营业收入本年本期金额-营业收入上年同期金额）/（营业收入上年同期金额）；当分母未公布或为零或小于零时，以NULL表示；

