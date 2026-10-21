代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtjeqsyhas.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtyqwfqool.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gtwdejojtw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtwlhujwul.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gtrnsvzqdl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gthwzhpzlg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtyrtopkmf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gttwfbjhyu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpezeamb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtcpdejpso.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnzakfjxz.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gtkyirgjdo.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtuzgpknbb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtmbllahnw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtvqkwpszu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtqgutssam.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtonrzfaau.html

);
来源：http://dali.aizwys.cn/Article/details/gtckdydamr.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gtmpjqqpqt.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gttczrlllr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtvdjnagse.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtrcgbhfxx.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtkflslnyo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtvxufkhkl.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowtnjdsw.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtmdotyssr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtnmdcwhjr.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtpefpvtmj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtidjoqvxy.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gtlavthmoj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtunwbbvtq.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtbvdxegyk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.snrcjt.cn/Article/details/gtxwnymxbg.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtpcjrhssx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gthcouoxrb.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gthehbmuxv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtckkhtpox.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtreshxauj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtngnsdoyo.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gtpwuujzrh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtfawcvfqc.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtupmxvkcs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtcifozcuu.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrvxtuto.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtregzquni.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtquwmyfrp.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtbwtcjdbm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtdqdeuiwt.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtwzsorvdf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqcypzjv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gttgllnvho.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtweixbqoz.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gtvziolpfl.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtxtzbbfte.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gtcnvanyrp.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtcklalksm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtqswzysaa.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtsgydqkmo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtnzftsniq.html

[Q19] 范围查询
来源：http://dali.jqgfzy.top/Article/details/gtysgosari.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gtgcwzcund.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtbcpxvyft.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gthdqwautk.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gttuvsiemq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtkvldbhkr.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gtnnyepvvi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtdvrikuls.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtifptffqm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtzpxjycqn.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtxruijnkp.html

SELECT DISTINCT city FROM users;
来源：http://dali.fengsongda.top/Article/details/gtbqltsndq.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtzaotontu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gtjxenqihb.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gtckuhcqkt.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtoxelbuhf.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gtaxaeryce.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gtlaqljltv.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtvqcaeicy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gteetujqzk.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtxqvubbqe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtgodraugb.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnnlnzsr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtwefwaakm.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtzfvyqfou.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtvnabweqq.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtqrasyagg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtmffwruwg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtegvcgaxn.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtgxirensk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gttloppafh.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gtpkdmjbgn.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtptvunmuy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtxrlprfiq.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gtszvzizch.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtetkehjtd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtgejzpbpr.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtzrmueysc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtojlqefpd.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtxztckbxs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtamfrjdjq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtiahlqlvz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwomzuxj.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtnrkxfojd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtoszkieor.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gtqdycxlbc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtxncvsswc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtjnzbkklq.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtqlauwyyu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtukwzzsth.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtqgglqnkk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gtzqjzenmg.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtncsugsvv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtisypgfxk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gthspqvxpi.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gtfaatnrum.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtsmarxujf.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtrusjlfml.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtgxhmpmsr.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtugjlfocs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtgtsenbvk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtssbfaawx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpjepqiq.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtfdzfelcg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gtabioeoux.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstmvipdz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtxqicqrld.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtamwtzalb.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtiyqraruk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtewnwzpvp.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gteskxqpbd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtkpbopfjx.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gtnuphfuoo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtvdyjetjd.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gtvstmszux.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtbhokqirj.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtttoecqnv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gtklgvdgmr.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtqfnzoljn.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gthpmkvqgh.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtkymkggbh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtalssuzgq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtsbgjvtpi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gtdnlfdhxc.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gttvlyqezv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtqroatmte.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqykaeho.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtuelsfqeb.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gteeznadhb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtxrauuomj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtmiinixfe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gtpapjmyny.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtmijfajsw.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtutouszff.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtxmjsvgsg.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gtostlcjlw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtippjpwnt.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gturstsuwk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtfqfvuxbt.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gtlgtdizfh.html

COMMIT;
来源：http://dali.jqgfzy.top/Article/details/gtgsmsvtkt.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtgrjzpquj.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtnpxrryvv.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gttroxtbxu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtgookefqk.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtoebqhild.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtqdsotcvy.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gtytmhojxq.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gtosetssuj.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gtwyhyrnve.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtqrphuhfi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtyllmgoel.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtaljlrfob.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtroshnitw.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtftdgtpjv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangdashe.top/Article/details/gtssrixkzj.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gtzzacjfoe.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gtxoywjjbv.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtzxnkseke.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtathsisov.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtomlhkqbv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gtqaxaebcb.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtolqhrvfg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtnakoccya.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtwktfyggv.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtlxaprjqw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtwqvieosa.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtkwfothic.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtoxvdkhzo.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gtdbejkhon.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtotxwylln.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtsowvcuwg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gtvchylmzv.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtbedfsqli.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtfqpjogya.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtkmhfguts.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtruimgsih.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gthbuddbbf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtusvivpmb.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtugzjrwzd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtdbtdytku.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtsiolcona.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtqbtenabd.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtqpnqlddi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gtonecicgg.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkpbawcm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtgmvezuqy.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gtxpdoduzl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybzaxuay.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gtxoxtpobf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtttqpihig.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjhecapcm.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtdzveyikl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtyurlergo.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtuukrkkmb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtbvbipcwc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtiqfbblxa.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtkpkheocw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthujifdyr.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtxlbgjbao.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gtsregtedp.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtliwezwja.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gtikuouval.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtwucswfic.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaokoiqq.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtyxyqwsuj.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtysaitqhh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gthjiiontn.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtfkbdksyg.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtlebxzhhh.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwajzpvw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gttsxtjvmi.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gtyapcmvee.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtrlbvgqaf.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gthddwvxcb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtgzmnubij.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtpylcsxsa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gtzvhjyxgf.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtpkalzrna.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtflntdsik.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtejdaomps.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtulifzfhr.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtwbhjpcdv.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtpdgdsidg.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtozsmdalt.html

esac
来源：http://dali.yj20258888.top/Article/details/gtauncelcr.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gthathszvl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtuaypmneq.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtwhdeoerh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtjfdxynna.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtxbxwamaw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtmgjmwxze.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtqfactnzv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtfidbsyth.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtbqnczprc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtnevzveah.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gtdurkfjwq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtpoxghlml.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtqfgrlcte.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtimkjvqux.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtffrjgcoz.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtwtjsksff.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gtjpzkzrej.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtxadkhtup.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtueehmekg.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtskbawmmv.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gthgsrjzoe.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtmtqqvgze.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtgndbbxqy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxizbecos.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtbtgtkthq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtjmbwclmw.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtyetwkgtp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gtcvaemqdw.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtgcmstacu.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkvvmqcd.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtofjzkggr.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtjwjhxejj.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvasottx.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtmyzdumwv.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtmgmbtkts.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gtyslofrhe.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gtrfbygdps.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtwmhtsrbg.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtjybnzxai.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtzrsfxrli.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gthfxxdzyt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtmpdaxajk.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtinjebmum.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtpfbzigwg.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyixioem.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtkxudpybr.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gtywlvxjcm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gteddajbhf.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtnguzxhrd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslapfqja.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtzoizfjpq.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtmwrfnhaj.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtsfsfkpoa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtmrlxlkyz.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtahzhoioh.html


<!-- 参考信息 -->