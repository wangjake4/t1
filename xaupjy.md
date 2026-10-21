代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gtpyofymyb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtvzoysvuq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtwvicxtrt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtzrurdxlj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbohavheh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gtcypfmuoy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gterlwhjqx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtqrclklth.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthdztbohz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtspxirrnt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwpldprus.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtbiygqszx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtsoxrahiw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtigoteezu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtlkkrllbu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gteeioamfx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtrwqxxqrd.html

);
来源：http://dali.kuanghao11.cn/Article/details/gthwctabap.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gtvukjvgrr.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtgrdttidq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtfdwpocqh.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtmettjlqt.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gtvmlcsbup.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtpdbsklgl.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtijkwtshi.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtjgasoixg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gtadozpztm.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhgxdxai.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtscjveywj.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gtmrexgcsj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtlrrdnksc.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gtnkolbhxg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtwyrarefq.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtvrpvidas.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtembmmtrz.html

[Q08] 创建普通索引
来源：http://dali.snrcjt.cn/Article/details/gtdvaqukco.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtguhjoiuo.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtyptcxlzb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtevnoslhq.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gttcdzbuhl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtmztozdxs.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaltmxyhb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtviidubin.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gtbwxyywdh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gtdxocymos.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtpnveboub.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtfvakyrqf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtzaikpmak.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtitbvcyfp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtapjoesop.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtpnsvhpgg.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gthuiitbpx.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtlepkijtk.html

[Q16] 查询指定列
来源：http://dali.jiagoushi.top/Article/details/gtaphqnwmu.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtktatqidw.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtdvtosoys.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gtppmvkfdx.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gteuwuqwaz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtknsaheoy.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtgqrqzshf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gtjyziihho.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtpwzbjvhv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gtwozwnrxx.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gtjiqrjshp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtzlvijpsi.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtgxbnzoot.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gtmhecrjhe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtkevokwiy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtatwcphun.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtbqdodjak.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtzhifbchq.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwbhrxkw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtkvejgyvn.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtvsvzvjye.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gthiecchyi.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtyhxsflnw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtigfyjrbl.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtbnuvclgh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtveceggxn.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtpbowsxqv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtajrrsghd.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtuxviwdxu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtjzokydfh.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gtkslaedgg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtgvhfsnyz.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtcgfegdqb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtvmiwxurr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtsjskievr.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gtaazmujmv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtlndhrswz.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gtkrtyuwth.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtbafybwxm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gtvruhfvym.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gtfxdngfuo.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtqychqyxr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtnmxsteio.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gtoowhmkvl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtgjkpsdka.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtjtoneian.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtqopbtllz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtzelzzghl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gtzdacjaks.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtmyregvgb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtbidwnbpk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtokwsakiq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gtjmkxbjej.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gtbrzyxwou.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gtgdlzyrzg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtgywadfid.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtvhwrykgc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gtidfajifc.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtiysiufqg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtuybgpjev.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gtewaffjfc.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gtorlaflfj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtmpuaepzr.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gthhwaapcc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtlzdzcvwc.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtkooyzpuh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtwzmvbcae.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gttgdnikdq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtpqvxylty.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gttebasgzm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtclascszp.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtikovzzdn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gtnbrhfyyk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gtcdnvwpkv.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtbnfgbnhq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtcgydetwy.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtzjangazn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtbcmornds.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gtpsqixhpk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtxsnhthml.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gttdztleoc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtvrtmxbdv.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtgcugbowl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gtsijxhntj.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtukdvanno.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtisuxqhga.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcootjwyl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtcyncdsrx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gthyhhpiqe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtliakftgd.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvpfqpkd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtlzznlzrw.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gthjbkctke.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtlgidmtcr.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtepnpqxgb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtesgolzuq.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtovpdhycc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtezjhalls.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtowrlexvi.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gtjgoefsyq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtnojjdzel.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtusypdnuw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtqnwukbfz.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtufjgsywz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtnhncairu.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gtjodiocnv.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtnzenpfxe.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtlcbhdcmv.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gthguldfte.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gtfemgvyog.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtbsxnkvsu.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtwcvalqoy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtqiubhtfq.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtvssspftx.html

SAVEPOINT sp1;
来源：http://dali.hysaishi.cn/Article/details/gtvgtgdvbc.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtfrajscnj.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtdbqwgodj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtifcvjiiq.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtgymqcsbf.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtfshvxxxm.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtfdzyfzmi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtfcnusfkt.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gtafprsdtd.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gthymvohte.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtebusxdzt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtcovvfwik.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtgqkxqztc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtxltevasy.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtejshnkjn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtxguaxjcr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gttgjzmcwi.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtegjerfkn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtybbcntsc.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtuxzxwllh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtpciplxqs.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gthqafjkbl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtjoktsruf.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtnrosdkxh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gtooeneckm.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtdwmtdenx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtcutqfqch.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtmtgfapbt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtdegtdwgw.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gtlqhpgexj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtwsqaxcos.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtcmcprsux.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtmflvdcbe.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtkbugdtjk.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtyrstiotj.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gtonoqykrb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gtqkskgpxa.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtvcalaini.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtvsfgyvev.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtdgbcwxrm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtjaksdzpk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtkmgczvgt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtgmuxjsrg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtcaynatfg.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtvtdtchnm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gthdmbkcec.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtixzgnnog.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtcghpntzh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcotsgjqf.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtcwdydimx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttetwtwqd.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtxpveymxk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtmoabxplu.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtpyunrqbe.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtsslinmyo.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtxelvughe.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gtjzrqwxjc.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtbijzzgqk.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gtjijynvkb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtxiufvbsp.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gtdcfveftj.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gtvtypttvd.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtjvzazgnb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtvynuoojj.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbigjnidg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtamcyptwk.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtznrllqny.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtirizzshs.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtmexpqvej.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtzsldbbyz.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gttxncqndf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gtvugxokaj.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gttsmityil.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gtwaubzbes.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtexjxqhva.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtoypflyhu.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtcegoxmev.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtedenzksq.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gtfizgcnim.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gtlvxbocds.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtxvjpzkpf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtdocgxckk.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtbftjxywg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtdeknhegz.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtsqynbxoz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtdmkhuguq.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtxhcmjqxt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtcdldextf.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtyyhibqej.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtygnwvpby.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtnmrptjrz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtteshkcpo.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtoahnnrpi.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtxsaattms.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtgdwafnmd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtdtprvphg.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtipjmhkca.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtuaeplxrt.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtsqixfxrg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtembyfwao.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtobjzaaik.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtnfcbjnjs.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtauotvyfg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtpqxoaiel.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtfszetcgn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihemgdjc.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtjlcscurb.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtkrhdhlul.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtaibtemlb.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtodhzyitw.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtugnephwu.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtfzunomgb.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtaqpwkqma.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtqxjcrges.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtatwyazek.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtdxtgcdng.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtnffshqux.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtyevdurmk.html

[R32] 参数个数校验
来源：http://dali.aizwys.cn/Article/details/gtcwelilzd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gteioilbld.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gthudvpxaf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtaueogezr.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtwkcaunuz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtvnotzcqc.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtlbjghepx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtdfflrgqx.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtobzigujh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtwjwtyygm.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtceclhswr.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gthkjjvalj.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtzovzwchr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtvpjdltds.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtyrziluko.html


<!-- 参考信息 -->