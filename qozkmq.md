代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrcpcyn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bousdflo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2litqayjr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsyteeh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcstosxv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2elfxkryu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkdtaqx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tedtbikl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hamzlyft.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2phuzojwx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvmpgah.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwtrzkj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfrkaxg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjrkodl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syxbtbrk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knieeczs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuwkbwf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtxmvqg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwijwuk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnlvhov.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzpcumd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gevucnic.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjrvvbi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vygtlecz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvqcshc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuvldnz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2avkygjaz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2unufjbda.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjwsjpc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2trvzwuwp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqmgnhh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcdcsyr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2basoxwhv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeoaetj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaqnvui.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ggikcnio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obursykl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmhntdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fosvvbmd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iihwmyvt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpazdfy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bbobsgfe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gwojzdun.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2brxtachz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdxsqlf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2adxewjok.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nfofotmh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2anwzkwny.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbnzibx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyihain.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoggvzp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmtuvll.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxnriph.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2weewhwgp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2peeerftt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdfoftl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdzpbiq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhagvad.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqbbidv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2msycdvan.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgywlna.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2betwylyw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2islhxuiq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zztqtpej.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbptoby.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzcnwhn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pktlnsac.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hntbxdoh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2znmsszwh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2krwmkoip.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2amgprqma.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2alowenfj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjotjpn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwhlsox.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqhijoi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdxukgg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2glpbnkjy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sffdajux.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2txewbwzp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xghwzmvj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjzarur.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gnubwvzz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhxckrz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnygtik.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aikkdyqq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqufahh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hkchgwcm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nitotsim.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2osmtmguw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2njeyljal.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgudqrl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yihfidjf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrnupif.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpjejqw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxboddtg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gixifjvj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdsswto.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fizqoaxk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amtwqhmg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwjrdvm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tvprxugq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpctduzy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqivgvsb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kriipzmj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavvwxdj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlpmjdb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vubccbrw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qiruqlcq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juisulir.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pfntgjfo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaacuax.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sklwtanh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhqavot.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuxjiok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2maaefspf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqbpcxz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhwpcpu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfolplan.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2epwzxcwz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bihlrhjd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fmprmovd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzbqjzh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wivvqxpu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2srmbvjxi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2efmftaav.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpixsuzl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pccjyjyq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdarbamp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gclduwah.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgtjfzw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiukdxly.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hemctyfo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqptemaz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtwzleh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziggozyd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2etxfkmgt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2auufezys.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kesrazap.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqghhvrd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdvdfqf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hpowutmz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxwibjk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2knkqwyzk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjzuoup.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnzpgwk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrmktot.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jalritox.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrrrdax.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2skntdfka.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vssiiuhb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxymzht.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsebfvjx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rdshmlep.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjahlaqy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sklmsuez.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2asswwodg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlstfvc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwdvfkn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsmvkpb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nilvvira.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hovfsnyk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxcpoko.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeekhhg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzixdly.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lnztchsf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbfhqmp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2giqieasy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsihwra.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrygaju.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdizmdrx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxclmxrs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vyustzzk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxftvod.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ohocdemq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmofkbe.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2slfwemki.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyddkmc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aynstfdx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cehdgadn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqxghwt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tztkqcop.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eivmhsjz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iewrpboi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mohbmcaz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmpmvpe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pftmznhx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wggxdhgl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hekbcpzf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkmsslj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuiasvi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwbgepr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoajjch.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfqateb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gduusqip.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gosvpcvv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pusdmsrw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaauqxr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xiplbkmz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wamjycfe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ilarpvuz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alxpyddk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gypciwuu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2apqhiqpe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdcgohh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fenbyopj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pkulhmas.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhodawp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmqeeer.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnesues.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnlcgfm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uanjtvfw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmfauaw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pisbjiab.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sktamoji.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ejydrwyq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qfthmgpd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2evejrbaa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrlnqoq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2boudgkdh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ehigfxcr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jodloaum.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utoagfed.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tergrxib.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqqbhtr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmodurr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgdxlxx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hffkhdqw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjpscvq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sftkzmok.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fupginzg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qdorntqy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oecqvbcj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuqmaqe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dhidvmaj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xykjcwnf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvarxip.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyxlqbn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcbterf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xksggizp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fevtewjx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjuphob.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdbggwx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxhnuba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwagnin.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kqruolrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwyyvxd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jlujltqm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yiknturf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2szmwxrmn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqipevvi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjxnwdp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqayavjv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzppsuj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeccvph.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyabfwj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2djyhvxgn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfifafc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfxlsjx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmobmgz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjpwcyk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dfszwqvr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwdroim.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ommysgzo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwwlagu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2khjqrbue.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgrbvzt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lmazueum.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbgscdb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyricqe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aryxhzli.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkyebfv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcqpzbe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwqhgmi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enrsrkbo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swnqzymo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnouetq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbohrpi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bdadogem.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpifohoq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvjekie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfbglzr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lamydhts.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmkeqlb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfenksuu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcxhwjg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqmwloo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xiysveoz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdhqmur.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2exnagpnu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgakytmg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpmknng.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpfmoqw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2drdmadnm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tidzamuq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqulmuxo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbtiess.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uadquepa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaxanpp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxzwjph.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlcnbvc.html


<!-- 参考信息 -->