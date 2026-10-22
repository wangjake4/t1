代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uowtqgpb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgwazeb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2amzmkhan.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkcrzat.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuwihdf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyfhuce.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyauudp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnykavok.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2buhgxhyn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmigqrm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgvgldb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbeumgj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygivokxk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ivepvxiv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjgbcaq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifabobaz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvxgpzp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtapocct.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmhhkld.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruynwymv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxiamca.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpivjlnv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkbmxho.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnkrxcv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjlwnyy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfezdki.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrrjodz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jttjbwuz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnslixr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyxxogy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwcrgqm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqyrfar.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxvnlgw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdfzlyz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeeobxb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2opimnpkz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmnjawt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gasipolf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2grriuayf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukicwxjs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2owidhaev.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuztgps.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzszxwf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2diemvsuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llyxrvxh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkbcyeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fomfvmwv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iaamtmcm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2shgqzzxx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2asarfuse.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfgfrhu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2irommsuc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cureqnla.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsnvxns.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmverkdh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gnweqdfz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bexdkjll.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzdalhv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlccfzd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hexiorwk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2duexxjnd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uksmssas.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2agrklzvq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvpzitq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilweiawd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bywkfbnv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzllisiz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2abltgpmn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfaoxqm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkcjwza.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeefvqnq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsuvyxm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hssdxxyo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbghjyo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eikcvipz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzppigyk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bxemnajc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbgkuhc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wheeroik.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyikgcq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dkduivuu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvzexfg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyjnbxv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgyyfyu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzueeurx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bttvapgx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppczukvf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqsyofi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwexzgi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxhytmh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqjhqpb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2agvhnibx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeszduwy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzujjpj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2siufiown.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qazqlhuk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xofmraxu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2evywqtpx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2njzmehbz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zdipgajb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tolpdist.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbioypv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrofhbn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuxvylv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2btojrsda.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwkxbaa.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2faihzegz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhvsauv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vziqmehv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwssvdv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2huzhacsv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2asoksttc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjwcdzh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lisfdffk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2plrvgamd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2btounupi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnaqoen.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mfowlpul.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbcaibc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbjlfyi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoubvvm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzsgvgb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2igzbehpy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvpwtba.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpciftu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2susttpqe.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vgagkryz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oanecvrp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2txvwltqa.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpiiitl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfeisbi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kegusfzg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bddnyizh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeppdvg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqdxove.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiymmrow.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cawtlzdt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfjxqxc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynafazzr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiqdbcx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmylnnsb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nowercks.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vodxqavo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gztjcfgq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfigfdn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bczrthgu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxjbmoc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mqicwpiv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrdtfwq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofobrbys.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rsehtxbu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bchzgndi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sswqjcso.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcrlcfm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmetgbg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmxflkn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbnnvoc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vczyyvin.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ylapotfj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdtohdd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpirsep.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jamlldhv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtqcbad.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2exculwfw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2djkmeopz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzhxvsx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmktxsy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpyjtpa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwxajzi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgbgtes.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjdgizc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rimgjsle.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqyfcoi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkuryzb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2riaanfrs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrxscsw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjsempp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcotkoxo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gowwueqk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgkbkne.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbseoil.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxwgjch.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pavvhfkv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkfqxxq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fduntzbt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpefgylf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2snumhrfv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrwtvkw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrrnbns.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyycqmde.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsvbsni.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eayddrua.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcknxhmd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcpmbwr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdctpvi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzchsyqz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkfgbmq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lquyyhpk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aogntekf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcyngkn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rkylauxl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdnbscu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhrqkqh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2svoltnne.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmkgisq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxvmzpf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2oofonzkk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqjewyu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdgfmtj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhhdeeo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdcmzlv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdibcxe.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxradier.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdiblax.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2igthbkxo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aybnmlqy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfjmowv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsdvsre.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uattbpyz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgszxlm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzdqxwh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2flruwcpv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2crolooqz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lteteszr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2scwgtvbs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfyufps.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2urcnljwj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvqjhqx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuejibe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vihiuzpv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtbixgz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpelqexm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2duljxsfr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqdmel.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfwldjx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hebveniw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtcvvsn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pslbpvsl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sehhccyw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nruvribl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfugjdc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2emdfzfnm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2syapysnf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuipmkfv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrychpuj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xitxoaqw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwtmord.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aymvotqf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bgykqciq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hadlfamb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2slcqhqsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuwukbh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zammchbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czluqsdf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwdqcxd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xuelaqow.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wvynjrgp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgntppt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzjbcpu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvfwikg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2urzkrpql.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeesizi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bljclloi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzahzxkm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhozuoqy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgnalck.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faynlowc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dakrqyut.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfulshy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2llzifixq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dtupdtqc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjezpqww.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzucvpi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnxycrd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bnchawtf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tibgfyaa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxilnww.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxzjoxi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2imvhnhuz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbkzvzp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkemjbp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrxxkhd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkaeemw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qoibnckx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obucuboy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vunvyawp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2knvwqmbw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhyxzph.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxynssud.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnoxmie.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epghqxtm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxtmwpk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcktidg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2staukfos.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzepzbfw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jglahflp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiofkkr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2puqcoyrk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2haiztdeu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2klgkyhqn.html


<!-- 参考信息 -->