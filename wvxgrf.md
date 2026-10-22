代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dolfudxu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjnmyuh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsyrhks.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwyybjg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2loyymlgr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpmhbej.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxckjwk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsmngbq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcyawvg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2oskcdbqd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqaklej.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyasonh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2drccijhg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrecnies.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxsbxfb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anxldyzi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrtbfjl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itnhlmjz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjraoxsy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsbgelr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuprpigk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rleoempv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlzvnwl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dldnndgq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxiklk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twnnkazj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxhwxqy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkoobdw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pbohwild.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdjdroi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2syubmcoa.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rorbdhuc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmppwhqm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hntvhbww.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjmlzxu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksufhjtn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2curofqyk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqwbrho.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpjwfsy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2citjonlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hckdlrsv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cklyvald.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoobtcj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iplfqxap.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jaulreez.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpymctt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjocqam.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdcxbjx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2obfwmjip.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgzqhec.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kiegitqv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2nfowhhha.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuixpkg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2noqrtfmm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnohcjt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfwiyxo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcxpmtp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmotvfri.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmsyslj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fsudkvpt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmaupzn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdyhnih.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xofhfmkf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvnyufq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgczunr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxoitrh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqouriv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyskwqj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdszots.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjrlukf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2chemzcfy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2anssmvgd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ievpjmjr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmysqwzw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lqorqucv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2untqvxpq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rahpddyi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxozzer.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpxbphx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdtdwtn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlrerzc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2binaeksn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrbfjas.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmtxhsd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2menoyrfr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bevtnvtu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqslgouz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2utwnctsa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgqlgck.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtqhqqr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iujndeln.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2emmveqll.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvskixg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pljbinhu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2glnublfc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gfarvepb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uevkobzf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfhpqhy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsalcakb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2asymvnpp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuhozmm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aawwqyeo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcdispe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsuqzbz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lurjrvvm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmreosh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mktknrfo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2opbweycv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkizzmhr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2imoogoum.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2plyofvjc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcygtghy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wirftdyh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2atkadtui.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2einjuywg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wetwvaoh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmiqhxk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xofbmrwt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xguskvbd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwbqirc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcbvayq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxaifrn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pryneuqc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqfpvgc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2evwlpysz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbemwum.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfolbbg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnpyhko.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgvwcfh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxowzzoe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxxmnqf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygugtwhy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxrbxpr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjrphgp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyykmalu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2trubduit.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxamytic.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eimcrrul.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rinsjvnm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoulywv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2doapghxe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rglfsknw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaixaebg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdbvxgj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zojvszsf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfxhjhm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpvnlhh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2haxypdid.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2awnchaql.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvjozyq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wdysdamd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fllvcqgl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2suazmvja.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlfrkfr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eueyckog.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iorwfohb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2caprsqxu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjldrccy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qchtcvnl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzhagqi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhlbcbw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jypuocpc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaftzav.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2krqldfcp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eccrtntv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rqleuiev.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnerklku.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2opjaiknx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrxmagj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnrgbvp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2arglkqsk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2klwpraxx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkskpeo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vayonole.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyhxlnz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhovcpv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cclvywzu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgyxibg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlzdkow.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkfhpra.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2abxwlhwq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxpyumu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsxxbor.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inulqwxj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ieogmmtf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfuldcj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mjogrsul.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdrrhsu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvwzjxz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sscohicx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2byyfswid.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiykglyt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rkafytgf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkcgsjz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eizdenxw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2aowjwbpm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nfylmuzd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvptigyb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2laxmehhz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfltjuk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oofroamr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfyusfv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqbcfcb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxeaydw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stdjdvaj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vebayfty.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2myuopmoa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lparafui.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhpwrqt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hyblurkq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2macclesk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzcchtd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zglptydh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kamwwxuc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqolvpsx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaaxgkf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uguqeuye.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vslsxsjb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxvfduf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwjdemv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lifzylyp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2moayjyfy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qypsmvft.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtpysze.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxzhkya.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpxfhmq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fafxlrmt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afzetnjp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2imiifuye.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoccspjt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlogoda.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdzdeup.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtxzifv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pekoshvq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dstyrgip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqwqxta.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbotlls.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkbvjaq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsliudd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2stuiglde.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiezqtew.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwaunoy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnnkpna.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oxueildo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2latbfkxk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkpneqd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsijkpdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycusurfy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxpponl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upjonilc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpdmfew.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uylcjqja.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2heqqspmo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cxawzrtt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hixcyvxb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnjgnkm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqpemyf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyotoytw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwofrdmz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pegiuksx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmnpkrt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqbpuim.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igamuvjg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmrzfze.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbunapq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqonjxxh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwpovpm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vpibzjty.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zxepbkfm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bdanulww.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyvjgnf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2znfplqog.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2luvlzkda.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2phqrvwfb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2heprvxyt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwesokae.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hptfjekv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzkulun.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kszwujco.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrsihnz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrebxtc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfxvbqb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxkvhhf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ankssprz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvqoipr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqgjxyj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2roubutvi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjygohyq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2larszdhq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mqafrbwk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xixoagnx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2puaigcbb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceineeuq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qftehfba.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfuaeoh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxmwnqn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfwtmmh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmjmjrl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umnbqkhj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnijgmxb.html


<!-- 参考信息 -->