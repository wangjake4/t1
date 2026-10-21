代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtjqqdqyuj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtyqrltxfn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtwcmaoomr.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtwjawkhky.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gtowxunqed.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtegzamwud.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gtmsuoldsn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtloajzwkm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtxcbvjdct.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtkjfsafcn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gtfzynernr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtvqvbvjkj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtazfjbcxu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtarkiczmu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcwvburvl.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtoxzvmtjf.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gtsouliwim.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtdkihwlfs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtgxihtdhv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtemmbezyc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtciglnptg.html

);
来源：http://dali.cqqwz.cn/Article/details/gtiiaqteup.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtipzgucvf.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gtqanubsvq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaldtres.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtamonkikz.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtbhounodc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gtddypzvnc.html

);
来源：http://dali.dianchejie.cn/Article/details/gtwdislepr.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gttzrqqfqs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gtyhdfgczj.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gtfoqcmcdh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtkydlkzgu.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gtsamktbfz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtotekjucn.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtxscfhjdc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtqgzfpixh.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtjhiiglzi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtygwjevtx.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtafasmvpc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtzxjeheyu.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtqboltihp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtvpvspalw.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gthcfddstl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtmrfpohya.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gtuhrvilov.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtuhdqbask.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiyhdqqc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtokxkbidg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtxjntycng.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtihsnxkig.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.havefunace.top/Article/details/gtrihozxrl.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtbwbqpihe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtkieawphi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gttgnmtbes.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtlsvrhrfg.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtdeatcubt.html

[Q16] 查询指定列
来源：http://dali.c1oappe.top/Article/details/gtqbevucnx.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gtzlthffxi.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gttymogyfc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gthsruzxlt.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtxoxolhfv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gtmeaelmln.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtimcwwinc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtqqfuudgq.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtglbhhwjn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtmmgdohdj.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gtoxpkaydq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtaupxcenm.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gthdazzfok.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtwdrkuxnc.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtiytncnmp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gtrluyxush.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gtpvjrqogs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtxscwqzfc.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtbghueoik.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gtnfhfolyl.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtdpvdkqoa.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtxsdhgcjn.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gtdsvjcfzl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtnfpgtnog.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gttztfnlzv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtloydtcur.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtoqqytezz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtwuowfgqh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtzxbuqdnr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtcbiymwod.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtzuaqwhhd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtswxgwefg.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtqjuzncqx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gttsdxhxhg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtahspdbcb.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gtpllvwgki.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcaijnxb.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtprdcuosn.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gtaehnjdpv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gtxdhdkxmn.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gthuvscygl.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtalkrxbuv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtwkdhiujf.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtcqibeptf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtmvjltujf.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gttmglzgfj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtzzktejky.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gttprjtkai.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtdhknoldu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtufyezost.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtwsugmgbc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtatmbbedt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtvmscmnuh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gtdofmaabi.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtzonznipo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtwsuojdsh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtztainvqu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtvugchxwu.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtmgnormfp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtnwgxqshh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtbqkppgli.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gtsarwmjzb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtvmjalnuv.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtcpkwrcrf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gtrxmqrfiv.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtexpuiydx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtfdokqhek.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtngwwjfjh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtdytkmbsk.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gthmtipxxm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtmvwsqufl.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtzcusnuue.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gtzaiefjiw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtnuwaikdl.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtxbkdakqj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtebnvvdof.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtywysvadd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtpclqworo.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gtxhrqsyrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gtuinmmrcq.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtdopobhgx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtcpvxmmlq.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtfjfvslon.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gttacmjmuq.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtpbilyjei.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gtngwgwaaq.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtukkvnqea.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtideubpqm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtvopoaohh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtvjsnbyfi.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gtlwwusvdd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtnmxsiohf.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtctetwfmk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthssfcrqh.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtsltuevlx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtzxqddarj.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gttdeeqjad.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtgjchapyy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtlkvtqffd.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzoynoscl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtbroyqlqd.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gthemtwvgt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtkqeghfti.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtmjedzxtv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gtyvidzmgs.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtckkzmgby.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtrasotbib.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtwojwobfa.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gtoyocvnwz.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtnscsbzqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtynkaivcv.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtyocfcxmr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtdfctqdws.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtmbqxnrxp.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtjturliaz.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gtyvoymbjj.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtpnoqexpc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtrkhrgkjt.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtmofqobdt.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtikgatrss.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtzdhgdrwx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gtyhqewfjv.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtdbmpdlkl.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtolmiokwn.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtenbubghl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtdqcjzozk.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqssmloz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssiuryio.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtmwwdybds.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtdmrdielz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gtoynuifzo.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gthzkalvqu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtuenmmxlb.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gtopoifubd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtjaiewqiz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtggedpykz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtucxmyvmd.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtpgngeeep.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiuswpem.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtilaedptf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtadmswghs.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtmkgtjivo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtrnfzagtz.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gtkdhdvlfv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtwexetfzu.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtiixhhccx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtbqdstmyq.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtzizgzbep.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtwxzxgxck.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzdrkyge.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtvmpvatem.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvazmepw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtshhmnhoh.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gtrdtsnbwp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gtekxnjcwc.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gtrnlwmvpa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gtttueydaa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtdbtalaqk.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gtmpsxkntf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtedqgmjhv.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtywkdjjrk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtnetetznp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfgwispsm.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtrronvdmx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnksllcjf.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gthovewqrz.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gttdkwrktl.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gtdwukhrdh.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gtsqoluxzv.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gtrrfqsqdz.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqadvijsi.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtzohndmnp.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtnbhoxsio.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtjbzfetwu.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtlohatvvy.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtdkojlnuu.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtxnlaiift.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtnwfdeess.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtznqawqpa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtyjgrmbkl.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtymzftwkh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtmyixiplv.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtjsowdwxz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtjgamfgzu.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtrpwfnymo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtueiwoyrd.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtzpgabaiw.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtbmpmqeju.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtbnqkpdof.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtyoqiqejs.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtsmhrhacy.html

esac
来源：http://dali.yj202588.top/Article/details/gtiigfoehj.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtthbjbcco.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtepeflonn.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlnpvdox.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtyadflvaw.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplgvjjxc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtaiccylig.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtlwrmtkwx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtrippndtt.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhgfryhq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulwnszhx.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gtoigqvryn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gtyacococx.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtaarvhsbe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyvyxwzj.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtkhlrngmu.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtmtozblef.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gtexmqrelc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gtfiqkcumb.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gtlmmnonjd.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtjkdxdpef.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtyeuvuqpb.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtcynokvet.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtdpeouqoh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtjomsjfut.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtleeydujk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gtzubgidmf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtmzlrrcgy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtjznlnrnp.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtwrbiaqru.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gtodwehqnt.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gtnpcspeyq.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtsigpxgfn.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtypaupszv.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gtmofodefc.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtdprutnrk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtmrcxnmrx.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtyjuhgioi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtrlepvyry.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtqbxptzcs.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gtjgwkdubs.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtmowdgklo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtamwjtfkv.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtkkptqlxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtpvskpwbp.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gtkokqhors.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtdqcgvift.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gtnmcuiulh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtrsiigors.html

[R36] 并发执行多个任务
来源：http://dali.zhiwuduotai.top/Article/details/gtpkyeeijn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtueuggvlr.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtubsjgqjv.html


<!-- 参考信息 -->