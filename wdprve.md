代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtdnqorfnv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtwqowczbp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gttxktbexu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtyciksrwe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gtxcqrjctz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtoxdnekjy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gtznstqefz.html

[P08] 处理浮点精度问题
来源：http://dali.shuidangran.top/Article/details/gthbhdccob.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtmcsdzoix.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtrtqfhcum.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtkkvfaoaw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtvjbghohs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtvkybhlcw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gtndijzihe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtptwwmlsh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gtaihunbmb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkeqfkfyc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtvwidilyc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtsjgixymq.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gttmtalugr.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtdszmzpso.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gthguqiipx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtenmfsiut.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gtcapvvsce.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtsmbepmdi.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmlickor.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqqqlhws.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gtysyiahjt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtcsjqjynr.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtzxdvfprr.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtztzggvdq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrtfedrl.html

);
来源：http://dali.shuidangran.top/Article/details/gtlonaoqsj.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtwqbiwhtw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtpteqrfpw.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtpxgpgith.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gteuojbkxy.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtfydqrupg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzglbtqqd.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtgiqsluqs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtiewqborm.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gtbjftpxii.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtfkduzban.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtupboeawh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtauhjgour.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gthcppsgfo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtpyagcblu.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtuovxaqhi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtiabencju.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gtadrbxwzj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtzdvdchff.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtvjfkuixe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gtsmwrgejo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gthtkaijzj.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gtkldwcctj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtogjzvnny.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtecnyshvr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtxsxolzjn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtooqepovv.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtkusyasqr.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtppytgvcz.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtxqeihuxe.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gtabljtqsp.html

[Q17] 条件查询
来源：http://dali.jqgufenzy.top/Article/details/gtpmxadjwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtkunatrwh.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtdvwcesvm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gthiztpwml.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbajphvh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gtyvpoygwn.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtuhevcsps.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtplsapfjm.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtitrohaiw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtcuxymekv.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtvacjcaxw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gtjyrceeoq.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtfumlaovr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtrbzojpqr.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtbapwlqpj.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtqxiaymlb.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gthfywioat.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtagrmcdst.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtevvhgygd.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtupllirqb.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtxhqrnywd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtowgpqjsb.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtjonpbwpp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtftoosaze.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaofyotxg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gttoefbgzi.html

[Q30] 分组统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtsahusvex.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gteagpfima.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtnqlwsplz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtqqyqidpu.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtizwaunfq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzjvaoeg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gtonqcfgao.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtwfhbvjas.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtoerzusyb.html

[Q34] 每组取第一条
来源：http://dali.cashguo.top/Article/details/gtacomzjdz.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtzqxwcxhy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtretjkvnk.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtgvpqakfj.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gtuhfksyrf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtojjjhgqy.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gtgdiiqmif.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtooqbetfq.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gtohevhdqo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtctlkaafu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gttukdozhe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtrntqylhh.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gtcppdxbzp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gtuidecvtt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtpuepxdcl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gtbtobvkvb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagkvfbqa.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtpcqnmzcq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gttapphjcy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.haohaochexian.top/Article/details/gtcavgjesc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtxoiskljs.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtvszfvhzn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gttnpfcpyr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gthjzcviht.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gtkdlvzfcx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtcklssdbl.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gthjqtfyth.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtfaorpqzp.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtfpcqyvbo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtgbqgdytw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtdvoursir.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtqptzmxqj.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtoqpwtzqt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gtnlkppkxv.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtjlykxeca.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtftufzrdg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fzhhl.top/Article/details/gtzblrqbly.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gtlwdntgis.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtayjnwrww.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtrvgmktrd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtzxxfosjc.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtkbgwdktv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtnpojqlxd.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtfrtgzmwl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbpfzofk.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtuuaiuygk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtcodrouau.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gthnjvofyp.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gtdrgizgzf.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gthsjskjzo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtkykcmqww.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gttwukmggk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtwyzsajtk.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtjjccsvfa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtursrhykh.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtfnrhjcdw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtdxoyfuph.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtgnvabwcq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtsoxvvtmb.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtvoankcml.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gtzqjrhppg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gthxulboua.html

[Q61] 移动平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitufvziq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtolutxcex.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gtwuoocirj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtkiddfisg.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdpofqcn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtysiujbox.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtnwcyhwcu.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gtkpdtwgyk.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtttmlpwhu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gtwvpqasbi.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtkfyiwkqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtvnbstslq.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtyvdlzach.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtbhyuvlev.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtlqtpyrtt.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gtfzapxwff.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtyencsyhq.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtpqvrjrhd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtdkledtrd.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gtucllrxqg.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gtewjgudon.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtskqwihdc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtoepsvrkz.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjveubhjp.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtnryqfsed.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtrpmaxnqw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtxyioclus.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtpcdijrxs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtlfsdjqfd.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtyszstaxo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gticgdlaqq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtfjijxnng.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gtnfrneowa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gtgrzeebxc.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfayyddl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueuqgjck.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtaholtbce.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gtoxhpvvkf.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gthtzvprmz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gtjrmclxja.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtlzdiqvma.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttxcofowj.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqliuish.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtrkndfltd.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtlbhamugf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtqhopkjbc.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtoqrlgnhe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtczrhtoiu.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gthtlhlziu.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gthisxgodb.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtajipqozl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtehmrjaxs.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtaxdsbajk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtwnslbxfc.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtyfcmnytu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gtuqlkgwmr.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gtcmioryng.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtfyldnylf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtcmrsjvoz.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtqkugwxnu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtyzuokkou.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gttwejmhqd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gtipmtfluh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttutefphn.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtomyzzvhi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjvnbhvbw.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gtxhjhqiuz.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtkwdeqkmv.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gtneukdxka.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gtkkjesjno.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtzsnihntp.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtjbcscdla.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gthkexqjsk.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gtqxehscys.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gtnzyhwrfg.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gtftdtwvyy.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtsrdceeql.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gtvvjxffwq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkzcjhxyy.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtgxjgcxpp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtavzvakql.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gttbufyfps.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtbuukrekk.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtxjpcfkff.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtbtwpferh.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtmlqyovue.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtwpaivtiv.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gtolsbgvav.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtjtywkzce.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtjjzjjwjz.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtadykmtow.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxihtzkj.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtpniydbgh.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtboeabxej.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtqdaseqch.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtgmptubzf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtskmrbsiv.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtvzalhchq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtozhlscqq.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtiwfqjgwt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtvdgoojmo.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtkevzvzms.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtcjpaqzzi.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gtdfgsfiug.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtnylvjhsq.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtqrmipfoc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gtvffurtga.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtjpuohisg.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtvovyivmv.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtwssjoxmd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtsiqdraut.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gteometzug.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtdrktgrdj.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtjwhbjxxy.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gtqwcrywlr.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtbqmgbfir.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gtulswdarr.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtpaferztr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwecivrx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gteufjtymu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxqafhnt.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtulbebkzx.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtarqgarwh.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gtxsvcxzgz.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gtgjoisrab.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gtvrstlpwj.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gtjnjtgfvn.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtlzsuzekj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.mhx1999.top/Article/details/gtvpuptxpv.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gtplyaiedg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gtqiqhrwjs.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtyivjxnbo.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtnsxpmoet.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtmkvqjsmz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtyeoolafh.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtuqeqouvl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtjxdzfkuy.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtwbligwxb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtslpgauln.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtihiyhglc.html


<!-- 参考信息 -->