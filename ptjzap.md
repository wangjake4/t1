代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2dupzuaid.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gt2xliqbhhp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2eytyytyh.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyktagta.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2pobhoyfu.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gt2etysozub.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2viqdbisx.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gt2yszrahqq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmvveona.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvesvip.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2vdxeldfl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2mzcxgrng.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gt2kalnlztn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gt2gbnuharb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gt2jfeshypi.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2dvesjeaz.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2jtbpzxmq.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2vuqtivub.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2nbttsemd.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gt2bswkxtty.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2mhkwoxwb.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gt2bkunumhl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gt2wyeglqgl.html

[Q19] 范围查询
来源：http://dali.yj202588.top/Article/details/gt2foewtqav.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gt2zplidqxd.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gt2eszseyws.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2ektmfptm.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gt2vxrikayq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2gykrbvlg.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gt2ibfgscqy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gt2ptniqpmt.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gt2ncjytybm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gt2kimowsjd.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gt2adswplrc.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dncnhweh.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxvthvsc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gt2poitvzrf.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2uanrghte.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2dknptyng.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gt2pbjtljyg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2xgoeoevo.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gt2ashykfhe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouxhhcnd.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2gnelmpvu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2wvjsccjg.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gt2ysuuauoo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2mprwpgrv.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2noiwvawf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gt2vxwxyolv.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2wtndgtbr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2cpeqnvss.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gt2vfffopws.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpcgfmcd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2addrwhcz.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gt2glwepqlm.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gt2phbpsgri.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gt2wgioxjks.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuabkhwq.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gt2cqngieqg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gt2bjnqczpu.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2lzjttklr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2wctybqpx.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gt2jdwztfxg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gt2knyxgshc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gt2abgoutzt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2yaoewowz.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gt2yodyyejl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gt2yoonehqs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gt2yfijjbdb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gt2mpjvdvrj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gt2layprivv.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gt2pddtkkgr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gt2ingmrwer.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gt2wiqidowt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gt2aezztpco.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2laqmyrax.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gt2vqlpsnts.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gt2kfepcgaj.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfwjjvlw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2ijicxjhh.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2syqzdxpa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gt2mmqwcghl.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gt2iqdtuksz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2saccvyro.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gt2mocazukq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2iddexeek.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gt2mjxdmhcb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gt2jjwggzhw.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gt2bzsbxikn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gt2kdiugqza.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfizpced.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cxefjnvf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2ddvkmyno.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gt2wfxagnrp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2iclooryo.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gt2gzrqrsdn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2uhwcjjej.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gt2jyrcqyjf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbibuvjt.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2bvnqbcec.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2rtojiuso.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gt2qxvlrilo.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gt2buigzmfz.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gt2hrnbdcba.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gt2byawulyg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gt2vueadhmb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yluhksxz.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gt2jostpkmn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2kmduhhum.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gt2nmvbisfi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2zppkgsgf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfwvlaj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2jlwphcey.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gt2umcgwqxu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gt2sscvubud.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2zasgfajl.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gt2jlcvbwen.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2mppxlubo.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gt2lkpqvnvz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmjtnwmk.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gt2ehkqhilg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gt2kgknuqnj.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gt2djmneovu.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gt2druzxobx.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gt2iailpxsa.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gt2ovitgmsu.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gt2wqhovixb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gt2mkhiwnpx.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gt2spxvvywd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gt2kygceugl.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gt2ugltkkwc.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxjqommp.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gt2xqrymmsb.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gt2lfharnnn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gt2awifwepe.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gt2cbcqrvik.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gt2xyyqsmve.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gt2edrudehf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gt2pdowwnpm.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gt2sbfhxsei.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdixlgyu.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gt2ynrxssgm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2diieqdoq.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcxjltud.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gt2rguvbxvu.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2yudtxybj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2qeasovxc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxqpsyqs.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gt2dumcukhk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gt2eebzvbwu.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gt2dmclaagq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2kkeencoh.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gt2lkswuthr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gt2gvdwcrwi.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2figjfqbc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gt2nxotagdw.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gt2kgdppibw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2sieufuea.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2anpghixc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2xbudsoio.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gt2xakjzrnp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2gpiwylcf.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etakmmlf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urdnwjel.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gt2koxdcufo.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2iezqqwbx.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gt2dopxdiyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gt2pipddvys.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gt2jrdipkjs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gt2bxvenmkb.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gt2wwwkugam.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gt2dxojtuoe.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gt2suvgxasg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gt2gptrondb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ektyycgq.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvtizejl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2utwzkwma.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gt2edqinkkh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2xqxfmrby.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ljcnawxh.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gt2nodadzty.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xzwahehn.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gt2evuwhuox.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpnfcdpv.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gt2jnzhfjae.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gt2afzyxchn.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gt2apdiuwde.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2lvljhmpw.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gt2vabbrzzp.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gt2yorldomo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gt2nzlaqxxn.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gt2uuwauoce.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqyfghqh.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gt2ktpnkqrt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gt2vlsoxcoj.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gt2lhgkfpaz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2xhccguvq.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gt2yitpgmtv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gt2ihrdbkuv.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2fsnhcsbw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2ljsrjdgv.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2jnqoepwc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gt2zjbnersd.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gt2mtbwyztn.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gt2oyhxypgb.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2mheawlif.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2fyqxhrlg.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gt2luqmfiqm.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2odopoqai.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gt2ixrleqpe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gt2tkydlafn.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2dwpxfnzz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2pczzoujp.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gt2qnmmppvp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2rjjxdykt.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2khtusezf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gt2rfpjizim.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwugnbxf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2ymjmtlpg.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gt2sbarvwjl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gt2olzubrmg.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gt2pgpwnjfk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2zhzvlwzw.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2xyqxckib.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gt2jywxuufl.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2zqggckat.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2zabcdajn.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gt2fspwxszb.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gt2nohhiege.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2qebcuxnv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tppzqhey.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2uqlytyoo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvptlmb.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2ndgzwvzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gt2veqjwyjs.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijfpwpdt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gt2uykncpjw.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gt2rmqkvcox.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gt2yzsldcih.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gt2marefngd.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2fkcskous.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gt2tseovrbk.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnulxgsj.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2xpunfjrj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gowikrvk.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2nrpwytrc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gt2yyqivlln.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2ldtinoqs.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gt2obdxgukv.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gt2vnjfbotz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2wbqmottg.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gt2yafavxjp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gt2ziwrpyta.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gt2dhrfuuoi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gt2luszxitj.html

