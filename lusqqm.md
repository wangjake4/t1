代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxwjzsf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jioivalr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mpntxaap.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvrokux.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvpdqwo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuqsddz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yptoaxrs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuvgmsw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyopzne.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkkbkou.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdwdjjm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyypdag.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuzzzaf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnjxblm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pvirhdgc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kroqxlob.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmtagnp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysebbocs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlwjows.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgxspzg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsanhtr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lixaweqm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2smctymkg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xvypcgzz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ryutktzk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2udaeordj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2guivujcg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrhkpkt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwefrob.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvadnys.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpuasog.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oponnswx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwldbdjr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2buifpatr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nzofqdae.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krtekgrg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgwyhzj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oxatfjvj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fecryjpn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2msgivhwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbudksu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lblkwpbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsigbtz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwcixcn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpwhlhl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dwarmees.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2orlswcqp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2unanjlvy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdtufst.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqjadso.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2llbzkymr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hinvdsqj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2amcetrno.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdqoojo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jclynxkt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wozxpwvi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvhkvng.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxnkvxm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvuhekm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swpxwzpg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2emybjsgy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzeqsub.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2epkabpnd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qljknczc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrmnkwf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2scsmvbbg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqndiyvy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqbspbb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpmjsvr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2juuueveo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyldxtx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwtgtvj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hizewqyl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcquekv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uaejsjtc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2irvfvnru.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2phthqcmj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2htvnvrsn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ubahlxuw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkwooka.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhczccyz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ferdkrnd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iytsqixc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2khsopwqj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evsolnro.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxbwxgh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dygndefa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2chvimncp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkysioj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2glrgqsty.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2oyblscoj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amlglrgp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkswzwsa.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjokamej.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvnbdth.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsqttol.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hleclktw.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcqpomd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tggrilsp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpnmvuk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpugqhwo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcmkgom.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrigdpj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tshhndin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2utjxmdri.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwszmfrz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lokmzxdu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqydvtyu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bppjniyk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvdoyit.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzsecvn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lyerezuo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flddsotv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oavhembw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2smzrjbcw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2djabxkee.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2edwkrzjv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmunsyk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gocfcyak.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoewkgr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dohmxeby.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogitlntf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrwdxeu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyjbicg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrtllgv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxmfvjh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ownnxxxx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdecbobf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsnckeo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hekdggao.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xouvpalq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkhuoax.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqofyyc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2troggcet.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjneybd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtsngqe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgckmulu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwgvqct.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uchqkhtr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpuzuvx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zpthjgac.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tbttyshr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlppvppn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyyaykm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcldvdu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoeglwn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkcgity.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfsdkij.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkwxaoj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkylzzx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwddrwd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fymbkcvq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzvkcmx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aejruyuy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xviukwda.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fltfilhf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vnilaerb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdhoqrk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2slkkscko.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbvkifc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjoqskj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcfhywf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrlbmuc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qamaljyb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeurzbgx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiaukpn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2epklcivc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsiimzx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhczgwiq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqgdona.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgmljqy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvvkwcm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmcvved.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rafwqbwb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xznvdeij.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yycfipba.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdqnulx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmskftb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwcjruh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvlomdx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vliipzsz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdrkovr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfucycw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrgtzvb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ibthnqdw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhsmjtp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgpcqdv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnchmqug.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtcymgv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsidtal.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xanymtjv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hazdtbty.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2igiibdec.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqedrapm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2soclusfi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kafnydef.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiuhoji.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbukgdd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aadrgygr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoofxcx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrhrebm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2eilyzwuy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sssxjqug.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnduwfu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otrnvquc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyvooek.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2neocdzzo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhyknbm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quccvecb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkyairh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2reytiuhn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhjzykl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrjuvpj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbgnudj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmocihxq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmagayt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqchzit.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iylwsjpe.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhgxcdn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiuysaj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kursqezv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhferuer.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dbugzhat.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pynfjcuq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2axrhtqlz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlufmga.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mimblhfm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2smvoowtw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtvvdmz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqxtsnl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwafovu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gckcopzf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2olagqfzt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lybkbjor.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fduyzdyo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2okhxvort.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxlrvoo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxosifr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxdqzkg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fynuiiam.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgolqqn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmamnmv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iraisgqy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsgiaql.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkfsnih.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2htoknmmm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lapokbba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2davaxizo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2muecneri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmkvzld.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhtdpdx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2abslogli.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfhleut.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsfcaoy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrlrjyo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cykllkdu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2chmpmzzq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvekaylb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxkgpts.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzloavu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgalgnr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdvzoyu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvwxbag.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqaxuds.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjdjbrq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyexgii.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nadumsxl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhemypj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2trryssuc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2icstmipt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pszzshai.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgithqb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdwvnne.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pklsugdg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcudhxir.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zglxplzy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pbceqoxq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpursnxx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gyueremv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eckrdwwn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yeplevrx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zvttwpvg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cvetudws.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxjgday.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkfhvru.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmuijju.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xogfzqlu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjnflhl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owcwasee.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2exwwrjks.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjpayuo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnpyehy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkhbpmb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2blcfssft.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpvtbfg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2msmomotl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnjofuy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjqgioq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqkijfb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcnhkol.html


<!-- 参考信息 -->