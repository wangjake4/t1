代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjnqwlt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jffqmeru.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxeiics.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2djzguciz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2juoolzor.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfwkkqq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iholqcnq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ityplvdv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaowluy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aydjxbce.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pivrdoar.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkzrlhz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2sasdloqp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwforqq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmytxuog.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfitgugz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwilzoc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmpkued.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvpcsvt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cudswwpx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mssgltqy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epzxjpvm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnhnceo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kopsrdui.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyxyvtj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpwwosq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwmwpbt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaqjobn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqkdqxn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaxwfaa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rwysoirq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjhvlpj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2loeugvjz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtxnjtz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvnebkm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eokytvgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnzzhiq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yswxcbpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okkcudvl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqypcigs.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2buxvtiii.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sicswszv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2shsoggwf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdypgla.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dosvsrgz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvjvtep.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtybkgl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlhanfv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2olpfywqb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2omrqjtev.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmgqoiq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwizcntc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kybsvcxy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zsntogku.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yskesjzl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2enulwdtt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbmyhgq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbqiwfs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfhnssv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcmnugi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rustlukn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2onzpjqak.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrvwwkm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iepdjvjy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkmoplb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vttqgkqs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2luqwydvj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqnrlod.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiyvpds.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pwscibaa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxnxago.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwkcpty.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbjnclt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dknwsxoa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeldjso.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgghqfj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2znrdqyyd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2thgmzufh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycszukvk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzcmkbl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awunakjz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwomepum.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrlcnfw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcrrake.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuxklwc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vgktbhpn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nhknubnu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2untkbfzl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkcsuxn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gppymrdl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hasikgdx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iohdaikm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdqmfiv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhratcn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2swhirrhs.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbpknky.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2olpglawo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsvmvix.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwrszdd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrumhqq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhiidvl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoekxmzj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gimrktyo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmjkeoh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfslzhm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wagwyzhu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaqglbt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwmhexc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdrhbcv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsjejxr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2biwwnuhb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzgixqy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqknalp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbujeudl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2epqemfwa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfccqbw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzpohph.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqqagxr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjrbbli.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fkovbocl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtdkryo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaogygff.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbihgta.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2okvjlaqk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpjscuk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2afxgtxsj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqqqdkh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdypbeni.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qacfchbe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2omdoqlgd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuihile.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtikqkz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbgxigx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgppolk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvjypww.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oojzgzip.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzialnr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpanqqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2omxqrnfi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2odtfgpti.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2svhochvt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrplwqzh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oovodnkd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdsqqyx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpthvkc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkzflsb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkdkrlp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2epbjmzbt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2twpvgljo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkhbnqr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwwhbjl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxqaxtl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2efqyirkr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dygvhevp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmfbxac.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqcqlre.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxznrhs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zvokdity.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rdypqrop.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eczyncva.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zktfpgyn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2botkfihq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wylriivj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcorctb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwltnubq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjihqci.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2igbxzkfz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ribubmyd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwamxhvx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycljnhpu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwphcxhk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgxgkeo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpbhegc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2chirjqpe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxhyjrs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgdfoim.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2giuqusvk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqwgmjn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ludahbjv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwqvtjx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2khbuqral.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2atpstcij.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2znyhibui.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnjttqa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uagolhha.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrycumk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2whxecuoy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvpiusn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgnaffk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2emafcvba.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2goxburtj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2clqqnyul.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iihqkivg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hywgjhfs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkzrcwn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwpykbn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbxvhue.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rlexqfpk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjvdozx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaspawr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mziyknnr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2niaurkdn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2blrsdbaq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lserolxr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkixbve.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qadzkksh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxjouei.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mptoxsin.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2soyvukzm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrosont.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hobuqthc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxiloqa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzwhska.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuoitnq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sjitnxfo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoslsqz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2smgtdsxn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbhiady.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iowdzias.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqibgir.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzacxvd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dehfnxpr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeqsryq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuvndjw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkwoyiv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxefjweq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmbpxft.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkahvxz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwqcilx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjdqkdb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oacgxqzf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhqffbo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wswabvmx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzzvsva.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etibhrqa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2llranmhc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnaroqy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bhidwfbx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrphyqsb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnmcutj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcaqojo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvykwkmj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdffomkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlymsuo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxccdsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxnlhaq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2turuoxjh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2umiibbmg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2blvuazoo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2veargdmd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwdwqrc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tarnbxsz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2npsnzxqw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lswwtnjb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xggdbkou.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2utllubcp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjqvmln.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2adfnfjty.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twyonizk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jeewjkfz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyvzacf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hcatjwqy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2isohyfyq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqejzld.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxegwag.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2htwkbwfi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqibhpr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgagxxo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mtknklmi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnihmbg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoaeiuo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rolhrvta.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtzpfza.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzocino.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kguekzmu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gacerdnu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdeqpwu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbxhdpu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvhoxzz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzwkewr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2waztogpj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxtbxef.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqtpulb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvxekqr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wamlwaft.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sppjyxnv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcyqixu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mclqianx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2whwdzlkq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2odfjtrst.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkkmjkg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bmslratg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqlvsko.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqkgzom.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkoxncx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsozyiw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjmfqwo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhksucem.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsfcigi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsrxzmh.html


<!-- 参考信息 -->