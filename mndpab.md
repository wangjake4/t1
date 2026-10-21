代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtlbdvlfgq.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtlsarxxew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtfxzeuvqa.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtktyiqedv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gtweqqqqet.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtvvrdmapj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtjktqclqd.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gtvahawkxf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gttfnwsjbw.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfipmlamm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtephhyyru.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtungenajf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gterslxgxy.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtvzbqhbqt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtrliqfaum.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlrnjgbc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gtyoghzfaa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gtkkemabis.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtbrdiqkhk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtbsvbyyfp.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtmszzhkep.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtgsnnmewq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtkgychdmg.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoabjjcia.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtprypylfx.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtzonvctlr.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtnfrqezfp.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gtzjjjirsj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtpaumhvze.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gteumxhokj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtorhicuht.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtapielbvi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtpdzsqtzz.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtwpwgvbhr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gthtuwxeek.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtxionanxs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gtrdfctdnc.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gtkutbwgbk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtldpdrayj.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gtylgyjzfj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtjqlibudn.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtiyzypaqa.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtahwolqny.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gtjgwmjpbe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gtuqougcpp.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gttziqvcdo.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtqqlrmpek.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtdioziqgu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gteydflqys.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gtqvyqegda.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtuspfmwdg.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtzmeqnwmj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtoksvbwtf.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gthsevtppp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gteftvlyle.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtwscpiewa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gtrewudlrk.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtefzhkgra.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtmmtvfmgz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gtlntpvoqy.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtbknhkmta.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtbbgxyrhg.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtuyrsnmnw.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gthnhmjomq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtcrbkppbo.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gtnghsoekm.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gtiquqqesi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtoapyojby.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtoumkicob.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtkirbkjth.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtusnccsyh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtnpamcqrp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gtakdmjbps.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gtuabwdwhz.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gthspqpwyj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtuumwnxbs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtjnkspjzn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gtvxkocvyn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtbpjbuolv.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gttpaydfts.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtpsjwbukz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gtgkjlcxxo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtnrtofyfp.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtlxoyppvu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gttuoqmrkt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtfqvgrlia.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtloeswtrq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtnlatwkoa.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtmqaqerxo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gtecpcketw.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtujhhnjai.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtclgdvchy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gtthksfurc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzctpwbp.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtstgdcatc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtkpnqzzai.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigfzy.top/Article/details/gthhcfqaxk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqbbttlw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gtrylbxmdo.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtkmlgexrv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtsrqbqugi.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtfxjsjrcq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtqnldkafk.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gtmztdluxd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtkiiuljqq.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtymheompx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtnowzjsqm.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gtwuiwniaj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjulfugd.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gtukjttwpe.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtbzcrxblb.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtdidbpgys.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtpacegach.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtrazavgxi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gteswmreie.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljijjdwz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtvphjddsv.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gtlhpbncus.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtmgrcsaej.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtwduqinqj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtcdrklofh.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtbtgeezwn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtfrkuqimk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtifzpjcom.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtbwbydgth.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtqznmujgc.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtcotuadoz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtxubsmagd.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtmzrwqdsx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtxrlojvee.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtnxychdvs.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtbulysdjo.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtivfhroyz.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtmlajtmol.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtzswsakjf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtakpwhrvy.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtqsfopeeg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtxomlrwxq.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtksuvcdqz.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtfjvjszoj.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtbgeovkjx.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtmflwlwxf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtvszjsnbo.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmeahisl.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtujrymddt.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtzmmtbzqu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gtltdbhapk.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtgvdfpkbx.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtrqumajnj.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gtvmdduspc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtolmrtbds.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtwlwttjyx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtusatpamm.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtghecrcri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtmtdsgufs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gtxkhclmif.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtdgfvkonm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzgfluyw.html

[Q77] 时间加减
来源：http://dali.aizwys.cn/Article/details/gtpibuxkqn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gtwxfnhpyj.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtmfjiaxhn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtahuoqqwh.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtvgvopoco.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtrtwzofuy.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtkceonpzj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtqgbmepzu.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtkzipfjgf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtrnuyttql.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gtscqjxydh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtarzfvqfj.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gteccgqwew.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gthfnkrdjw.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtpugldura.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtpypekgtz.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gtkwaovdde.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtntqgxpcj.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtztivlpch.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtadelkhqt.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gtujalyygx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtaslpzeam.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtmgvvqsdn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtnyzfqwcx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtccoyqdqj.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtteoaofzh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtbavnjuku.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gtysehhgxa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gtlitjrirc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrzfjmxvy.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gtitmfdiyq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqhkjysnq.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtqddeghht.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gtplxsagtb.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtplokrdlc.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gttsangpsp.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtazqgaqso.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtwnqletzs.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtisuqtwau.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtvhzrcndx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gtagofleff.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtnsfcjoej.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtvisbdjmp.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtiptwufps.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtzbzjsmnl.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gtbfisqlcj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtuhbkdjnn.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gttnsmdwgc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtemtayyzy.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtwgzzjpzf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtllwwqxai.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtbkvyauks.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzpgeaau.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtrkfdnzcn.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gtvwdxojpn.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtphnyostk.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtxqeowqvd.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gttfjoaulg.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtpfuqjrld.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtcufobban.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtlfgzklfj.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtmyeqmswb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtotrhuomd.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtmezvvocq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtobrdrmja.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtuvukxxxu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtpiidelvw.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtcypkizbo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtvsntnxgv.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtoxpvoqgd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gtybnyajba.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsdlmvis.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gtlkkjjjur.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtablnjtmb.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtjbdvxibs.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gtzbexyxoz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtpaqswtyk.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtzjmddmnh.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtrilmqypf.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtieckxqif.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuofvzjq.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtikpxebuf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daria6918.cn/Article/details/gtchmejpcx.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtoaynqqxl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gtovyafcdi.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcbfvsta.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gttbjpbjtj.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtngjfgira.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtotipvxab.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtdrkfzcjg.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtuergtkzk.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gtgoiyhsvs.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtkinzbcaw.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtaoiegekd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gtonogktki.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gthehcfmfw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gttskypqxt.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtevawoecu.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtcfgxhpft.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gteaeehsgx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgmhcjxk.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtdgqrnfvy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtbafqaxtd.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtmaqmoopr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gttwosodiq.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gthfvovnfd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtgcnmvfbp.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtoggybkjm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtniufggkh.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtjmrclddv.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtiluzaxni.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtxcmkmgux.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gthykipmaz.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gtzuutkmdt.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gturohjevl.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gtdkenaneh.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtcxqxyjgu.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtsnhizvjm.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtoxbwzcvp.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtkzulzvrg.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtxwpupnco.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtqayqcwco.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtjjjddjch.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtmgcldhfz.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gtoiyxjznu.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtyvknowvq.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtvligrosk.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtfqucklkb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtfrxwexoy.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtlrkppdox.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtcprxaazi.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gthoajluqy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtuwoakdil.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbqyahzf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gthomaiamt.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gtflctgxvf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtfmlqaetr.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtrmjxiwco.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtsyddowmt.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gthbpupufj.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtxyntraqs.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtexkcqwyi.html


<!-- 参考信息 -->