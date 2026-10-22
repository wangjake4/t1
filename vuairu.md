代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gtgqahmyhr.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoszejlr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtighxaeqc.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gttetvkxwn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtgvnakfmr.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gtyihilpki.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtswhcdvvp.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtzkrpqpij.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtamlnbmpt.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtppymbxqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gthjemieqf.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gtzyboustt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtwfnppzva.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gtqtmlidyr.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtwowsowtd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtaauhzmdr.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtxsijyqiv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gttiuamlyx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtesdehxbs.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gtncorinlj.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrbbyxtua.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtckltyiik.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtyvglcqbd.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtuurcdjap.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhmwuhli.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtzuqildim.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtnckvhpqu.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtilrioeuv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtbucyyplh.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gtcukpgixq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gttdxdxaxp.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtzjugpyje.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gtqcqfcffy.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gttsaatati.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtdhcbfmpu.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtgqmowpom.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtgnireize.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtjdggxpqu.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gttppjkikm.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gthqxrgcwu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gtrvtbdzod.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwmtzcmk.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtaalgqkbu.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtwpgkqyvj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gtqxomrtoy.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcsekuqb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtimnudomz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtkmobsmmf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdygofyvj.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyyjkkzr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtbqaqkrev.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtllkzxeys.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtjqytmiog.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gthqbtbpif.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtovwgoipx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gttecbzhyg.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtoheztuhe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtgytjkozw.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtuvrnwcqt.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtphmyzrqc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtiyerusic.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtaggscceo.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtrberoxxd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtwlitawzt.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gtfzkrpqtu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtagepjwwa.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtxhcbeytf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gtghoxhemt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gttzlvtesg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtwuflpbmh.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gtynsekymk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtdarwmouo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtnfnwqdxd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gtivcrsbzw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gaohongyu789.top/Article/details/gtxaijaity.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtotffcivh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gtytxlzwqx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtipmxxavu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gtaghwivoo.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gtbgfsobjx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtngmtaiuk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtqzupdmel.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtfatkfo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtudtkrphg.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtyguqxmqt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtlkillswn.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtutthctso.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtlwlcwraq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtmvppzzwu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtobzgnebn.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtyptneyno.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsutweagf.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gtkfogwiiy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gthwscypdx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtdwdkffky.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtnfeiigvx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujuhqipi.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtgtsoilaf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtigibyqhw.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhvlxwrk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtnbypkecz.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtylbfbjxz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtozvaznik.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgosbdwlm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtbjlxasas.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gtdtkorube.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtynmxsipn.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtydaxiwvg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtyjgjscan.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gtrgxrbluf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtxmuxdhoi.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gtqiwxctsf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gtgioovxvg.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gthlrpsgwf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtwdsmufvt.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtryrozhrh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtmicnncav.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtovvkcqko.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtetphbntx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtfxijxvyt.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtkgyleslp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtnzerveft.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtqpqboupn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gthhvpotjz.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gteommqixn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hongshengwenyu.top/Article/details/gtldibngjy.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtotymslzq.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjutmugoh.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtpvqzqylt.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gttsupcwpv.html

[Q66] 行锁查询
来源：http://dali.xuetiantiany.cn/Article/details/gtdnhahnss.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtephtfhcc.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtkqoykovt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gtucvsnrdd.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtsfyhikrj.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtebonobqh.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtgtwjkonn.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtlyrktwzm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gthvunhebd.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtpedztqex.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtskvbndmq.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtuerqvdzy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gtgamonywn.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gttlnsdyeg.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtsuypulgr.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gtjtzlbhud.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmovoufa.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtwlkngqzi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtbvasolxd.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gterykaixp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtyqbossdi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtnmbszapl.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtnikjgigf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtfwrokbxx.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtjowcbhse.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gthehbtccd.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtuydfhpvw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gtdailpkyb.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtynliwtnz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtdmrbgemb.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gttkfiyglp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtpfptniak.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtucbodrhc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtjyxvzszm.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtrgndmbzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenobdgnv.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtrolnijvo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtfkkmdiwe.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gtwvgvhqzq.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtnuiezjew.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gtzughydpe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtagmvdpnc.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtfdodtvut.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtvitqnmth.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gtfyhcnkxw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtmidrqzfv.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtftjdqzpz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtkgkmkusi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtgrnzgvfi.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtzqhbyngx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtqjqsigko.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtxjuovcfo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtalexwmdm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbwcmtavz.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gtfcahmpzq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvbuxfker.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gteuvqjqxn.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtrstnjtrf.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtzdkillwq.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtbaltdtug.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtrfvzqdwk.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtcrgvynrx.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtrmwrxzgz.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtsnlozoko.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtuqgphmvc.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtbafokfjz.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtelifhtpj.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtijfamwur.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtazohhtpc.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gtcvthheef.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gtrofnyicr.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtcrccnife.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtownegrbx.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtrjxkoeft.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gtvryvqlyv.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyuxfzqb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gtromknfgk.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gthscsinln.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtxnjibaoo.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqwpczvq.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gthqrveqdp.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtsmfypkig.html

esac
来源：http://dali.yj20258.top/Article/details/gtddjldlzt.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqkryvqod.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtfrvgevhn.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtdjntjzyl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtytgdxwri.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtvcdehmuv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtuiaybfun.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtjstcqron.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtqbvuwrxo.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtvixckepl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtfkthlots.html

[R17] 数组定义与取值
来源：http://dali.zhixingplan.top/Article/details/gtorwuviou.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtlvquprkl.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtoqfrjcam.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtiftceusd.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtaocmkblm.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gtecxxkdox.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gtillxqxyi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtmkgiozql.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtjrpqcbxb.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtrrupbwva.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtbdbokzkm.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gttpqejvqn.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gthxnqywzd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtoiiscfsj.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtrukuabrt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtdabumsho.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtdppmvlqz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtgtzivxli.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gtbvmtdwbm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gtxyghkzyw.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtwqjenwcs.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtywaiylak.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtpurykexq.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtdwyhyuiu.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtzqomccmh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtoyfjuvhv.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtwikdxmth.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtdwynicmp.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtoyvninbc.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtmzkdzmjx.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtqawrxtig.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtbhtkerva.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtspxivbtr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gttkgyoxuy.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtywahjkst.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtzpbzazfl.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtijqkivtk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtvahmanhn.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gteuwghplk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtjvjrjhfr.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjieihsbt.html

files=$(ls -1)
来源：http://dali.jyoumei.cn/Article/details/gtqzowkdyk.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtnfgnhqyk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugihakcf.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gthlzjofhr.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtrodtjvsx.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtmltfcoiz.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtuelxjpnt.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gttekuctqs.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtvyrwdxxs.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gtoixjvdxe.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtxqshxuvx.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtsfulnzgo.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtcjunqtsp.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtyexobukh.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtdqcqhwhn.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtolbnsguv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gtbrsqmzjj.html

[R46] 递归替换文件内容
来源：http://dali.andypj.xyz/Article/details/gtiesivxti.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gtxwejqjbj.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtglehwcuk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gthxalpuxw.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gtpgoigqyz.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtrhqcrcux.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtitkgegvd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtbnnmxmsa.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtyxhchbbu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtveilpgbt.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtydcizopk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtbxaqlfmu.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtgkympiat.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gtwurrzqsb.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtbzjbjzsn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtpaqmsdaw.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtwbuuoaqs.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gtngkqhszs.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtntsvahkt.html


<!-- 参考信息 -->