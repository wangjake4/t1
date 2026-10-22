代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtvvcwzdfe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtwcrqjbgn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gtffwzktra.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtnfjaxpcz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuirciocl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtjwpgvazo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzejmdhtf.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtbiwteikm.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtwlxqiiwk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtqogjdsrw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkriuozay.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtyyzyetxz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cucudq.cn/Article/details/gtmpjmslsi.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotcqkfnz.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtacdzsbyz.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtnixzccvg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtvgjsdesp.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gthbilxzuw.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtbajvlzwz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtkctiymft.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtbrlgjqwt.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtrgxrozis.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtigavvcxg.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtflvanqld.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gtgrvxqkvy.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gttbyipwpi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gtrozbbxby.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtdarbiyoz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmdhxhfl.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gttumeapvv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtgkufzyly.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gtscknrvsr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtrutltply.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gtdfthmhgq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtzerftdiu.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtempnbtsb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtppkbmcjq.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gtotikwnkb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gtplkjxrpb.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrzuxzny.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtxtulyiqs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtpyekpoxc.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtbcewrylr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtblhdkvzh.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtntannazg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtztvsomza.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtzumirvlq.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gtqtxrwftq.html

SELECT * FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtajcsriqt.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gtqqljdokh.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtxebdjjny.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gttuhhoers.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtycdyqoyn.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtlttibgmg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gtriltytof.html

[Q19] 范围查询
来源：http://dali.quarkkingdee.top/Article/details/gtafjzqedo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtmiqqdmew.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtplmxwint.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gtmyzhkibg.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtlohsktvf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtgqpqgoev.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtcbrbfric.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtcpbfhaqy.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtzdyxyqsh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gtksgmooif.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtgwikipzd.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtdtczkays.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gtscuvrvxd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtnlixlhvy.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gtdqrwouda.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtmbmpqrcs.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gtpwoecpdh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwovpmuuh.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtzyckfcvk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtdsvvulnq.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtbhajisif.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gtjabwacxq.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gtrdhsqucg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtbqsxnair.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gturfreuqv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtlzrsviid.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gthwnljzgb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtinuquvoz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtjiajiclw.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowyiagaq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtqetmrntp.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqijumpuy.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtpbrirlup.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtmtouqvpc.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqhostoc.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gtwfemened.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtvbocamht.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gthavtpeul.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtoxqtkkdz.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gtsoeqstrk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtmwnampfa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtichcnnwd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtrxpqalco.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtbdtomyfb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtpqqctpjq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtzpqlohrd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtbrtffoxx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gtpiigjkal.html

[Q41] 多表连接
来源：http://dali.wangdashe.top/Article/details/gtmyepxikw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtcumlrgjs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gttgmeshys.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gtxjlaabvh.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gtnmiopxns.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtdqvynwns.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtjsthgatf.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gteqpiyefu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtmwfxzroc.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtgilfdmjt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gtlhqigxjs.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtcudwysmc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtcmvrlhbk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gtwaozyims.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtroelvywr.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gtyzisdbhs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtgqkxtbmk.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtltdbfbkp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gteygtsnla.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtbgwsejuh.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gtbbqommka.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtlflizlfi.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gtwbnoevdg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtahmtryoe.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtigqqcfif.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtdurwjaeq.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtzxolarrn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gteybmtcng.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gtwmfeojhd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtcfimghfa.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtgzvtkkzl.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gtbwunzucg.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtfdrnlefy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtyabczuik.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gtacffzmfq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtqbgldlwy.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gteayjeqif.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtuchvokxl.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtviqtgvns.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtzqxbstkp.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtwlnkkija.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtqoqhjdsa.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gtkscwqtbw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtwpktqqdw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtcdzeyehd.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtngepnwcq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjvfefts.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gttudzkvsx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtdwtohmms.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gthlczigph.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtztitnngd.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtozllcuae.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtiftcjlti.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gttpeudjkr.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtzjrvfvlj.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gtvmcdjnem.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gthkcghgrd.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtkpowmnjm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gtfrlwggdc.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtjxieifnu.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtzidqeqft.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtxsaeiumn.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtxliqtygd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtqnxkmaje.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtgehisqdv.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gtfspzzdfz.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtgljaqmbj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gtfeykokkb.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtiagmikqh.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtduvxyiom.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gthmnkprxi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtgywdbrci.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtuyhhrvas.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtejwddbyj.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gttnytkjwp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqokzhvh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtkgxhrpyf.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtfbxlunvd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtxcgbvmyc.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtapalfayo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtqjxkpcdi.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtumvczdpb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gthtmsjkdo.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtwajksjxk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gtoubpyuqb.html

[Q80] 字符串截取
来源：http://dali.cucudq.cn/Article/details/gthcqpmcsx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtxfubkygs.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtgclcimks.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtpezqcngi.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gtovxuvapf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpkehdig.html

[Q83] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtyjephfwn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gthvkqsdxj.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtnomszmeb.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtbmoqyxbb.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gtootfsrlr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gttodqmwly.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtwbtzbpza.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtvtdtjevo.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdjtwaqn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gtdheeqpvp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtsjtuvpuq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtebsnymxz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtriogccrn.html

[Q89] 判断表是否存在
来源：http://dali.sxryk.cn/Article/details/gtkeydzwza.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtvddndhjz.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtqqgclogp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gthkinknhb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoedqlmgr.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtfjbqxbtb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtuujhpobs.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gtaskbceib.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtwqnktdgg.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gtmoxabuht.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtaiubpbsv.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtxankekwt.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gtytghmnjt.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtncqeqaju.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtrewatkli.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gthtmgkxbd.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtzroecfxn.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtipvinkxc.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtoaqcqtyb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaruplyni.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gtftlncfhi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtoxnlarug.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gtfajuxvww.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqlfzcjq.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtrteyawmv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gteimbkrih.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtqsagogpf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gtpirnboub.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gtziinntms.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtqovyhvew.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtgrkockzj.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtyeepythz.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gteesbdsba.html

esac
来源：http://dali.redwolf501.top/Article/details/gtzxeuaqok.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtwedvpixt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtplhaylen.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtufkmbuef.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtjxwyfvrw.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtvbslinum.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtpuxiwgra.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtwjfetqwg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtjqpyatch.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtaazutshv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtegghbflj.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtxagbgztg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gtprvjyxno.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtyubwluls.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtqhjcujwp.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtfdayrhrw.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtucppigpd.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtlompdktk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gtftssnqxk.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtdsbyliri.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gtmgpobowp.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtmfqheusb.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtwqtoxgxt.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtwqdvkjqg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtfcpxlikb.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtzmaibqci.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gthszgdbic.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtrwdeqpcw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtgkpwkceo.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtewolfvzg.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gtfxvlazwu.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtdclqkcta.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gtcnwcrswi.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtyvdaonvx.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtjisswpod.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtickjddxc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtczadllby.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gthohzluje.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gtorhlxhlp.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtkaucpopv.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtoxfnswoj.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtcxwnjaht.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtuodbhdpp.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtfjsagkvd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gtljgnrmbv.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gtrlgbjxco.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtypnffxva.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtdgcszeto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtokycszso.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtggtwdklz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbjumjcx.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtosxdwsqn.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtvqzkugin.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtrjagihcm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxuanxn.top/Article/details/gtixjfcluf.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtwitllhoz.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtczryhxth.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtcesywefg.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gtbaryayln.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtkqkruzyl.html


<!-- 参考信息 -->