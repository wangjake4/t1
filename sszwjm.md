代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gtqoraszjn.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtwqruseim.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlokgwit.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtydhpjban.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtmhxzraqv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtpbskusro.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtzgzkmyol.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtrklaasqk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtepznzawt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gtipmowbdx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gtgfnctsxf.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gthcxzjayh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtffpvkawe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtxuptylum.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtqeiaztnu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtclvdkoaf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gtrmkxiqxl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gtlnbusjuh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtzaogrlxf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gtifrxpqlw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvphmktla.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtccrmxshb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtghypfjkl.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahauhboc.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gtfohuhgdr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtqfzoscgv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtkadcvmhh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtgsapmafn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtqlrpppqf.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtvjmdpunc.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtkdwejbkh.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gthfncbujk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtbeqbvqfq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtewwulvdv.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gtkobzavpf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gtolbdmxru.html

);
来源：http://dali.jianghu66.top/Article/details/gtnxbzoxpg.html

[Q03] 增加列
来源：http://dali.ehwqpu.com/Article/details/gtplbwclya.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cucudq.cn/Article/details/gtistesmde.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwfqaazi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gtilwtddle.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gttvqhnefb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gteufixzfj.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbphcjpt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gtonchuzmh.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gtrssxyata.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtqltzpwtr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gtsasoafyr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtqpvxsqly.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtbtgrayci.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtmpakehuu.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtnbmdiotw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtvhmancsj.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtdcmvwmpf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtcshjlouk.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtuqmgzmik.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtuztampfp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykmxhlmk.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtpxtsgpoo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtovreclih.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtjyfysimz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gtrqengkxq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gtrqbllvdm.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtwyogukrz.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtynjnevlq.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtzbdmofda.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gtdmuesgqc.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtbpmiirzf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtpuzlkzfz.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtcylqwlia.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtacjbnoul.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gtgmqitvbk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gtjpesgyoz.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gttebqpurd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtbdkaocdh.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtrcnigcdb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cashguo.top/Article/details/gtcslhzpae.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gtzjjqujoq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gtcddtbudb.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtdqfctoxo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtbwcwhshv.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtxvcviwbs.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtdecuywxe.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjcqcoln.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gtrtaxbnmn.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtmhlqjcnb.html

SELECT COUNT(*) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtelppcusw.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtqpmwajba.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxlefvnhe.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtzlutconj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtywogqitv.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtkupqtmow.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtigvrwcyv.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gtiuberzar.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtpdviwfyh.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtfubytrzj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtxcrzbpve.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzuygxgg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtxlrvgffy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gtqriqpsvs.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtisyliclm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gttxzdtbos.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtwxztxpbj.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gtjthavljl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtwznddfor.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtybkouvqt.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gtzvblszxq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gttgectntq.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gtrtwnqqzw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtgkowokxh.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtlqlldmbs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gtncgbgpmc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtvhynybjq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtbggjxxte.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlenbqxua.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gtnkgolozz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gttwyhcpbj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gttiaifgqn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtjpcntzdr.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gttoyzuhme.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tian-w.cn/Article/details/gtvoaqvpij.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtovmugepj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtzvngfwqr.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gtcqykcjio.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtmpzleybd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtdllcibir.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtbrkrlcjf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtxyzewdrj.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gttvaggmeb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gtnaiefrxb.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtqqnogdtv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtkhmyjg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtoitehvzr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtjgxqwmio.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtwhyjekmc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtwbigshhb.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gthbgwrqhm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gtrilbsxpj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtltowxfef.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gtazwqndua.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gthinxidud.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gteomfrdop.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtjyzwwbet.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtfsrqtddq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtgjbjddvz.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtqxsractc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtxvysanvb.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtwxxcanbu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ivvv.top/Article/details/gtctztbvoz.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtvrudizme.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gtkwwzxknr.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtnbitjjfe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtwxijphpg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtkgdtqwfh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenczvobw.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gthswyyajq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gtvnojpwca.html

