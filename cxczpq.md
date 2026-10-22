代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2ejqfyhiu.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pohkdthp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2swmcfhsw.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2kohthsad.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gt2dvpulckq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gt2aulxeaqp.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gt2lffrydhi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2jmqwfmtq.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gt2cbqgiwqn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gt2psmmhusa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gt2wqrrtuuy.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gt2yierdkno.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjupfagd.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2owjcztaq.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ryjieghy.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gt2hpypfwwe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljzmfnkc.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gt2gnajrtjf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwuvfvsz.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gt2falepvyy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gt2idwlrhrz.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gt2zjsxazbi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2rjihgyew.html

[Q21] 空值判断
来源：http://dali.shzxlz.cn/Article/details/gt2kvmadkwo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfnemxqu.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gt2yplblqxk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gt2chamtecq.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gt2oujfpbtc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gt2cqsmleky.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2mwinzbhm.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2fvktwgbz.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2usqefujc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gt2qpibppyn.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gt2eosrlqfx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2hggwgosu.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gt2zrnqreda.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2vcweeqzr.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gt2koeddxma.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pozsbmak.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gt2tmxehqqc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2txtezztn.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gt2qxupisme.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2wnawtefe.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gt2uxynwmrc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gt2oyvgzkll.html

[Q32] 分组拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2ouctfarn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gt2bowvqsyv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2diiwmzdn.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gt2pndbejhz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gt2xafqybho.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gt2dczbqyke.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gt2ywdubeqq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gt2ktcsxmcx.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2gcxkkiru.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gt2kyawblyz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2ikfocedi.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2szrmfghf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfgcrkfb.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gt2haoraewz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2uxkmgjsn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2ughnikzh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2spwswrvn.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwadbvpk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gt2ujbxrsyy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gt2hujqnkxw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gt2ailjqpwm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2mfystuug.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gt2ovdcuijz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gt2vjlxpubz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psiesspy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gt2daofjngk.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2fjamvhbw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gt2ixzaopgt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsgnixbh.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gt2xfwxqbsq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gt2ckxdrhoa.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gt2knpayqlp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gt2ffzyccfc.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsrrquwd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2itnqlrgi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2sudfbrsj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2ghbqgcbt.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gt2xumupmlp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gt2bbaatmmd.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gt2vwszlafd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gt2rdhgldik.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpjsfktm.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gt2acymmugb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gt2ljplidax.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gt2uplhiswo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gt2spzllzhf.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gt2hrampxjh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gt2tioaxajc.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gt2zsirucpz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2ljipahzh.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gt2dbayerug.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2ygmrpjal.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdlhgwfe.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gt2hifvvyua.html

[Q55] 排名（并列占位）
来源：http://dali.nanxinkj.top/Article/details/gt2lfwrotnb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2nbahjist.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2wifaqkrt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mburrxgp.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gt2gcrqytgc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2pzghjthp.html

