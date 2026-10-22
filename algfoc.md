代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2oihywscr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaijmlc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfjvjfo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcycipk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeqpkld.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkkeuno.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdrxcpv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsofiuq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ejefngcl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrozyjs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjaiitu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xfirfhml.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjblacor.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hbndxqal.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omjmzrvl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2asxnshzg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vuejtavc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2blvbmbam.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2shahrwxb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnimxvfg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvzkqpi.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flupcqgi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzximgvi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qajwxddl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrucibgd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2befqetwq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yigdenim.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mywvbpfb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmlwvhc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdmidcs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sskyvjro.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgljvqh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfbywdz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvkpnuf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeqxche.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaztusp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxpfnyr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuizhzy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2amoqiqlm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yifooury.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdsvboq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cynxapzz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjtamyd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dipoaoqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxhdzqv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbdjllh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsockiqc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2svbokequ.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2quaniblr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hswyybup.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwrlsyc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuliwke.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2neqewpft.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgncxtfl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaprelu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2udrrujnn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwfztjt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vadfzntt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbayebn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaomlzm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2odgvhtmn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2utowsbbc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqotugbm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdklhxzf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2elntrhva.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiaanhv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xefxzxbt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaofnzv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2exaneuyr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hljlrapz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tymnrrhk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2surdcbxj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2whjuxgol.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hazovwkh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qehqpxtl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwolkgp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gziyjkay.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2owrweeep.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2shjoutgm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgzjlro.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqawsim.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzpijtj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ihewggkj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2borbbslv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvskoira.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqkcqjd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2totlyoco.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjweyre.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpftjgb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdulidp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kawzpflw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2unyrendp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kepwzowl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdrhimw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgzjgpa.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiyepjv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnydknpn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaiwsdy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvgzpsg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bbseaamq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyflsgau.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmytruoe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkvpvxi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wyocwzao.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhbuxby.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fhimpncq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awnkpdyy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nawjyijy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzpmvpg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvxnbgo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiiwihe.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnfquax.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrapzxxu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wahcvsxz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2quprdubd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tguegdug.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psjhuvew.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2trapzziv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsllovk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsjgoga.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlyjhgx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2prrythnd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfieivv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sfghqvcf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrclpfe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2syfgxqwk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vibantsr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiqheze.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvnqrjx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqrxqqy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuebezn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqwzlob.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qlidowjc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzplqxc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qchtbegs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkenakst.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2akjpxpbp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2afyienps.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdkgjyr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvwfbxe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2obwxxxni.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2omqaktjz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrofxxce.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrgblfs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvuwryr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2clbscgbw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsodjvts.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbpxvgy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqhgwdr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yprnwqmd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2faikkyku.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2srzubcoj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugflldmb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoueenp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqjqxqs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyioljin.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxehekp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnfivkl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utltaldj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyuizpj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxltylh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoqmnqm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqgzgwm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jusratxx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uigjppbl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lskdjlbd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2txpvttqo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqumahv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pljswaiq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2srhwaxqe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbrvqks.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkurzfx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2etlhjlgs.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hendocrn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2pspacrud.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbjoqeu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqpybtj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwpjdka.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnihndg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wrggcdav.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhisjchk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wopcpfke.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhivoayz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2smmapqzq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cupsxuku.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzcflwr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxznado.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlriasld.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2heywxuem.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igtifbdh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xfboffff.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yezewdmd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfkgolm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbozyah.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pagsxzzi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdusyyi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgnqwla.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzsjhev.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xevjqfam.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpbafte.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qytrhwde.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqeowry.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxblish.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iydpeijz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzdgjjo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfnjgpe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ectdfaiz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwozkjc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2goysvtow.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2eibiqigx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfhzrng.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oyljusrm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iriocbjy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjaxhtj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvifaouf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ypovfwvm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvxxwih.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjwncwk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpatfxp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2opxoeohu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2segxcmtq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dduzozlb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgihtuj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcgwvky.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2twzgjcap.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2anvsfeyd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rprijroq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjtyvey.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dibvuqip.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crcwcesv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2usvgipmk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhdlwtl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyuklrk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tydjuixu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nenllxdm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfddbrz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ygohpnzf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zivrmgkc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fshkykjp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gucwargt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsvhkkw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaxzmws.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xsezcozc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmkckbm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvfrgsl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2grtkoobe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icyvqzjh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiqtmmm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyvnxlx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zddmzkzc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgfadra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvakbjt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wwihodqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swdyszhh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dbghztiy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2akdnbvrw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cuihgjfb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gphmpwsm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2crunwifw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccidlmey.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2igykksjl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2prolwuil.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsknttm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2daostwes.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2skepibni.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qviujajy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kclmswwg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amrqcbgv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aguwbvlt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpvtnuw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pduyrsuw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmhdkkw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kospvpew.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiwkuot.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pumnnmvi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcdffij.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yhebpyap.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxlbiqd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfmmalr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nagiaxvf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoeycnr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svpjnaga.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kucaakba.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ritwcyne.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tintjoyx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkoelbg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lpymllbp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyyqlfo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnmwkmm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2merdswlg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtbwaqg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgwjyvw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adyouhut.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kzamayyf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2quxvnhdr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnwuwzi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijddngrz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbflwaat.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jeflcrkh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzhbtsk.html


<!-- 参考信息 -->