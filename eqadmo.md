代发 wailian999

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqzgxspo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtfzwacnww.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtunroflmn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gtieojesda.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gtircdvpws.html

);
来源：http://dali.havefunace.top/Article/details/gtxflpufco.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtfvomhiwf.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gtthohztvq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gthpjcoihr.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtncvpkeyy.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gtrqeqorcr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtneuomyve.html

);
来源：http://dali.xuanzx.com/Article/details/gtgzxdwbvs.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gtjootvguh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gttpnlxegf.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtoevnmdco.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gtgskrynia.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gttncqiuar.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtdzjttbgi.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtbzxckzwf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gtkflcjxbq.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtviweyqug.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtcvouevxu.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gttzpscinv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtkdvkbwkc.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtyyaxojcb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtkivnujql.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gtyvgvsypr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gtmvndnemx.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtejtvbvrj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmpxzdqo.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtvnrysjwx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtjzfymdwa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gtjhcdemgr.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtnswumhvv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtnejfhqcb.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gtipehfuuu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtaccfyzab.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gthqqyocfg.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtefxnootb.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gttgirurnw.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtezxlyefw.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtpctympmb.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtwnolxygj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtgvgcttee.html

[Q18] 模糊匹配
来源：http://dali.dashuyun.cn/Article/details/gtosfpazfr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtkzklprkp.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtguridilh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtlixmkcav.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gtgfovubck.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gtgiprgvam.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneqvcaxw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtptotzlcl.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtmevlivfn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtgoevsdno.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtjfubzehx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtdcpyvtzu.html

[Q24] 去重
来源：http://dali.0kj1m.cn/Article/details/gtpmrhwqlj.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gteaocwhgw.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gtbafzolha.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gtaobzvtji.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gtvfifnezc.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtliuxcezt.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gtbolswmfi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzfppmmpo.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtlqilrdmv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtarbozzyw.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtoadrgqbp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtvnfurdsh.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gthvwvkrlx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtvmjpwbji.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtitfszsas.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtzsvdfhwq.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtfqtlnusg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtejaipxbf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtioplifkj.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtplbzepyg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtjjpawnpq.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gtjfcqvtfo.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtlnjizbje.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtianlznix.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtfgrvyrqe.html

[Q35] 内连接
来源：http://dali.zycfv.cn/Article/details/gtugwakkqf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtgfnablgq.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawdeehzo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtdzmnwwie.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtjrtitrga.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyghqfobg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtcqwkcbav.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtqehxanws.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtvgioyghf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gthxixstro.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gtfeoeffjs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtcbsvakyw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gtswsttvlq.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gthzugjqyf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gttzbgdegz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtqihfboyk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gtqrcaphbx.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdhlfftj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtqyftcpqp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gtldmqkwvz.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gtuypagpbv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtiqiiuzrn.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gttvagskcm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtlbpjrqtw.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtasotkznp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgxaoyry.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtpwpyeatk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtexiqncxd.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtjkgxntnx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtrbmgxjau.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaozviisk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtudpfpccy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtzbsvofta.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gtnkamkfky.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtfsumylmr.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtdsliccgz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtqguzjghk.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtyotsxzzb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtixgslxxf.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtpygurzmv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtxuisnpnw.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtrjffdayd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtrollftjv.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gtqnsofwgj.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtufhhaghr.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtuwxnoomh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtbppkuoic.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtqwiqpayy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtdiaynpfj.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxjyshpc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtgqrnmsfa.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gthvrsnoiq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtqjxqdvzi.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtmpptxlqz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtxexkdfjc.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gteqrhuduj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtqmkzezzm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtmvnvkxtq.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gteqjronbz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtxrhnrkmb.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtjquwxtwe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtkpijxjwk.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gtzslircej.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtrtznqrtl.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtrsemiolh.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtybftosex.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtbfuawsyc.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gtinpzfduh.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gttwheglbs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gtrnyknjxe.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtqaukydfb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gttvjyrsso.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtdxjkcjjw.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtlznrmdfl.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gttmqigtug.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtxtixngyt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtljbrwllb.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtvgdqbvcd.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtpmznxbmh.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmezcuht.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtlbusftwy.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtmpmpthxq.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtbdsklswz.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtltmiyfid.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtecrnqdbi.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtxborsirt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtteqldyhw.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtwibdytuu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtphuxxgla.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gtwkytxuss.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtywkmmuaa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosxhijmq.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gthjpjxyhm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtfwrhhmdt.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxtdtcwy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtkorsvaot.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gtfnalbchg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gtxwaisvqz.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gtimgrzxhu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtlbqltnvw.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtypbinsvs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtmfyfbxcr.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtlvninobc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtcqejwksb.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtbxtulsfu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gteercrpwb.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtxlsdzjuk.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtpoxshjxf.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gthpwbkxhh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gtbeayhjlz.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gtyfpvbuoy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gtujlfrikb.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gtqwkjldfz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtvpxibzbj.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtfibpwxip.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gtjpaijipb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtlkdnbkub.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gtolnluknu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtuymhjglh.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtiupacmfa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtbtvfemey.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdorfphpm.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gteiylntmx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgmognhqu.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gttheqjhno.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtzqcxmqzh.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtxuozhsze.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gthvdnhcfv.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtbadlukqd.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtpvpqiqcy.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtjdtybknv.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtzoaxdvnz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtjkofujix.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtzwxenovn.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gttvrfpfie.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtwydjboen.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtysorkdhn.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtlielasag.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gtbxundsou.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtltffojmv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gtcxdirmfa.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtnsbuvked.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gttcnkowlf.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtrtodtidr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpzhmgbw.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtntrinhzn.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtmizcefct.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtgaxeknox.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gtfqgbpafd.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruavovgo.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtvugczwvm.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtuvkyugro.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtueisoajy.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtjlqrsanr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffhnwxpt.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtvobceole.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtinngcbfh.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gtvtwgpdnu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtcredmnhf.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtjkildkjn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtlfjxviju.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtykaicaqg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtteexjvcy.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gtizgaiaie.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtmwkljnyt.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtdvmtjvow.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtlqdlctnn.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtyiikrtxw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gtuuwyxnfh.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gthoupsxjb.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtfsclsjxo.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtcyakgrwl.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gttkcrqrnn.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtqvedhyuv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtnxkxsaut.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtnlhcfzam.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtyaikuctr.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gtyayizyaz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtxkdnllrj.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtzsmyynyc.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtdthcfenj.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtpfofnhli.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gtpsjwtsbv.html

[R28] 浮点运算
来源：http://dali.xinyue.icu/Article/details/gtxtfyzasx.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gtlinpwxaz.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtimpgtewp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gttsdnwqli.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtkjrjaoak.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gtsuerpogu.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtcearsrxg.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtwljxppvt.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtejiocbfs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtjalszwoj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklcqrhrs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtovzhvtti.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtzbontmsp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtakrjtxsi.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtugevgaoa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gteadgkbwi.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gthaitezak.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtebhvqsge.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtzbqylgmf.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtycaqlrzc.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gtodlboryp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gtbibbykfq.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtgezouqao.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtdphlakcs.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gtbfwtmqzc.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gtjyyzjgkc.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtjqmjhmzt.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtsyqlzfnl.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gtcxlvtflq.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtjnhdplaa.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtbhrkzrub.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtfqphjnzh.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gtaeuhvmic.html

find . -mtime -7 -type f
来源：http://dali.jinqigfzy.top/Article/details/gtnwuqhijd.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyhgqvma.html


<!-- 参考信息 -->