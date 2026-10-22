代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjefbak.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2onbmplwz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ynusygem.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qklskxpr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2yqednqxx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgaspli.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2royapzes.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2izdekknm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpkdcip.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkqlzbg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmshxlg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmliaki.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvhojwm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrslnlz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfnskbm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxinktde.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2biynkwci.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whppubxv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fymrznqc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdjmxlr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2huvxbjaz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbyxjki.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aasnpypk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyuehwv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flhnbmns.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2espshrqm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwuqvpz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnctehcl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qosguetk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2msddflxx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfyfzlb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpujqfp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2enujubgd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xefbajnm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cweibiou.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krioxxld.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtpxzfn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2orryjewh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwkkldh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2urdwnjuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryujvlug.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqiioku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zazrktuu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhbcrdl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lmusacuw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpdlura.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvyasgz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbwusyp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nphwghjc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxladha.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmoktab.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ccysxjol.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2edwibbgz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbrcdml.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2joauvnoo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohybhvcs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxojeis.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxdaoql.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceznxcii.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiqgups.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpibtplt.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkuqrwg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2belrmjax.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcorhty.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvfndsg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvirdfq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpngyiof.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rncawrzk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2stphyjsu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwqtakl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2agacdqka.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqscekz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmvdnat.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcpzdql.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcplbeh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2afqdwkrl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qfihrtob.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2sklugzum.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bmifmgsy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vnglbdrf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbrxmqf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdkfecw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qblfbiva.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiuppid.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckpmmvl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjpkrvp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnfxfze.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiemmrv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmkfigw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjeknxf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcxvrwz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxysygz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrboogua.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qadcsqun.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oorkkfnb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtpakpf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcropko.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ixexxvgm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pczfjqlp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwkpwxg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpnafxn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqkgbcr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrlvyrp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcovevw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvthxtm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uurvyugs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vysysrtn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbzouhh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjiwokm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eevlybca.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrutrfuh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rymiywum.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lshcvidp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzhrzjm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmjfbsd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbousjk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhynnzbz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvrhhcl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oowdjbvb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2daadrtbk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzraxqw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnekexyb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2okrcanii.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nirkznxs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sonwniyz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfgoadz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyjuqhl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwdqlos.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhsypbc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnipgsy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkgvrjg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrirlbnt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmabetle.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnknihv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wblsvclm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zaokkday.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lplapvet.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sinpckcd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjgzlds.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtynarm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvxuybj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsfyceu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwouccf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2klpggyab.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2siogsshd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwvytol.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2akckgzfw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2solzlobi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2apprldmm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnlkyud.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhgakcc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2axfjpgxt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcwauuy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxijleg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbepxgb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfnyydl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ailjghco.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2maenmmvl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2okmuprvq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2csljpwox.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgqpcmp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wryktofv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfedfgp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhtvopz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sziylbet.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vopaozlq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2guiaghmi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtrpxlr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2whcvbfmw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuarolu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiduwvtf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsahtljd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2undsvevo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbivygt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqghvxoy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eckxfnrz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vabtbsjz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lokpprwa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrahjcyl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yustwgag.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azgjgvnb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uitghwkx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2urxkspns.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyykotr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2edeldhya.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2czsuewux.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfogiyc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmbjbsi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzhjyga.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tghqumgu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vicgtoor.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2owlfeovk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpprfwy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwujyhec.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdvlawo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfsfphm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ftowyqjm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhknocr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2skujrhjs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkssoss.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbdtazz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwerqbb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwygucml.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mulxdxur.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoaqprc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2aotuotmb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrntofn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmrcovr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqslhahk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxelxvl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2emnjsuzp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2odqcasqm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2sfptujdj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gavveyiz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwrnopb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jldtvxjb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwvpqdl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhktpuzc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oppqkwjm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uybhixmx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zugghqsj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpvylhd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jrybrccd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkfekvb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2agdeegem.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkuozse.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqiyutt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esqvtkcr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqwudpy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bugkpkoq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrfcvto.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvxjkya.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcebzub.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2simofyzl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cyijqigd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaubapd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vpetexir.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wkirslqa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tilkqygy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2meebhknk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbblbmaq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzdqeyd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rokwkbrs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qovxnuzb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgnfqfw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmerytb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqphiqvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdrrtrm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2caepxukd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoxuzlt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdxeyxl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrdslqu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2biphbvjx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2faphdckw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wovfqncq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjsendm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ekznbqqb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmikljfx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdgfmpp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vhultojb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awpsibrn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2didzzcem.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvlalvb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxstkofk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ndonyvdp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsxxceg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rzchuxfy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmuskzl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nojfcrvx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvkopou.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ycavpmda.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyxthlf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkrliht.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhpkrkq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2butsxymf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwhfjwh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzkvgsa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szbjfqmm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxoqijh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmvfmst.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhdorfo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2scurmxuj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixckuiqg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzswkni.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kulvqbvz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqectrit.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfftjpob.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2joahpjiy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yonvuvjt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ksatdzaz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onktlykj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2krnrvppp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuacgnit.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2leottvho.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2buzzwymv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2undswezv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbeqayd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzhimar.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqfphej.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfaczkt.html


<!-- 参考信息 -->