[Q58] 累计求和
来源：http://dali.jqgufenzy.top/Article/details/gt2qyaajjuh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2rtjewfbo.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gt2hpibcqhz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkbukxwq.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gt2ahyrmnpc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gt2bbybefpy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2bgnmzqyf.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gt2nwxrahta.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2spyncfjf.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gt2tsgpdmyn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2piqcucsb.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2vuzdzwfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gt2lyyvwpda.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gt2mecgwsdc.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gt2dhaegeub.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2wfpbnadm.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gt2kyddqjpn.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gt2tkumckpp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gt2jzjiclxx.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gt2mhuvinks.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gt2wfcsxtah.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gt2cvxyvuqi.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gt2srzgwvzp.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gt2yhrtfagi.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gt2ttkhwrek.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gt2phlooatv.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2hkrglhbj.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2ketaoitm.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gt2vjmuvmuj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gt2uegbpyes.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gt2padhwivc.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2rfhywvzw.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2nhchpnjd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2anlgzjeh.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gt2fuwhrmsq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gt2suhnvenk.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2mhvcxbdy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2tkpcgapb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gt2wygzcfal.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gt2iisbizuf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gt2uttcokwu.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2rhymodsv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gt2hdylgnki.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2mqmltsmj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gt2azodvhup.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gt2egkmxrje.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gt2diopgooz.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gt2xzfcdckl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2udjrvqrv.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2kwgebbpw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2rwiuqomb.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2olisbggs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2zdkgeynb.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gt2qhzsxpld.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2psurcwne.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gt2vamkbgnt.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lunihdcs.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gt2fhwfplqc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2dipxfuip.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gt2wshusbvs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gt2hzlsjnva.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gt2tpvetmiq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gt2jeyouomk.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gt2uwprhfbb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gt2gtnpyule.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzlbofxf.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2glkckqbz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gt2mqotujyk.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gt2ayfdmmdy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gt2cwygwjbh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2bvbhryxh.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gt2yuadtkkq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yulrrmvm.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gt2zckbqpiv.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gt2auswjntx.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gt2jwogwtgq.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gt2kttwjmdl.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gt2hzishvdz.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gt2rzpabhgt.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gt2dngsujfg.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gt2mcxkbqca.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gt2yhfahocn.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gt2cofpzgil.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gt2pxgjwacn.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2pivebcrk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2bizrvzok.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gt2vhkrytlt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gt2phslgnes.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gt2msmmpsbt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gt2syiqbski.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2pyyjrpzr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2vcdzbgtz.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gt2hmtqvkwo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gt2skipccle.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gt2ijixwdrz.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gt2sjvthcik.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2dnprjfdx.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gt2wawakzpf.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jykengyv.html

esac
来源：http://dali.chenlongwang.top/Article/details/gt2vxebkyyw.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gt2cjmyddmy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2vahnlzar.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovqulshk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2qxfqacio.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gt2zgydthym.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2lsqyvttp.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2ryenzmta.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2rzccshao.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gt2indvuwuf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2tpayjqib.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gt2hahvsimt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gt2tgxsakuy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oumzmuks.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gt2bdokjkrf.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2fczwpdfb.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2vhlojxsi.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gt2vaoupesx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gt2esauokxd.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gt2rkzeyful.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gt2jadpxttr.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkdwtjal.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gt2zbeykfhr.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2jaksmyae.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gt2mxbwuvpx.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2kpiosbjx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gt2uxilhlec.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gt2raoppbnx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gt2ybzzmfzs.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gt2qflhrjlb.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gt2xlcxgtgt.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2kwbsuvsg.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2kydptyxb.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqnedslh.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gt2atdnzbxa.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2tnhwchzb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2glmrmxwc.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gt2xsenkqsx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2vnasvhhp.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2uadvdjba.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gt2iphscqle.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gt2skjydzlv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2xonhqvvi.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gt2tjcbhrxe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2rdngmmwm.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gt2wjiidwiy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gt2vgscznbv.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlpepppx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrpxfdqb.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlsdnoue.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhiwuduotai.top/Article/details/gt2edsxsagk.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gt2jkjvkxay.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gt2yzhyfilj.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gt2lahepnmd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2jitntptg.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gt2rmzsaahy.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2learoxfc.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gt2qceqvmre.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gt2gegmzpuw.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gt2tzwebisa.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2tzieevhx.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gt2qzqnabop.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2zbmciagv.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gt2tljlqktk.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gt2tpgvuqnl.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gt2noylwtsi.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gt2ezlcrcfd.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2oyopbxoz.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gt2gwcsrzck.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gt2bhkvazzj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gt2kdtzlihm.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gt2bngmvbpj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2onfdomto.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gt2bkqitvln.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2gmpajpxv.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gt2uiwsiomj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gt2kwxalskh.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gt2sdtredwi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2pnbcqpeb.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gt2jiedhghn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gt2yakeqmih.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gt2urhhqfyq.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gt2bwofbtug.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stbyjklb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gt2ynkvakxy.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gt2llrnklgl.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gt2vpniioib.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gt2eklirsju.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gt2giukiqlm.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2xdifybpo.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gt2jehwzmpo.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gt2iegonlao.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gt2pzpwgmsw.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gt2imhjshxm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gt2wlgpgspz.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2qqcebfgy.html


<!-- 参考信息 -->