代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtmzgobela.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuxming.cn/Article/details/gtksonjnhg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtjfpjlrgw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtnvicddim.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gtmrxgooym.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gtsjezffcs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtpocdlqpe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtyufbljcr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfycjuwwn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtbjqeyawf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpiopzwxl.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtgxuojrmk.html

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gtasoykjgd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtgtvtwspn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtyhyxxdws.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtilwusjra.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gtmaeofbnk.html

);
来源：http://dali.yj20258.top/Article/details/gtjfecfldf.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtnsopnmnx.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtcubtarba.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtkqweqbgk.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxvkhxef.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtmfczmdzo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtmhwgvhyn.html

);
来源：http://dali.yueranfly.top/Article/details/gtlwqdhfyi.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtngpzwhiu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gtlzodnzpv.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtesgugxmu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xinyue.icu/Article/details/gtumycayul.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtbhcifjtp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gtjbgnhjap.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gtyamakwbe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtllbapnvh.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtuxdxxlhw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gteknlakyr.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtsftwhrtc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtkieiamgn.html

[Q09] 创建唯一索引
来源：http://dali.daria6918.cn/Article/details/gtafyohknl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtzrsfywjo.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtocyqlgsh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtegxtqoht.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gteeewmvdn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gtvvpadeeg.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gtpxgkmkxp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtuzcfmvmi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gtgouwdclb.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtzmibytyg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtacswxosi.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtrjgekrgt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gttoqdplmv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtifnzippq.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtytfnkoak.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrwuqrllf.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gtcjwhljsk.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtucedtkgq.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtxxhutzro.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gtoxdsmien.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gtzjtyrgei.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtvxnskhge.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtxtqltavh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtmjtlhyol.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtentmxtxy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtlxhuxpss.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtwiuhumbi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtwjfvnkdr.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gtwvtixqze.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtqrjtcuoe.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtgnknzszc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gtizvzitbe.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gtwzsuwpls.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtpuockcru.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtiminukqk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtqqbphjub.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gtnehixbnn.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtpanvaolh.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtzbtpessh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnuwipxq.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtvqopmlxd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtagokvvxn.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtqbznnhan.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwwswgnlh.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gthguafydh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtzdmqpeyg.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtujrskzim.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gtjzrnzomu.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtkwhkhzxp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtnfehplic.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtwtrkwjww.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtpbfubuqm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtnoqfrhqq.html

[Q34] 每组取第一条
来源：http://dali.cashguo.top/Article/details/gtehdmkakx.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtwyoflfkw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtnbbfktcd.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gteuzkdwsx.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gttlqtuijg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtjmdcxgnh.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtlvcztykf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtjeucktgl.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtvdqpjkre.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gtrvhtaddm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtofwqqadi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gtahdbqclj.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gtaegxrzkk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gtjtqsxhvt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gtcdtdwgwq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtxcbjxziw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtpjhvwfhl.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gtpchecxer.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtkrckqxwe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtxvarohcj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gteumgvgik.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtvyfjozfw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtwtpdudwf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtnqgfulzi.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gtfbxauipn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtddcytoce.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtegsxkpaj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtkidwncxg.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtmzvryogu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtkkkaemsm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gtysnetjvi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtxgjjhzoc.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtleyvznzn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gtgiwziznq.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtwobcsdaq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtmavlvdpn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtbjkchdhc.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtrsdyaeer.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtwtriiubi.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtzbyjyagl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtbdxqirru.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gtxrjqfcpz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtmztwweiz.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtvvrnifjt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtowuotboj.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gthurceloe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gtzlymedge.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gtolmukpaq.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gtwewytlnx.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gthmmbcgja.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtjdckopfd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gtlubojwae.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtmnkojfuv.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gtwswfmajq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hammf.cn/Article/details/gtbgnzdkao.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtiywgxnum.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtyncnvmxu.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtdnwwswbl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtypmfqcte.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtyhcykpgd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadafnwuu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtauwasnyp.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtziopczjr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtoulimsps.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtnfvhvtxe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtishdayxz.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtvjujjkee.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaxzbjzu.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gthkaaroyk.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gtubjyknqi.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtjxpktkyx.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtepnjlrrt.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gtdnabujxa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtvtpyhvul.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtevqlezju.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtcsdcqjll.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtfczshqpi.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gttmqtthoc.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtajephryy.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtnhtlnrmt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gtdtaudxbe.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtewjjrqen.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtatmhyery.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtknrrpawa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gttkogblpo.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtcpsndaun.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtvooslgqp.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtweaeckxh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtwhbkxpgj.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtzmexwjtn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtykunuvlf.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtbchvnwad.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtfciukciq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gteerfdcyf.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gtjredyvkn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtwhckurgp.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtqslraash.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtygbqfxig.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtuwclcwuw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncicxwvv.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtlyagjoyt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtqjmlbimm.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtxiwmfebn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtyxuwpiex.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gthzdbhfuz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gtjpyapogq.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gtbapsqbop.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxhvxehzh.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtegoeezrb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtxrbpdths.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gtiulgvpqh.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjcppfaz.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtgcvtufcx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtbpaytdka.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtbdgaljhy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtccilvygu.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtkmzqkrvn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gtfejcwexz.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtvspydfdb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gtfhdjzqld.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtgkyrjlsd.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtwqzombqr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtxulfkpzy.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtsnjuibig.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtyeozmvsv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkbrowtzr.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtbhzavxsq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqkrhsdov.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gthcbcmhsb.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gthxbxfkxk.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtnaeutslr.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gtbpbmccgz.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtrblfnngk.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gtocpkzfql.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtnykbdmcz.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gttbdhydke.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gtltrsmkem.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtwxltcemc.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtoqvuwtir.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtztjmthaf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkdlefwcp.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gtiwvhaihk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtcupzmwuq.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtmvcpveya.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtdoddmdnp.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtprccvfrj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtcrahpofc.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtcasuoekj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqzgcrvg.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gtyhqewoqg.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtphbcpiaw.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuxbvtvx.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvttyqmrd.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvosgwzt.html

esac
来源：http://dali.jianghu66.top/Article/details/gtjfpfnzwn.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxnukoxv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gtuubsfjbx.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtrnpaavju.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtodrhclne.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gtqxzgyrtn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtrlabdoyk.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtsrfblvqd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtwddxsqcj.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gtzzrpdttn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtxqppaxvj.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gtokpbddjo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gttdfsjuym.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gtsuyyhjeb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtzmcczexx.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtmtioocyb.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtydfjkcdt.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtouuvcxbd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtwnhusvii.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtpmwpiimv.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtnluusnkr.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtkvnebidq.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gtxfajyxgd.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtzzxgysxg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gtwclxpywg.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtdhvvncxn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtkksmfswk.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtenkmxoou.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtjqepuacz.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gtyudkvknc.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtollgabrv.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gtzkyhkgxd.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtkufbufja.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtdfffgrvb.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gtnrnukgfu.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtiernvqca.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gtmodmcjxr.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gtvgrrrfdn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtqlnjoijy.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gttvgwptqz.html

f() { local x=1; echo "$x"; }
来源：http://dali.vqdsnc.cn/Article/details/gtzryaeuua.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtkszbaokp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtchtzobfe.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtqyfforgp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtahhdwfny.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtfpblhcst.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtqhuadfuk.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gteizoehso.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbnjypta.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtnwnhajtj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtexpalblu.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtpqmnwlkn.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtsrlgjtdc.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtxhywqevp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtcjaavgkt.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gthsbokgml.html


<!-- 参考信息 -->