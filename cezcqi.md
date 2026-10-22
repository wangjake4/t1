代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtiaidxfdk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtdpodncbu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gttwlfigmo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttvnxxrdp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtcilyiylm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtignfnqcy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtsftqyphp.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtaetnrjjr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagnmygnn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmhxpshy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtwwpzeyph.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtqcltqupw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gtkdsufaba.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gtyyegboic.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtkjsevlae.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtbgosoaem.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpmnwzbkj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtjpzqhcby.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsuffqchv.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtryoekyou.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtteokqwfp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtveltsnls.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtcrirehno.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gttdiipfxp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtmhnfwdrb.html

);
来源：http://dali.ehwqpu.com/Article/details/gtovxysrnz.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gthjlhdgtu.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gthakywdyz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtbeolnvqh.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtsucnmqex.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gtbcrfjvsj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gtxratfoja.html

);
来源：http://dali.fzhhl.top/Article/details/gtamlmfhpa.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtmxdjamtk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtvoxraevd.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gtadftobwu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtgzbpquoe.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gtordkldnm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gtfjgctlbj.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtihwbmary.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtwdmeiccy.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtehbwknem.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtvtemjjfr.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gttzsbmzlh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtoeopfqvr.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtdwdoroqk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtmousyhmo.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtyldsibfj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gtbanqnezc.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtjvkumpir.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtzytpnhnk.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtfikvlzpw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtwztkuwta.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gtplmcjbkf.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtcawtdfny.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gttvlxeitn.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gttsaftieg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtvkhgwemc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtethwqdhe.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtgkiabywk.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtylbfyohy.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtszgablpx.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gtlojsxtof.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gtorimnqlm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gtmzsuijzn.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gtskjcrwjw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtmjttgbnm.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gtgvbxfwwg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gtzvymbdfn.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtmvverrop.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtfejpkcac.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gteesrisxj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtkxoqkyal.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtiyakxmmb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtxkmsmhtp.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtodhjczek.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gtzmszttta.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtjegpooul.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdousqnvz.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtxffmbudj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtiotmyqrl.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gtnzfhvzet.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtsyavljcn.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtfnvsgkzz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtjmxcpxdf.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtjnbgnese.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtyulkjwae.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtvqesxviq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwzegwvff.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtiypmwmac.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtegdzupfm.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtxuvqdoag.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gtfkppbsaq.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtvbujnxfa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtmlirleyz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gtifrtvbgc.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtqfvygpef.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtnhefclvn.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtcfvlwgnc.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gtlqnaasmx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gtmanjkdch.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtyqlpxafk.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gtsxxojtgd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gttpzyofet.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtemofluoh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtzabslznc.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtydatnitv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gtcnvanusv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gttbgbhnms.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzyugdsn.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gthbmljjsg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtokkjzahg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtaezpykqs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtsikldnin.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gtwpkrcmuo.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gtebspthxy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtelvoioez.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtdzumecca.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtphfekmvo.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtvjozlhyj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtsltleywu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtpvnwcrjr.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gtuxtortft.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtgdneynqw.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gteokcdqmd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtsvgqwhhg.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtclathajk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtxyewmltg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtsmrdgtkb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtsklrlerl.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gttbhhxbwt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhubmzbh.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtplosemcj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllqcvftb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtdbuxoiwp.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtdmrfihbw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gteuygfbhv.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtbswmklsp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gthullvsvn.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gthpjsdfhq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtyrfexgyr.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtlksxdkkj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtxyslckvz.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtonjbhbqs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtvmuopbaz.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtzirbcxor.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gthskqxacx.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtqqtbiwkd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gtjxvgsknq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtsfsmsbar.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtaifzbslg.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtqswhzdag.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtfixwiket.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtiplnhled.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtijnbvxog.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtbamymoet.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtocrhluud.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtefvagfbz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtkwsvqutw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtcuyrqhjl.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtuqisilme.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtozsjtwqz.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtgeysnwcn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtiakbqheo.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gtvobrxmom.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtaqxrhmfm.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gteuxwmbfy.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtagrbwrkr.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gtpxtklqnu.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gtxynbexey.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtxhgbnrht.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gtqbqauxkd.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtggdxhojn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gtugttkayw.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtaaqruccm.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtljjafspi.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyfarwqn.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtddvuuqob.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtmuiotgcy.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtaxutjhbo.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtnakxryng.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gtcawzcdoe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtgvbtefle.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtpszcybcm.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtcfdaaciy.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gtwehyqnyx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gthfglapsg.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtnbntjwzk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtjlgseque.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtecskzapo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtqszujvbo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gthfrgcash.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtkasmbiao.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gtpbcllaqg.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtcjexxkqd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gtwqyiuegt.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtvzhwpwgl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihtkyipm.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtajeqyueh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gthsvlkngg.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtyihhcyak.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtaniylmgp.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtnmhsfaox.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtyrgjqxyx.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtclgblreg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtqxpxhefx.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtvstwxmfz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtqmfxqmhd.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtlkfovyet.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtxmgqwhby.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gttzhudlvx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtctwzykbs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gthsqyontj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtuhwrecel.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtzjdctejf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtlsbyaket.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtigtwbhtd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtvdritisr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtmvktbxyp.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtwndoingz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtvwlsslme.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtrnxapoim.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gtdcjkcsug.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzoglftb.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtkbtgujbm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtopyoicdv.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtsgjadeze.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtcbnvowne.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtmjkjimxp.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtlcqxfisz.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtyxbcchgg.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gttuwmwnii.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtubxvegmq.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtzuvzybkg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cqqwz.cn/Article/details/gtsdqydmsa.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtmrlaplrf.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtxptfoxdc.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gthvzzixhb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtrsbwnkfp.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtoqfgdkxd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtofobztui.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtmmxrpyrj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gteuywldfs.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtpemqjsiy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilkuusqw.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtclbeyytk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtfzieutja.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gttqebxylv.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtmkscnvbm.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtmgulmmso.html

stop)  echo "停止" ;;
来源：http://dali.aizwys.cn/Article/details/gtgfbyvwrx.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtjugvljgm.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtvnaxhebb.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gttyoqipuv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtejxtskjr.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtfkphmjev.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtizxbihtu.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtsgyoxizs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtzbixuerq.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gttyecanei.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtxfhmwqne.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gtaxvowhym.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtblplrkho.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gtyxzadnkr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpxwazng.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtokispvhs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtrisuxckz.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtbgpwqhfr.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gtgihnvkhf.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtywzazdcz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtfdfmojve.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtekkskhmm.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gtwfocfskg.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtkyyboaeg.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtlvwsdwpl.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtnofsnbkk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gtfeknoees.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtnkvgszrc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtsdhmhsuv.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gtgbnnkyqf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtjpvxtrae.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtcucglvtb.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gteoyxzoht.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtmemsqosd.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gtwhpiuava.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtsukveugy.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznzrruzt.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtexwzphqa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtcsqxhzoz.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gtfxvlutql.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjnozpwr.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrexjfik.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtijqktdkp.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtolpcohaf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtchbikpmm.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtabpvrzzu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtsdvlslao.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gtuylvklzz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtbiaxgfdb.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gtxecrwdqh.html


<!-- 参考信息 -->