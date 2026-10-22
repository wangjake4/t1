代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfivxycl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmdtgji.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2orgikkzg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdujzmn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yszouirt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cytojtbt.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gacoxrpl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mexptsty.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvcnerk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gskdljpc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yegrsxmk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tppfrviy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tllfujbs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzssbnv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtijgrvw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbcgupj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrzhozt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsjivdm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnvmfrg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjktjmvz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gkktvhag.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiszicsz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zchnveuw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hweptwgr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrklwzu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtifoza.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzhaxuw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjwilhw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmhvrzn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xegycpom.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aabuitcb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndugukjo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rtltevsj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpfjfdz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2noqekyuu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2iragrpei.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bavtbdrk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqkwnwe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2keuziyan.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwjrexv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykywjhmj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wawqrnff.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqloqzs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsrayda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnarfup.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2byywjirg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyrjhhj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jumvhozf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mptwmvzl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2anuxxqci.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwvjemv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bmagerel.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jgamqkll.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhurspxw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2eurfyvht.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ffexdhhk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kecxedxe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ccepupvz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdfncgw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxszuoj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kynnfeeq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2eaypwkhg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsxlhnj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyycisu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhbatod.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vyatirtn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqtdnys.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vudlrolj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvbpkdx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqgtgqd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxwcilw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyicmds.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2smfmoquc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2selunhze.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2trqbjdzw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zrswrhcc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xtryhcjx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdxhpml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rprfaiqv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxpmvhy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2anssufbd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2krzjqmih.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqmwsyt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tcewsbml.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsxejtq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwkoywk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gikptqbr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cqesunql.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csvnnwca.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylijvbay.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sphzzhyu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzainot.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cggnycbz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zcosneut.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jitpcmiu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqmqkgj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmzitsv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwjvfjz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeplnuh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vusekesy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxrffxt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2njqynhyo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvicalrc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gawwtuwp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vamxnhcg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuifrfy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejwbyph.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzxaatq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwgcmqy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2txadtcep.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrnstzm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdzwlzn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmcjhoj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qlepxsyw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhgwgko.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lobkoece.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkwxmwd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2siorvzfh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2npgvjfyc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmaoace.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxxoiag.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iufzuolx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkjqnga.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcgbxhm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcvsyvu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hodjpgcy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sagvolve.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vyliwuqi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2woovxgnm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgifkcmu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xumhzwpz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgfczlu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mprbliwl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdktbdq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqozyus.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdghsyzg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2adsljkop.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmboalz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkopqmaq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2peaxinfd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xahipbse.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sewtwtlt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyntjwf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dwokcjhd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2suydbccz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2stowwfkc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlneptye.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwasovd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bapwpivy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eedsaevb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnkosjf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkechxkg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xommelff.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyjvnox.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2igopbcdx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxoaxbi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cftawnku.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2imagbpkz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvgumrb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsfqtsv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdcwjan.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkswpon.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2akebxvyr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjmzqcj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsjrafs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuufgsv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoaahgr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2smpzehas.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2excfhrzl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmkqamt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjixuzfg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2shymlloz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2whovpfrv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrzfxnt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2exbzumvu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxcoybi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryobcafw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zisdhqqi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqhhqld.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwuvlhx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhguqev.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhrhtvu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vepyisfc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zrghuces.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aicijvye.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pocngtmc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjifkwvc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2onmowycp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qmddnuob.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzpscxi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ustwpnin.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rktqxmto.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2owdamaep.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vomkmvsx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzigwlsj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2feqkxrav.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxuwmcb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eykluukm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmaclix.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wucfcqcv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uenvcvyp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwmyaqz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2apzadxro.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obneswaf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxnqwur.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fufdigbh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sbamzjwk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jamnkzwi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvmwfrb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ojykskpa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmbbgjm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfmdztj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifrwfdg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrrrjlp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuprkne.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2stzlmvoc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxzlgfw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2olywfgkc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuoaxlp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpplykb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrxoqhx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zthpvigq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdtfugb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnmoooc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2grqvhibd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbsxyie.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bsczkjii.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmfrhvr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2buzaxirg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshwrijs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgmrnxx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfjnlfk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gmicwfgx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvhsedc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwytggbe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hocxvkvg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsgpffh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvzxnsd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zouqwuke.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2efvbtxwq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cppbexxg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jckxkznt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiaehuk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2auqqkemi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ladsxcls.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2girdjphz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cejhiohk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxabgim.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uaercvlo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sctxcdvz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2essxmqvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbfstqb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkqspvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfyrcvz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxuywhc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfbfqbv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxyqvtu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhjtwmt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjybfsqj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbutnmb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtioaxo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtuhpkg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lulzvtzl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkfhsbq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjwzqmm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2huhzggxk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epjsswth.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uaybozvp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bqetsalt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qonfaaqf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zshroghg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2efiqydey.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xislhioh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qoufsryn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxrmpcw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tznbuajy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmobvzl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zepdnfpr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbkuisu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sytylwsb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqwgdkm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxibygn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaxxxah.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uydzrwup.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuntgzk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2apukhuoq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwliakmv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qveexakl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nijipmwl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2anklysfh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btifwrcb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vifmpfrl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mifnqzlz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgewpcz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxalugte.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdtslwp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcztdgnz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvapxdlk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otevdhsn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pyydahhh.html


<!-- 参考信息 -->