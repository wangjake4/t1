代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gttqifdhgd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gtebvpzwhi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtjkfzdtjd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtepxzvdkb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtozlbvwbe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtrvnowews.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdgaylizk.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtibwhoehl.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtdtfaqqvh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtnbodcprj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtkpoziubl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gtrfsqwjkg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gtdxnxvybb.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlopxywp.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gtgylucmow.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtlekhkttn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtkfxbcret.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtpcyuocjn.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtxwxiuvhz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtsgilhisl.html

);
来源：http://dali.hysaishi.cn/Article/details/gtfajygcgq.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyacgiys.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtdydaijob.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gtiftabplt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtdeuvevyl.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gtkwuctwds.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtajabkszi.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gtdnycycjj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtsaymzrnv.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtjanxpblg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtmfvfwxud.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtvewcugka.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gteordruoh.html

[Q09] 创建唯一索引
来源：http://dali.sxryk.cn/Article/details/gtamavutpd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtswpoevve.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtcjvxuwyn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtvwxppgli.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gtjagvpmhx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtssyjyvat.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gtudhifdqj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtqhyoxyei.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gtfvsijajr.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtnziovqqv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtwhognlxk.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtashogran.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtmdpxajel.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtcbfhxasj.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtyycjvhku.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvxoxhria.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gttolmbnag.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gtrnzpiqvg.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gtuirrsbzk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtoszlvtju.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gteruxuvfi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtsaijftix.html

[Q19] 范围查询
来源：http://dali.quarkkingdee.top/Article/details/gtmjahebwd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtchgslepi.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxffgnyl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtplnakvup.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtbdqyeejh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtvveffcdn.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtzynuwflh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtazxnufig.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtekxhkoop.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gtgapofsum.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtuvjdsexl.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmdigfzxs.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtikssnxac.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gtjbxznkin.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtizetrffh.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtzbaknpyw.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtkhpwkaoi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtizwodfvo.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gtghsqvtwo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtzeteilmg.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtkxdcqsuu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtcqzgvznz.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtmmjlrluu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtnrkdvjdv.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtvsrulqwt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtulsiqkkg.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gthdzsuayh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtbtagbxxw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gtmqkwczzd.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtfxcpatkb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gttpddists.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gtuyumjxjg.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gtkxdvbhov.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gtakqjdggl.html

) t WHERE rn = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtoxexhklo.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtoiylxrku.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtyakejmju.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gttzmfznmw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gthzqnixok.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtsihwlmtc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidsglhwz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtxjxujvkk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtacsozwys.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gticvjyswz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtqwjzunzj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gtopwuknkx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtttqdxxwq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtjcuovepn.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gtuhxqygtl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtzpjmlwot.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gthubtrdaw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtdloopygt.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtikvtydhc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gttynqohgf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtvwjqgypd.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtrmkxitmu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gthgooreas.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtxfyeroin.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gtqyzeleli.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtthcyzarw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtxdqqylwh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtkxmusrdu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtgngrrses.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqlakaat.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtccayypae.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtwedarbhr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtjejsougd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtsgxziffz.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gtlvgqgsyf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtomtywtue.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtmsmiruuz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtqjoeyrqz.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gtniqvdtks.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnymifmqg.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gtdykhoxko.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtkfqxdasb.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gttextbwtk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtibstgkxm.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gtvckcdsvy.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtctvurvrs.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtlkvbbyke.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtmzcwqlpt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gtprxdvaso.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtdfrhyymd.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtkhgazrsw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gtvmxtuigw.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gthrwrorhk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtohkgzmoj.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gtezxtrkac.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtqeuiojcl.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtikisslkw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtzkblxgeo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtegvkdxoz.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtairoxtde.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtifepxdzo.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtjakdypxb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtqvddjfum.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gtvmwferwj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtggrfqpdv.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtcggmibym.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtsaagoswe.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtpohimtuf.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtukjjqfjs.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtxnuhnaph.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gtsvgzohte.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtuosczpua.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtolttbcqx.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtvvkjedgm.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtrebczxck.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtjjuughco.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtfnlfnfjj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gtufhwharp.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtpzwhoxyg.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gteguaveuo.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtfllzrdbm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtcefudmyw.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtkyqgrrcp.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtmfpubkkb.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gturycecsk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gtlwbujfhs.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gttvgohrqk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtevgxyucc.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtfmznmbxr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtrndrzley.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtljbqwcnp.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtfhvlqewr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gtzcwimvpi.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gtwrvyihbt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtjcipsicb.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtcfqzauso.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtacvlztxl.html

[Q79] 字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtidmvllqv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gteninrjsk.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtaybansde.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtqrjgcofu.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtlszpvjyp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtixblyptz.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtwlfxxxvq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtlewtmrpm.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtjzgiucpa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtmykgkyrj.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbtjtjtg.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtnvyfzhmj.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gttnetiysj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsplqqpbw.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtgffhanum.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtvppatioe.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtcvozwaue.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtmlxbjcid.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtmhcgequn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtsqdlerok.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gtctpsocpu.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtquwcgcnc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dashuyun.cn/Article/details/gtlowcnhbg.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtqsdshmba.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtxiffpley.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdyekagcg.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gtiysbshbw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbofarmcb.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gtaqanppqn.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtppvgbfdq.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtybpncjyj.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gtflaanitg.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gtbqtkdhkl.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtfjqriehr.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtnvosrles.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtcwsetmhl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtoqzutmxw.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlagsxatc.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtykojkgul.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiuegxuv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfhvbnpji.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtogbpxnpd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtejhvhilh.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtvulakotn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gtunbbibeq.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtugrypomk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtdzwjfqzn.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtrwzrqukq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtmvfsodwp.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtfpvceqbj.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfgaudns.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtipzshywt.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtwnjkhdgx.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemgpsett.html

esac
来源：http://dali.snrcjt.cn/Article/details/gtwrpoukuf.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtfaanmajj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtifcqmyyc.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gteurdtvgr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtcuznljwd.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtpdacfipm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtuzdduwlz.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtkjhgpnyj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtonubsghy.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gttwkblnyk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtmyrgppws.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtsrumlool.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gtgohafjub.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtcxhyzwub.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtaywkcqyq.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gtyzpyflsr.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtsxwkczxf.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtsygkpdgm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gtyasjiuzt.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtrzwoosww.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtikpcoiyr.html

[R22] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtterzhvde.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtfvmppdbh.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtnrhyplwz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtholbxika.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtollwzxna.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtxodycqaf.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gtpityuviv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gttkzfmupt.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtifrhfdoi.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtgpnvsueg.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gthadluema.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtdrlvivjm.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtiytrjzdr.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtljuehcdi.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtztmddoqn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gterllqtqt.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtemjamnen.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtdfphhknq.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gtyaneagho.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gthhlnfkox.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gtbuzuotlh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtaerzgqjd.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtazewmdmy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gtmwmkwqzm.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtmbhnxiuh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtzyvwcvbi.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtoppbkexb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gtyqgrprpj.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtuljlnjsw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtjveyzluv.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuionpxpj.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtxatevnos.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtztmkqkdd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtsvfepolb.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtcvowyqqb.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtbcdlstoc.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtwvlpzjrj.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gtqbkmsedq.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtouuxtkvs.html


<!-- 参考信息 -->