[R35] 后台执行并等待
来源：http://dali.yueranfly.top/Article/details/gt2oqeilqol.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gt2ixgbfhvw.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gt2ljgzceax.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2tmjohntr.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gt2imnmrzge.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esyhmyqm.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gt2kwfchszk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gt2wevoqifs.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gt2omtfcnqc.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gt2jjhitynt.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gt2ljmqnxzw.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2xwjgphsi.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gt2yohbjuol.html

cmd >/dev/null 2>&1
来源：http://dali.cucudq.cn/Article/details/gt2xenzzxsv.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gt2rtpowakw.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2baplqnjj.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gt2pwbnkmay.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2fxvomtxt.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdrihacz.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gt2vwtzyugv.html

[R45] 批量删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyaganfc.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gt2ctdmupte.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gt2ftzrbpmm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gt2ucyqcuoh.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gt2lmsadjve.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvpeuyrb.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gt2zdactasj.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnerxngm.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gt2extyattd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gt2inzlgrdu.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gt2kkmgwiew.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2olawwped.html

[R51] 排序去重取前几
来源：http://dali.zdqjudy.top/Article/details/gt2latiggmd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gt2nedhooja.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gt2djraaint.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2fmzeahqe.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmnsgzei.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eevzkwmz.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gt2xjibxkeh.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gt2slvsylcv.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gt2ikeipkyn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gt2yhwgzzjx.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2kqpbahps.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gt2tivaszfl.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gt2jpaloqbn.html


<!-- 参考信息 -->