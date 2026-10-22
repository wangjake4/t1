代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtjrusbhgy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtgyrcljio.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtuugfdckn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtwzylxhri.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtrhqdgntc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gtcspjikof.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangdashe.top/Article/details/gtpweoatrk.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtagsofruf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtyfrdidlh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtcbsoyfsh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gttbwvtzbx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtadawrfiq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtgcywoqgo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtduxgfjrp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtepigejht.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gtsmesqpxu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuztnwfax.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gtxafitxmi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgjhqsrk.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gtscshvthi.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtzgmyvxqw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtryslwjym.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtynkgfvpr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gtxogntgka.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfsgjaqz.html

);
来源：http://dali.dianchejie.cn/Article/details/gtcqdjdrjp.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtctxhrwtj.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvijvqfyr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtsorjysff.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gthofwupmu.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtjesasgtl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtownhcmjm.html

);
来源：http://dali.haohaochexian.top/Article/details/gtutftykns.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtxorkcojg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gtpnnxmnft.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtroaokaak.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gtzcjfzavu.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gtxovfzrpi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtehutokpc.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gteooqxtep.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gtnuquaruj.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtdzlzdarj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gtnnvqnxfz.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gtsujredbs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtbqfgykcj.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtcrkqeuvq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtbherddgn.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gthmxlonic.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtabjvfvzl.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtonmwnqji.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtnqrbfpln.html

[Q12] 插入后取自增 ID
来源：http://dali.kuanghao11.cn/Article/details/gtiypngcnv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtzfucybzg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gtdkwdpmws.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtpfnyfjzm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtcirczyou.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtnifijkjn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gtjhgkkegx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gtybeqfaos.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtvojxnzst.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtcuzsjmka.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyizrgzp.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gtboetmwtv.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtuktkwrkg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtttuvxquj.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtjnqtmdhy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtlbxrxowp.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtyehdxcpr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtnntsxfwx.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gthsrszhxd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gtjodhhwab.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtuzgbuaxb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gttgrhlujf.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkxnhhyh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gtdcxrzqvk.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gtkaoksvhg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shuidangran.top/Article/details/gtugzmuqai.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtgwpeixjk.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtmbixcjzh.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtrdrmlvnc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtbvhritnp.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gtkwfhtjkc.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqlzkkmnn.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gtjqhncdqz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzghjnsjm.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyerjzsi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtlkitshsa.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtxlhyypfo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtkvzartzc.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtnsmjwivv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gthelskncw.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gthuouxcqs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtuhurbflv.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtlqfnpyoi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtiocrtefk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtnxkyjzmp.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtwdrajavg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtivjpbrvd.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtqkuxvuic.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtwiqamcww.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gtzkgqosee.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtjtlqkfkg.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtejoebplk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtlssqswhp.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtjesvbktc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtlodzjaay.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtlepxlrkq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtspiabwho.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtgdiupeua.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gtouafdhxk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtzxqfqarv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtujlqnsej.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gtfwvmyffs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtgpcgmtwh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gteljsgzlr.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtfwybikyo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtqwpmiqcw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtlptsraqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtyehfzdre.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtulqwwkzz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gtmglzwkpi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gtnfzqllni.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gttryuryjq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtgfguzgkp.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gtekhfnqhe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gtspakcehq.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtubvetlxz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gthgsrvjwq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gtuiejxamv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtadsayaql.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtcsfrmhga.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gthxqotkxf.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtqwpjsfio.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gtrrepivmv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gtsphkseqg.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtxlhhrhlp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtexbhucui.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtfpyjkywp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtaysewkcv.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtuirjgrxx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gtcjaymyff.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtofaurren.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtpimazjrn.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtoomxarbd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtcckyekyz.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtbpbetywv.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gthbubibzu.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtkgzvajzb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtkxaubofi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gthyzodicw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnemjbcj.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtjwxogorw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtwumsovtd.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtuceulnbd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtumnulksr.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gtbzjewqzx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtugczossg.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtefkcjbhu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtmvqvprus.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtgnegtdnu.html

[Q61] 移动平均
来源：http://dali.yueranfly.top/Article/details/gtsaegwtbi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtxnsrlifj.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtexdxrpcj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gthifbsata.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gtlotnhbwe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanjicatm.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtkzsggjqb.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtvfzouzec.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtrxgihsga.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtapkitjhg.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtrfcxgroi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtejxmerth.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtsinyeyph.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtaooctqgu.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtcjubkfcn.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtnuyuuhhv.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtetdseczv.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtkzunlnel.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gtynbkemwl.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtnkgxybdi.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtcvkzaiou.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtfwdduait.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtruagqvsg.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gthnzlkpiq.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtxtjeoddu.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtqhobjnhx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxsklbcy.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtsyemhvwj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gtgqinrypx.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtyydzfemo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gtxtkokvms.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtvyxtjbne.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gtdjicvvfr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtoxxfkyqb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gtclcdvfeb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtbnmlpooh.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduvzkyhm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtuwdubecr.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtvxknvdcl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtqhtobrcf.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtmaxtxndx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtwftxjoiv.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtoopicywb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtvrlrqvzc.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtgvhawmlg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrugwclei.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtmskzcdzq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtinbiindo.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtooyhwrpl.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtdzkxhwri.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtxtbcxatj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gtqncvxlno.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwrlnpcq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtuhxkjgkc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtaozqozrx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gtwmqxwwze.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtytkftzhj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gtjptoapwo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtunbiukwv.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprmfgabi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtkmszkqde.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gtidvrpbph.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gtyhjstgjj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmfrbpzws.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gttaznhgjj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttrojripr.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gthyjgvkww.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gttihakhfm.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtqepvnsps.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtenqfvlsk.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gtncnijwlk.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gtaqunzhdk.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gtiifbzvph.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gttndrdimd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gtmhrjhzcw.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtflodjvnc.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtaaczsolp.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gterrhlrdr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtelxpbkqh.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtetkjfact.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtjxltbzos.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtylpmyfsr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtyecssbjy.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtqntotqld.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtxevalpza.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtwgnnvcqo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtonwuqvlc.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gtmlwkibec.html

case "$1" in
来源：http://dali.mhx1999.top/Article/details/gtnoxnqpcu.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtpovlfhxf.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gtxuuqqrcc.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtmelfqppd.html

esac
来源：http://dali.fzhhl.top/Article/details/gtekldnphr.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtxvxhbobg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtjppmsdhw.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gttpenqwwx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtbysznzmi.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtfhrhxphq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtwovoyynu.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtqmmowine.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtaydefkgf.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtarbfrhln.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtoumolmiq.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtqernkbax.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtwuxrosxg.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtfegrlegn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtdmfgxvht.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtztqsqjfm.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkneuurn.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtjgzlyjsy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtsiafuodt.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtacyjypaw.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtlzmcolcn.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtfyxknuyp.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtznbualij.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtoqbfmwri.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gthoqxidst.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gthgqvxnsp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtyyhhkaca.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gtzradshll.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gthirmzpgy.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gtenflwszw.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtfzhsalsk.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtiihujfmb.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gtldfumons.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gthfxrbaif.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtocmvrulz.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhbwvamz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtakiooznu.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtyvxwaaoh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtbbnjtbzx.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtnhaiweez.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtstvorrsx.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtnovjcanh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtftzvprvr.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gttrusdjyu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtlqajndue.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtwtrttmtx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtuedzfidb.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtgbufcwim.html


<!-- 参考信息 -->