[Q58] 累计求和
来源：http://dali.jqgufenzy.top/Article/details/gtrxkkgxsi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtzpxfasio.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gtrjlbeiek.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtvmxihrvd.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtxllzhmyt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtoasbgrvn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtmbbuczwx.html

[Q61] 移动平均
来源：http://dali.jlsjyb.cn/Article/details/gtxuvsqceg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtupsgqfta.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gtiuxhselq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtpfhljnzm.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtkhgeutqg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtyyesqgdr.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtpvzwndiu.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtgzdfdnoi.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtyvexbdoh.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtzdgukknp.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gtadcfhosb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtdrvostpq.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtfstqctxh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gthmszxyco.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gtwztatovd.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthadmwuy.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtcfotkjsw.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtelrujngz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtxjpyvadw.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gteudmrcik.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtlhqzauhq.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtbxwjnggq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gtlnpodfto.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gtpfoxvpmm.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtnipfutwx.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gthuicovvu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtlqmxgyaq.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtovmksdyo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtzyeqqqvt.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtaromcaja.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtqsqyamyb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtppvwtauv.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtbnnkvcok.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtmtpojeuy.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gthoeazxib.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtdopjrngf.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtdsebolto.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtconhnvhz.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gtmuqhswpm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtezqyiepe.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtvhxuxmtk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtsyvkrknb.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gttmkehhhw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtclgulmsl.html

[Q82] 字符长度与字节长度
来源：http://dali.yvedp.cn/Article/details/gtbriwbltm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtpefiqqpf.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtdgqdycfr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtvbmqnslj.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtspcqppzf.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbhpqzdm.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtfygfwcdy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqssydzdz.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gthfpzxpke.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtddfdofsh.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtoybfmmks.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtfnopxjkp.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gtgrxfahjk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtjooquwxk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gtxztsubfm.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtdazkjfar.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtvarolxdd.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtumccxuqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtfdidlufi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcdnzucil.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtnbphsnqr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyofqhnrv.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gthgxsvzwg.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gthzweryfo.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtbvhnpgjj.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtknsngarz.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gthnucpthx.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtchmvdfbu.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gtecxqxuxu.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gtouvzkjfr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtlrvpywlx.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gtmcdyfdux.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtgvdsusgo.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gtwrubnswo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtnbxqdbkk.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtrkczfuhx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtxhuugvnd.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtirkgrbeu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gtglwfynan.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtlmgsyunw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gtpcrbbwop.html

[R10] 正则匹配
来源：http://dali.yanxiufei.cn/Article/details/gtewvewyqo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtoslajnbc.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtokkeyzjd.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtzhsgxvdc.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtznrnupbn.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtkpsjrhzl.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtcjdcndnd.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtvvkrdqlh.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gtypivhasv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtcrjpvowh.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtlhcirdzu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtcozguofn.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtbxkgcypn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgidngyt.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtpxjknalh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gtfweewytb.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcggopra.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtaynjxako.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtrafhuafn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gteudrnyvq.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtxietosnj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtifwxbttt.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtlisldvvh.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtzmbveigy.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtdbbhqqbn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtliuiauwz.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtisdwjqcb.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gttmlfeogl.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtuasvsneg.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtxgawrgwg.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtfpeihnnb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotrzwszm.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtbavkssvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtzmzswkad.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtvaawerwj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtjfeydexz.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gterxrjswt.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtppnvxasy.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtvylriguh.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtmpqeashg.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gtqmblvizf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtljbntedh.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gttdopppkb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtbdeurbld.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtdbxdmncx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gtkpryxlch.html

[R31] 局部变量
来源：http://dali.zdqjudy.top/Article/details/gtqnnuomdm.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gtgtaexaeb.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtmbpfgnoe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtvhnzwzms.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtbjpdfhjk.html


<!-- 参考信息 -->