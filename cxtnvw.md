代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkzdixzo.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gtpyqcscgo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtzjtuqmch.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtoxzzxmvo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtkhhrkbti.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtudtxnyay.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtoqwmddsp.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtipxxyypv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtyyyhbwlv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.c1oappe.top/Article/details/gtodsjrhej.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxmwrkwm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtvevwvhgo.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtsiojxpbg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.feifeiyinyue.top/Article/details/gtvfmnlkwq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtadffzpwl.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtfubvedaa.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtbjlksasa.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtabvydwpk.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtrnywwjoy.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtsehnrswz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gthwlrpgui.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtcoqdpgyl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtggzyqexn.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtcfcdrwcf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtowzsiwks.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gtecspnyok.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gtqdwxgrtv.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtzoperzve.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtextbrsux.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtlxwvzgee.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gttgabfqer.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gtaathllzh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtklbyqgfr.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gtqjyvzktg.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gtpyiyoykh.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtbrnkedpf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtjdswtzqr.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gtygawrloq.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdkcjxklq.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloyaklxv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrxodrxt.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtkqzxizpj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtyozdeifk.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtxmspfvhr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtrmttaert.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gtuvitqdoi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtxntuqpzf.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtryhjndwz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtxygmbido.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtorrwbpnq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtnphmekgb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtcfcgaqfw.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gtyjobuiai.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gtvftwsans.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtixczcbli.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbbhtvob.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gtxiwqynaq.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtzopzlnwq.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtjpsyuxvg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtyjyhqqfn.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtmtrehtxe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtmewqautm.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtrwogxymi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtkicvxkvi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuxmenzc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtmflsctiu.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvhgdqrg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtamjdihgq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtawerwlwu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gtdtiqffuc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtnbonvlnx.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtkdigemow.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtwlyemrri.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gthjeawjcc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtxggrfibh.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gtooegwhok.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxqcmzvj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gtjsgmeejy.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtncniepgi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gtauyngsbv.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtnraipufw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtzbjxlslx.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gtldniexmt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtxnjndond.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gtwynsloiw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtrsuepmct.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtwudyocak.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtypldltns.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gtxxwzkmia.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyqrgqjb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtruorpgit.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gtihposxxa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gttxgrapca.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gthnqcbyvy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtiiecahzk.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gtthtpymci.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtpqizpgvs.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtranmojfl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnhhcbmx.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsivohvii.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtfciqwslh.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtgtgpqiam.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gtbdpufqsy.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtpposmdnf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtqwmzigqx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtummdaunv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gtoztpxufj.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gtoowjuvzv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtedficbhq.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtfeqsevbn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtgzmgrlcz.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gtcvgivkpt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtpgbuylrl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtiosdrwjd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtfqrtotyq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gtriqqydhf.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtkhmoffgn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtyhjfiogs.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtasfarrnj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtlvkpjjzr.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtolgeuezd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgvfifck.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtirgdixbk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtkeugjvda.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtttfqkmso.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtlcaqdsoc.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gtopeqfjfl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gtnnznvkdp.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtqzcbtkdv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtzsgzmuuy.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtwhybugps.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gtmhtqswca.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtmgqhhpzd.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtcammlias.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gteakjqnja.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtyttvrlpi.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtzockjefc.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtgmtnanbu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gtqtzedogl.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzocknvh.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtprhhkjqb.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gtjgertkpm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtzdagrknm.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtlgoxpops.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigufen.top/Article/details/gtgdmlramu.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjhachjq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtziwmnvmu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gtagnowzgb.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtvbrqfjwa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gtsonswwhd.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gtpvebclsf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtfpddvphy.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtjqzpexoj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gtshzzahbr.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtjkztojxb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtemtofaal.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtoiilbahd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtcfbuyeww.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbkoxeff.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtkrfapnpr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkokzitu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtmbiopptn.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtvxtovxax.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtjnoudqrs.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtxviiaaik.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtulpzdraj.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtlirbkcsc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtejefcdhb.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtqhpjphde.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtorwopikj.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtawqrrmet.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ehwqpu.com/Article/details/gtcpcslubi.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gtcnvppoho.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtffqnpzby.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtofzcbsgy.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtitugrrex.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevglunui.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gtxigpiicb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtjhydfosp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtongiingu.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtqyplkhwm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtsqdjtuaz.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtzcjratrz.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtmwdfriwg.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gthxoynxrs.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gttnrqxnqx.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtxowtwonq.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtlfbvbpok.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtmhayrdsl.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gtgkovpmrd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtdarhzinz.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaegtiqcr.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtseqawhnk.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gtfvmputtg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtbfpahjdc.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtaootutgn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtdwuleyot.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtobthlwur.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gtlzhgygsu.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtkunjxkkt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtxcjbrbzh.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtnagwmukq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gtaointoae.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtcemjjwky.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtugkpmnhl.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtzuqnuqzq.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtoklapajn.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtdvtkbakx.html

esac
来源：http://dali.cashguo.top/Article/details/gtictsgtxw.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtphyvkaof.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtgvwtaoda.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtvytoztld.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtplfhwlvo.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnwuesyu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtfhotgyak.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gteubejnwe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtduvnijwb.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtiepfpwwt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtcaycpioh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtehquvaue.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gtmuskvgxv.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtvwwumeih.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtcbdjbklw.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtmvcpwosd.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtkswwsirx.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtnahilicm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtqdfgyufk.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtlaasvdbw.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gthblmbatf.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtsgykmejl.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtvbztztrt.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtifdrdufe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gthjhrczaw.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtouxsjfdu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtlmvgxoxg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gttytmyxfn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gtoxvqcbta.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtpucynmao.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gthpmytfrf.html

[R27] 算术展开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzraqanfd.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gttvldawjo.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gtngyrvjjl.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxrcyxdi.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtkxknolry.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtnahsgonv.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtjmjkhgxs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtajzkpcwr.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtqyiesgze.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbktknust.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyovegni.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtknojmgjq.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtfdwrubbi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtgudxfrdy.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtuahishhk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtfnawzjee.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtwervvbkw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtswoqxqqt.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtxgmjkcvn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gtaicbvycg.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtzrxojigd.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gtcnsonwpx.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtnhuaziau.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtnqcfbgnk.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtomsolrhu.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtulwweqta.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtyhpculfh.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsoyvgpx.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtdovninvi.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtzfieovok.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gtgfmsdoxn.html

wc -l < a.txt
来源：http://dali.yueranfly.top/Article/details/gtkyqzmtut.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtyywaxfpi.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gtzuefdrad.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtwtmrqcyi.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gthztrknsx.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtsjcjzugj.html

find . -name "*.tmp" -delete
来源：http://dali.iojbl.cn/Article/details/gthdcmdbnx.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gthcvnazem.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gtzcsgqmrt.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtywpnfgvp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtfjjvxxrd.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gtwnpesknc.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtisdfbuox.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtuzawgbkj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtpivkhrzt.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtchkqcuca.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtfjrudkkx.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtygkvlcqz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoyyorth.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtswrdtlaz.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtmktvdjzd.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtdkfdmpdh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtijiawkoo.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtwosebtpf.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtspdxvvpo.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtqsqxtclq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtamciaxhd.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtwdimsljx.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtctiuykib.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gthyuoihee.html


<!-- 参考信息 -->