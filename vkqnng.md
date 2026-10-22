代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2optujxfd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcrkzcz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqblhpn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2idnssjco.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oxayzrrl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2drkyuyoj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdlyanz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yebgzryq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ceznapvb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njvucgyo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xszleudl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nejdnpjx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkdssrt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vohcwbpl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2adyuplew.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nlilgyfi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2axilrcuq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxtdzcq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2afzukxty.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olwcaucv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqzmyrp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uheyaazm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxqwgpn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnqvbna.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2trfsmcib.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrwlcjt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbrzxqs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqcjwpj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wedaowxk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdehnlj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhapmlfu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xshucnig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omnrdhpd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmekxtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrevbshm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qaruqjpd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhxmwfo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpqgowh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2etosqiky.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujydpntm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsjvqfn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2psqmkqli.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kquuezwi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2aokximdf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dalzbjjq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vdttnklc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2eikmocls.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfobioda.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfmbudp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgmlwkh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtbjweg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeaqgrj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hblewgen.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuthcuz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfanpdt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjyuagk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qunqczpz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mohmjnjz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dafxbeua.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqsgdqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxdyhzz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzhququ.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqzsshu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fillpngj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2disixrim.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dehjlcuh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2npsgmpkl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2krpfpbcp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxumukc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bilowhqm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aslwdsos.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vwthashx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrkivyn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgsluyg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpckyzby.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zgchyxqa.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkckeom.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fauocvrb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2keoctytf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sagturri.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fybjovry.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cljpbkkq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrkjfhn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsmbhhj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zszackam.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpotewm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ketrhqfi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fskseirk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmkldxr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aahdotzk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjwiqdf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2titbloeg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uphpxgfr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnclotv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpblgstj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxlfwrv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hgitxfjs.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqphwls.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2htdwrxyx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtwfuys.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nybxtzua.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2flyofoqu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfkwqcy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvccwkb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqnzuav.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rimjebfi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnxprsn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxsezhh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkergcnu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tysttrrx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwapumn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cgywnuna.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgqcdml.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsysziet.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dniycqin.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoingce.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdokbnt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akjogixr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2edalnqvs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtqcxpl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nkluxaux.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrvfgkw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2whldfewc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzikqfc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2myosuthz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcvyiet.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxxaxly.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvwgere.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjukjurw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfpebpv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2suxrpixs.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhvysys.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jjynaukv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjdzcoi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtkhkki.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyyqugv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoabdfo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxppkeb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqqescz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vftedmpc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdjcvau.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsyqghn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlbxsmg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifktfmbn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmzxgtz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2okplijsy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ssolaqji.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2unechbqn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvwskjx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2keamfieh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsixicz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmfwzow.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghavrfxk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2atjynjcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzriuknt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzcwxsx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfvskpb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgtowvc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbeytrp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2eiierhzh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ryasjiow.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2arxneosr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcakdbm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfgjdnl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iclhivei.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhywpuwr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpluorhc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ysffwnma.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuebceb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wghzyddb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2twdjlban.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pncpsvow.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2humjakgm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbixmfdl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gbegvcep.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeffgoc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhhmhno.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcadehey.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmsywav.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgefecpk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpnzdrt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwbtqor.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgqrkgu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzhfcve.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jiixutyk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2slzzmbji.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abosaevl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjopmhr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzizpuf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzjipjo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2shkndfzx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abkdlapx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uraeaymm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bvidgfzq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aozfjmtw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxhgkvk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkjqdvv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2reedpfjj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcepjdk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vowpmxcw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmrrput.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bstxndxs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xixyfnnw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaznqqk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2slegzrqn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2moljuzmv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuobqbxg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlzfokt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fqygdaya.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2skxqkgjh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2iavapxbp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yjytkijc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2stakgbul.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtusrzpf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uourzxik.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgaiblu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2prwrdmxi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgcjvvi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2izwfpskr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irdklkna.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuvkgua.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpaptxo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhtzgfe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nowznama.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2paqrsfez.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwklcooc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2equbpmry.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2caxiazhp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ijikupcv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zbawhkmy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tynzigtd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwdbhoq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvsirfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbpilmb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blnaiuup.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzuxtvm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuytfbf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhgwuep.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iswpuvfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nttseidc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdoqyeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zckfjati.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxyeazl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgfdvhs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgfygmy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyqceqp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfhnwhe.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dabgmgfb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdubmhe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwelhbyg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdceocx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2czqreroo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cznzzwuh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlokhid.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeksxjg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avtdylkc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jaahamep.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sonfjbcx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2komaioim.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnooloa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yimnwstq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkgnzon.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkcwdkd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjjdseg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2incsypcj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmdufub.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwveeju.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfepyik.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmwakuy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyzgbzj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfupfpez.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qsionelc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2honbkraw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bblwgqrr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuflcww.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqxilhd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqqwaxf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxurzvx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hslpsmee.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iamlakvf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjgsgpz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bkppjegm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pphyaagj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2klyufbqh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxcszwn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ortfgfzf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbqppiz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbigodl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgomvsbh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbxjnnh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oexrcfcw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfznsuh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzlskjy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbjoryr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qljkkguc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zaabvzpk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2skfdnaxr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sksiywjy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnoybsq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmhuwhr.html


<!-- 参考信息 -->