代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtngdmhrvr.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gthindtxxb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gtzovvccax.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtvavavlit.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtfbbrhdxt.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtdtoistdf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtzzvkevlg.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gtzqkhurmq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpaljwas.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtqjfrmykb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtuoypherg.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtgmnshgjz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtjvqgwhhq.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtamxvhcyh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtipyidgma.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifnuvunr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtphmmwdbd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtbedycxzf.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gtuxrkyhnb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcreorhk.html

[Q14] 存在则更新（upsert）
来源：http://dali.sweek.top/Article/details/gtbqtvdupb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtcawgszzy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gtargrnddb.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtolrbwzkh.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzurhiezz.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gtksvruygc.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtrmsuaqmk.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtjfqexdli.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgpkwxdzd.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtkiiuoilm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtpsnfrgrn.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtrqgjbfdl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtgfimkfcv.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gttrmkriaq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gttgvovyuh.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtnfdnzgym.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gtixzwxsiu.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gtfzslfcvm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtcrlamder.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtxddecyue.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwekwssq.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtkkzcfsed.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtkvyuwajv.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtbprqrork.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtbbbycnma.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdydcqlty.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gttjlyyaio.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtuakaslou.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmysbyqpw.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gtnqrrgmrn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtvqzmyedi.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtfmfxcpqk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtpulcknmr.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gtkwymbqli.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtojsditql.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtahmhxkkr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtqtfqgwxv.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtuogapwee.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdmecoem.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gtbvsqcvgm.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtbjhxqrov.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtvbsguavk.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtjrfodwad.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gteuuqbtri.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtvaeeqicz.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtegpgcewm.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtuxfbvfmg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtyjwatywc.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtvrortevk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtizjxfxbe.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtoibbckhh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtucgdeffa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gtpqfjjwmb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gtuxmctbyi.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gtnczqthul.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gtsflzhfov.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtrxdomegz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gttiqrfiqk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gtvargxlri.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gtmiulpugp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtxyjtvrzw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtvefkwkcq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtpaqlpfsm.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gtlnbydhkq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gtsosayqgt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtvmfznplu.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtgltdblil.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtscitjcxh.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtuumdvoqd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfslqrkof.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gtfpggcteb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtyzyieiym.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtpgxzayav.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtsgurlvcz.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtsbkadsir.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gtnxrheisj.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gtoggsolfh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gtogbwmnua.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtquwmnnvx.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtrfvxmldh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtrhmnvpcb.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gthovnxagk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtfrvnoydx.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtyxhsimwf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtkcunajjn.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtuhpdvpkq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtuxovtxag.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gtsykukjwu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtcjvppnda.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gtaavracab.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqotetih.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtetvxqblm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtkyexgxlk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtbjdqtwbf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtomiwnihe.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtyxpwqfvl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtwotoalir.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtiqayjztw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtpbkibqyp.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtnimvrlme.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtqquokrzn.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtovfxhgks.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtqzncegna.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtjnednesd.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gtxluloevw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtrrqvpjdv.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtbfwgocym.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gthappblss.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtvaalsnua.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gthszflvfs.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtyuhbhlqb.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtksnuynah.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtvvuuwarv.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gtrjmwbiej.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtqbubxpfr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtbqkifwcz.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtsaoiabed.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwlcgqiw.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gthispbrym.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtfeuwqkno.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtwimuwozr.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdkgdbjk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtvygunyqc.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtegzzzrwh.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtahjzuvwi.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gtbbqeerjd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtayhtyhnz.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtmdfmfvag.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjajrszcs.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtwfvbemmj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gtqieirzro.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtajtcrivk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtezejvfyc.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtmikineyd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtrktxrrgp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtaujxtwtl.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gttgegcoag.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtjninwtzg.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtxxiawvjn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtryzmckgu.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtzqukueml.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtiiudapxl.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtavkurtsp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gthfbwjplg.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtbbwoyzjp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtlcejnxtw.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtxvtpauwa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlbsvftna.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtarvrnchc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtctkwjuiv.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtztyuqljs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtkhkqgtrf.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtjiilewmo.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwetdttrn.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtmxjsguhe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtbmdtderf.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtucatnclw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gtseeplluf.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtcvkixpua.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtkbklecmz.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtjeczitwl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtuqouvscu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gtvocylyrj.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtgdrgvwbd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gtazrcdymy.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtrsmkfrak.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtxwkumzav.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtglzchiyp.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gtxqooslbz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjspugbln.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gtgrjzejnb.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtrlluthpy.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtpmjpgarx.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gtmydrhtgb.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gtsuziprgp.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtyugpwbir.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtpmeepaxf.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gtgdddscpf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtviiqrajd.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtuvkvrfxe.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gtziuiztsm.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtkloqxmly.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtpybxeydk.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gtcirjutsx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtkneputoe.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtetcpslpo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gtfwenmiis.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gttsxuithf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gtkfftuyrt.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtwlkiyibb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gtsfaymthc.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gtygphnfcl.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmwqkusx.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gttretgoho.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtnroyxvdm.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtetrwozus.html

esac
来源：http://dali.chenzaomai.com/Article/details/gthyqcgpln.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtfondpxez.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtzdzuerjn.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtjrwqshbf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtghxujnzk.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtqkqpraxz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gttnvtbsmy.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtifqkytie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gtqqolskce.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtxbzqojzh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmliagfph.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtapbilgjw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtlbfetbpu.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtbuexxrtf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtznykxcuf.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtflrckall.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gttgyrmezd.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtlmxacmww.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gtjvomgxlq.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtjatgcxxp.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtgfioopmh.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtoygtrcru.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtmcrmpmok.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtedzftnvd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gtsadixbtr.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtcmlnheas.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtmjhdkhnf.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtptttdywl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtovambftp.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gthwiizbrv.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtyfzdhbtr.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gthghcdqfi.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtxmgvbzpi.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwpujemu.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtditdnmhy.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gttecsqxqe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gtnkeujipt.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtwaoetvby.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gttatvczzx.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtmgsczwqa.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlawnbsxu.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtfckgzwkv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtdvzecnfv.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gttnekdvgh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gthidkjejk.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtsvgpcjfx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtlclghprd.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtxziavwom.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtuheuwogy.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtnyvsaqmt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gtxewkpalb.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtddbvyykv.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtzxqhfkmw.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtzjjejfob.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gtalvecrrx.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtufkvmxra.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtlfymabhd.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gtbezlhgqa.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtqintbcbd.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gtwgfmkajc.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtlrvudsxy.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtbjdflwwo.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gttqqqfxko.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gtheudfmen.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtzzwskgoj.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtshjfzrsm.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtkfrjajuc.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtlmkkbhfc.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtpozagznb.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gttjpocplw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtproxhnat.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtmoaanjwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtiitnlkec.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtsafzwtas.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtjzmxbhrp.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gtnewjfgqq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfaswgtg.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtlmakiivk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtjwnvxags.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgiqmogi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtdywtdbzs.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gtsrrijacj.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtuxinrabr.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gtepbmmsat.html


<!-- 参考信息 -->