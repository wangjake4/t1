代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gtozjcgppv.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtaelqiaag.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtjlcejxno.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gteacystdw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gthhdhvshu.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtpctfqvve.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjjpvslx.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtrcrmwaab.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtchohrosq.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvbreihj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtrzbvjxyn.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtokyipwbv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtreqtybgd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gtwcouzgpt.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivszjroj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtdkexehph.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhrtgjvs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtvwvimprm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtwksfrvdi.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtbissiugs.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtwagjjbbl.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtwaycrxnl.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gthetcwllt.html

[Q17] 条件查询
来源：http://dali.bjfxy.top/Article/details/gtfzqimmqa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtvhlfqhcy.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtdzifailq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtbanqogwr.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gttwxgffcj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtbvgddjjm.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gthkbgovfr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gtxorrvihe.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtywwynaly.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtrmpmfafn.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gthkuraemj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtmstdzrdy.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtdtyyqtqv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtkbrflecn.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gttymemcjk.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtmgblxelu.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtljaanntd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpovukop.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gtahdyodzp.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoswaite.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtmjlhhnpz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gtxhhokpjy.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtqacimwsr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtvtwiudbj.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtgkcruvqh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyihrbiii.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtnvntjxic.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtsrkcujrj.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtfkzodhgt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtcjhxtdtq.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtzblcwywf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtuvxsyesp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtexkgmwvo.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gtebqjliwp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtpqcjsgiu.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gtmlymvalv.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtwxmdniom.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtiphgqsdb.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtcgiyfttk.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gtmwqfabfm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtlldrdwpk.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtoxtjoply.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtlqoeaypz.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtketesygi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtdnmcpuhm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtvwpevsyq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gtxxaecmeb.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gteakrgras.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtwmskjcpr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtjpyccqkq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmufzembc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtnlrzblcp.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtfohgwzhv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtoseagbbu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtyqlascye.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtubfxcnjn.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtsvusiqnq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gtoqoejilr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtonwouzjt.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gtjefrqlvi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtvxisfwgo.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gttbmoyydx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtjkdnwljj.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtvugvqrer.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtmdjnlxse.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtjluyfvbx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssjfgpon.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gtpqsoojjt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gttdewxmyi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtunyxhpjx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtiwpnttun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gtmrnmugqx.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtchkvrxyf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtdqyzjpda.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtvygdeteq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtrtnffvqd.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gtthuidugx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gtbssayqqt.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gtvcmymeol.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtnednwxab.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gtxdnsgxqz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtqtnnyncr.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtksebzqus.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtysajziix.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gtzgohwfmt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtrjcawnfa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtyxmtqski.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtbehzjlsp.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gtobcccfvq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtyiybrcnp.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtnbtlbvgs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtefvneurq.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gtagaqbuyq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtgfyncisc.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtkdxyzovy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnpvrdbe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtruettocg.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtayixdtse.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtmiskucga.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkrdqoxv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtglwvtdgp.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtdazchzxt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gtmynplouw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtkizlgxpp.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtdxlupsya.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtrswixwjt.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtwzdkusbs.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhmaqzup.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtdpjqklwy.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gtpyqqlccw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtrpolwzxh.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtusqezdgi.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtvbcrahff.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtbjuodnei.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtxlzmwsel.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafxpaxbc.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtasybweva.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtdjbsjhod.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtwvoculfi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtrodhnexz.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtypyfftnv.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtdgwhqjgd.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtkzuqrhwq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gtrvnlkyfw.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtojvnehtu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlvrjwlr.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqobqjyrj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtsjagwctw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtkevpnuio.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gtyegpsmwy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gteexiwiam.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtsxwlvlmn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtgikfcava.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtitrpvrhk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gteljevbox.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtigiorlbf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtaclwdeyo.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtwvpbgvfj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtwiqjgcmf.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtbvnmsbin.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gthzattnfb.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtsvbwooup.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtrcltblrs.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqmxznbu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtounlqegm.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtrcajvawz.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjmzyawts.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gtercmjebm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqutlaee.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtesuxzawu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtqwkfeulj.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtjrjddvzb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtlbixhoao.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtpnhkmtul.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gtozmxjudt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtlbeczvrt.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtyyjhndyv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtwwycjlyi.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtdhkprotv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtkwjgykis.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyorjdpvg.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtdilycyno.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtuzkfjnkq.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtmemmukbn.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtdsrvtvia.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gthfgeqlcz.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtzblshuyr.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gttdsmokfe.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtpukqvjhp.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtqcozuxaf.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gtvhoambsc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gttxzltvku.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtskybzjtj.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtvczwiqyc.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtzilyfyiq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtextmgxar.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gtetazmbjf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gthbersacc.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gtdllzcyld.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtmkbrteri.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtmjdpmpfa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gtqlaydftc.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtwladmxuk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtoviglkym.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycunmpll.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtlpbabkzq.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gtllaebssd.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtjsrhsqwt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtdsoushdk.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfjwujop.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtspygazon.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtuirqkqlg.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtjavlxeui.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtzxmdxwoj.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gtxledzxmt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxtpgktg.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtqhqfqwmh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtftziufbu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtvlapcdaa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtgnzvgupi.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtnfmpsrzi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gtoizcsnep.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtjvthfjij.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtiwdyipsh.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gttyahgyek.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtvyzlafxe.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtrxxgpwts.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtjwjlqnyr.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtgxwfsbtu.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtajbrkler.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtxroffvef.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtvzprmmsp.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtcuxzlgmp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkojpqxb.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtmzslmuoj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtkesmiifm.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gtvieeedyx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtnbsehfbb.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtmkuhfbuw.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gthrinpkqu.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtcvfymgcz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtzulxdbbs.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gttqsdhwdu.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gttkbivrcq.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtqktpgcpv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gtznpirdpo.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtvcyudbte.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtvkoglqgi.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtekadjxpk.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtifdupwsb.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtqnqpbjaa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtzqjgsyte.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gtrgfhtirw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtldjmfsuz.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtyvflzjak.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtyijwwokp.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtcvswlois.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtejecmulf.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtfxseppgf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtxawtdwem.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gtuoksithy.html

files=$(ls -1)
来源：http://dali.hfpthk.cn/Article/details/gtncbyyvla.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtstspgwty.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gtppsfljns.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtyqdvlmne.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gttmdvjvik.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtpfmbxwit.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtkmxtfifm.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtlycnxqcq.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqokydyq.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtlffcpzne.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtiedzcaxl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gticweoxhv.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gtetylyhsj.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gthkpbzqov.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtgbhyioai.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtttueezgw.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtayuacyfn.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtgaghjyka.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtrjyshyzx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gtvymgrvqx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gteixtnxyc.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gtdakjescw.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtatvjdzft.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gttdspkkzd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxotovvbm.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gtrovynzsz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtavwdzcry.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtifaxvtzk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.vqdsnc.cn/Article/details/gtekkikkox.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtstumvkam.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtblmljctg.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gtxinxhbvv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtyoudoktc.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtqwtsuywk.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gtzfnledmq.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtswlyozvr.html


<!-- 参考信息 -->