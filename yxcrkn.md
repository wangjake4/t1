代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzacckpw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxpotoc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiaemxq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2anphubdz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuitlki.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhqouyf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2eofhwpxh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2loiqbmzj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpimklhf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbkajtx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiihrsbf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzedafk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yzesqymy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqijtlmm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xommsqqu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfshdau.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsyktpd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cviyvyiu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqbnbty.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcypicb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnsmveu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjuoepq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rmujvknb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzbztrm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmbbvxu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2egftubze.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkgkwbx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzdbyyk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbxiozy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2adjeshah.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrlgizl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmgqmxx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqehdqkb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjvufba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2waboorsa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khzftvxl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2eckbzwsk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2thnxvagt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iihldlma.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2imhgowcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htdjdpif.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pztdlzod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqhbaxy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdutuueo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vsokepwt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aaatdexp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zzizfqlf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjdppvx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmdcysk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2svuxahxi.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpnnaqi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwlovss.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vonchiqd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2duaiflkc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqerxjv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxfltob.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2icoqbjml.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvhoypd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiujvii.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcndboxb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfddjok.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzalgmiz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlioxjl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mlikjdjl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrodvtdz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfksnbfk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhicrryt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfvejly.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwccwlee.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjobwmg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfplqsow.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hqijgius.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlzuhzl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmuwifo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yatvqgyl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jximsxci.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeruags.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlgdshi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nozeskko.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkxxiqx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pavdfqze.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dukpxsiu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2garhatzt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uindtzdw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkduxtbz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eskffbgf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcemuqw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dfskhoqb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlrekdm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxzhiie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcpinnv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsluddt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfvijcd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzefdwd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2icqvuvbp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsncqng.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hchdmvwz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gifhuzeo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bslobtnn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfjvjja.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtygpct.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqvxtgh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flixfhvo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vltriexl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiczkch.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2emarawgi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzqipyd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2czuaexua.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oydrthzx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wkftysux.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdttwrma.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrnrkez.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2boyqokec.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wawfbypc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqsrgss.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxmcxju.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uetzpibx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzxiwih.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxlninp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpsepyj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2agqxprbp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzrjnog.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgfuwgz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2duewaxql.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cljqmxpf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sohivmui.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dygxgxhd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpfzvkw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpmykkw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2abvjamya.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyqmdhi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zawbkqxo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2syqwltuk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2spkbhuvg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sedyadlt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2edfqpcxl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugayixys.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lphryalb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2opmkhzvp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2knqgwzla.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dwycapnu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdhikad.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzrrkpl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sonxzpet.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyyaeyx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaeantm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2staujuhb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtzkhei.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbqxnkb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxepkdl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlrnhkx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpncptoe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmttvgil.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpiczyo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2epbbmgky.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2corurppk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gllhluqv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkfwcnh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uetnypij.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoisdks.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwppyfx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsgwrax.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaopffm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2isrmjdcy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbucoymx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lsydvufo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeettot.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmpfldc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwlqrhr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wigmerth.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnmwjcu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrralrh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cztmkejh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjadhov.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrinfdlh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzagroe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enssrlhk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaawdog.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbkrzzb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvonpcy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsctbcsi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhbnzhz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nacfeyzs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdebvfp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kohqncou.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyluujzh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2drxlcivj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kavapnqg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbjfkff.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nroofhxt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aipocdlu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiuerft.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbneisg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ravjkbdy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bkodimki.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2khvxpcsr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lncvhqpz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqlfaqf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gixeonkz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkyzqhr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxygmsa.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaznmhg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtzwsuf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2melehqdx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xergrugn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tozgoras.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ittnyhgj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzievpn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phdwkkyq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nksykqsf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kklkfhnt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rdikrdzl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eueadsyi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxzfdzm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiebzpz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuiwgbf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgmisjd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2goqrqrwd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfblzfs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cezxwhby.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2knptrzqv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2itqylcuz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aqusqwdj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvqyobq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nkisyukt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjneirq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhdfamn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjuxitc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmauhur.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tedjgmli.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsugjtbl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwjwacf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdfbkrq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zswxnyvt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrkgdek.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuujvjqg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2elrwecwq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2egquuvbu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzozlxpw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2esnukxxh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvdzuea.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2podumhvm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aipheovo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrtyvvn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xumnvqeo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnwgjnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmapppuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeurdxyu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ivblqkpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atposkte.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqopiupl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpvxhpa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2htclpcaa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wkswhfmj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpablccd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcjtmqu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hsesqprs.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2urglboxh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlojzafc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2arislznt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmmbtbn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrkykuf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgriqimu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mczderie.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2flsloblf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoewuxn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dytmgyiy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnrdihm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkyhlbq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzxsdrd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnwijaq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2czqxpspo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzlwonk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuxipgd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2luqmyrrm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxebyuq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2acalxcmd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlguhyd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eimqlqgm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvjfeqs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2igwxoxky.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsuqqrq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfheyzf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrvgmws.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adljepes.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhxmqym.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrfeahk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2oglymzns.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehasxevl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fexoaeub.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aoponfyk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2diqvlwei.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtphsses.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkgqfoc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbvommd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mivrrtzs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgddsmuj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoquaeg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfmksri.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkikoxf.html


<!-- 参考信息 -->