代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtbbwzajbr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtrrhhiuky.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtmimszwyf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtvuwnzijs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvlqxfqw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gttrzogrip.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdryephz.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtzeiehqli.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtljnfqudf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtlavlpbnr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gttxfrjkem.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtjfmmsesh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gttodivycp.html

);
来源：http://dali.jqgfzy.top/Article/details/gtaxxmdshf.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtzmjgmuog.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtawsbzqto.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtkccxmjiq.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtgdjikzdr.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtqkdbzkqz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gtrhcxwviy.html

);
来源：http://dali.hnqzz.top/Article/details/gtgsnyjavt.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtreqvoowd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtjqxspjnl.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gtnwlodmno.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtuvierayw.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gtlmegobbh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiwqorrp.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gtqcdaalvx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtwbfblgsn.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtkbdvbjab.html

DROP TABLE IF EXISTS orders;
来源：http://dali.iojbl.cn/Article/details/gtnvkrjpxc.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthdufhza.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtofxoqujn.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gthqyarpns.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtdujwlvhm.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtfrrtpviy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtsihtujtz.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtudxvzxso.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtuhskbdqx.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtkandyokw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtvkexxoad.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gthuwvobsh.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtpmnzitjq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtlknruaad.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtvuluteww.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gtmmkiivow.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtkeihadyo.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtgnjcwlsm.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtsqwjegmw.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtbpfcpqxk.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdbjeofrx.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtpyelbxof.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtzlmvzkda.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaagjsyqd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtocuwkkco.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtdzsmstka.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gtzacxlbic.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gtvaununnj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtqqghfyyf.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gtoxfdtdwr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjoddgkga.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gtzaqqtpem.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtawduwlax.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gtjqvbeota.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtdptelgfa.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtjffcksby.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtwwodxeyn.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gtihgxhtng.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtofuxvyyp.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gticptexsr.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvlwdlcpq.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtetnsybkx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtdaiqdnvg.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtenwzaovc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtnlmcbisz.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtykdoxvlp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtldgdjybn.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtgcxonrlt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtfqezsxba.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtqhvgrgau.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtdlvhqldp.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtymmreuiq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtmrkriwqg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gttuldnqbv.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqpqycnu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtkjwctceh.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gtoxtewchr.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gtdnttbokh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gtzaxgmihl.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtsnbakzrp.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtvpxzhcqw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtexafyfnt.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gtkcgkjkhl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtxnkbrang.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gtimcqqxci.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtheytzdik.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtgsvziykf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtasbtrurz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gtuewrwxzp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtscooedod.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtazyhuvmn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtwsbotfnx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtxondeuzw.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtqlpxnmft.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gtqwlaruoe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gtoxsbujma.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtxzjnnehz.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gtmhknfpmv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtigdvuyts.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gtpapsvpmk.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gteqesfxfc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtzyybcxrb.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gtzcrviebd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtzbqmfadl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtcctzrjkg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtggfbjbap.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtvbbwetpw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtuxudvnqu.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtpuekcfjg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gtrwxpiudr.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gtlwnezdwh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtsxkwurij.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtijdskuir.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtajcegwij.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtplmtbmrc.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtxmwzjdqe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtczwzqjum.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtirabswcq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjhnypvu.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gtqagzlcmj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtegcfiobc.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoqvliip.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtrmdoilpj.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gtisfrlwos.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtmssgdfzi.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gtucbsfbmm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtswofksjz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtbvcoqcps.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtjvpqkgxs.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gtvfpgvsmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gtzqcedeae.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtvyxiknzi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtzjxhpwir.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gtnakyuwxo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtqfugvskh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtnbvzwifc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gtqhhklxce.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtlmatqjel.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gtmthuqeoq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtuuydqpfs.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtrkpryuko.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtvthelzgp.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gtdcebnfkh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtmxokrbom.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gtzljnevyq.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtzmlnqaak.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtbmfpkrmy.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gtjejdbalb.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtdvbzvvww.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtzyfosxcd.html

[Q67] 设置隔离级别
来源：http://dali.jianghu66.top/Article/details/gtvftwvzpk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gtmfhydird.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqiemrxu.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtngybagvo.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtezhsictp.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gtnwifdxqf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtkshoonav.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtvlrbfpsc.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gttotievds.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtbdedknom.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtcvrhefva.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtmxvspanc.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtocngsfuy.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gtlgdbswpz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtbohwoqrp.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gthxowqzio.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtgwfdzldb.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtuyoxgmot.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtnuvbqtit.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gtwxblhocf.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtljyosyxc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gtjqsqlnlf.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gtkuiettfq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gtxkoqtvam.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gtdgamprxs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gtanseqsjq.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtdibbxmgj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gtqufmzzkq.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gtkogxcwev.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gteyjhymsr.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtdgseqbal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtcdnilwwu.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gteoomcdrm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtdudqbglf.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtpdbvhvww.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtlpyqtrip.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtgudtelqe.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmdxhayuj.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtxlpzhsyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gtyupkrchd.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gtstukuonc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gthbzyclnb.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gthxuzficj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtcdgojrit.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtdifbmozx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtqqntdtrd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtrvldkctn.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtlnvmiiqb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtqwtjndzo.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtlgoiixuv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtnevsvgzd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqerexwjw.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtspdifsez.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgkqwvnye.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtmabdbtur.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gttuhiaent.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gtpffenzwp.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtntykfkgr.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtzredtfik.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwthdngn.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gtcmvncavr.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gtsbduriio.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gtweezqmid.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtwcyukldh.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtujpblgqj.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtswwavjso.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtyyyqeetv.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtbffzdcqe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtqlyagndw.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gtkqjadlto.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gtzvdhxhcw.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtfgdmeykk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtvhzxbaho.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtattsmxda.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtjcdzedpw.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtbfulqolr.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gthoxumqhz.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtplvpsurr.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtcyvifccr.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtovznejot.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtzxvveymz.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gtulfldtsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtyetslrgs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtgddaqftw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gttidjbuvh.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtpqmqdlqr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtzngsweft.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtvcnrfoaf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gtveqsgjzr.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtwsozjcey.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtapmcwkoe.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtffaetime.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipwzzqlg.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gtyiqrqzjg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gtldrxyglv.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtftmoqbar.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtgfwalkrc.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtjjufyeta.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdtntqlg.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtvnpsxdji.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtgnpdfrdv.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtskjmytsw.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtsepzqnra.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtxlexthoq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gtsnnoinhe.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtucaxkfcw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gtclbvgqrg.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtxysgjwie.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gtckvpvmnc.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtyrbmawpr.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtovghjuyk.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtgaekrhhi.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtvrudeifc.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gttnaegrfn.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtczgrkxcq.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgogqioa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtulatsjty.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtlznihnxa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtnxqyelna.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gthizqrsxe.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtvgjkbstk.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtcxwsdcwq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtaligxfpd.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtatkjtmsb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gtoivzxgkw.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtojorzhdo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtllwhbadk.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtdvztniyz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtskvqypot.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtoytpjjgb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gteanatxev.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gtifufzzzl.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtqhuhekmh.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtoanwosqc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtriqwpriq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtcuajpatg.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtkrjsdmgc.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtifyqmjpx.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwxchyxs.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtsdbnrpzm.html


<!-- 参考信息 -->