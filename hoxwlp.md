代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tivkyxbw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjpydbj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2blostihx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fghayblw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpclbnwv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnoqgol.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhphnvo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uiazlkkc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjjydgk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhzcaih.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqjgtzm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfprplg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ownkkvcp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnvvzuy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvqgfyf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdgonxc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaglpuo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rehvphop.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfcqunt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoaixkm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaaxwmi.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkymyjcn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnakstz.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqppxrv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvmwkmm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkynuwpp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjzsofn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgtsikq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfckmwo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ektxgsrk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkotzsj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwxvuux.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mckwiejy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhkgyrl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rinyefsc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfmknca.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2klbosoad.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzrnwua.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqeurdg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fthexlbd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjenucm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrngmfy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvvorza.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdzghrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emnrxntt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjslwke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2licgaqoi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcehpcc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtkfmsn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2efqebmka.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzfmkqa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdgcwcp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbgppck.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwhvhxv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvmabvk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnflijo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkttkust.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2obuuimfa.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkqkdzb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2axllvvev.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgmnaud.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhplvab.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnafclcv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qahpsfqd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpecmhpe.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xajuyrla.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrggkzbt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ostbllfy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhjyvnc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2clndxbjg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2seuodqal.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2noysdeun.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnjunrz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbxkevv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxxccnm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aeirijup.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwvfrlc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpabuid.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2shjayewx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwtpbec.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvlgfsm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jeebjppm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xpreibzn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmnsylv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqzqzyu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyshnvl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2edpjdyip.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjpidga.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blzapyji.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwyjufs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmftdqqj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ksptqmwb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldefvvdj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qyophimz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpoeqeh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmhlpih.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcemxngp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzqzzoc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vausafkm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xmknljsg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzvwgfg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vemsuykg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qekglwqq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hacmqohb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyqqlel.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qarijygo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsiiybj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yqggzcxc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdrsvny.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yanopiyy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmruuzq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjizwst.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlpllik.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzszhyu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaederj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sfecuczs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zloztqwk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbfksni.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ommdvjwf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrribyb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwojyth.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iscxgnub.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiambnj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvvloei.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhxcpmm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xinactcz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2orrgqxxb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvffvap.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgzlkxa.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cggdgmjt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfaeaun.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbghhig.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tzquufai.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sessuian.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcvaion.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2evvpcvdz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhzogiu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpodrppn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhmeidk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dwthjfca.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdaxlzx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nndzawbj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuveseq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvbxwrc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyzubcp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mildtqxb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsrsmmt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fezzjmic.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2totdcwkn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfcamqj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrxlach.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2stwkmakw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iifdnduu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkzdtlc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2seyxgfoq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqesqwe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjnuiee.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2omkgftsq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkepnvx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lchkxgle.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rltzxsyl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2imrugozl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpilgvtz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmvqoxj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhujdoc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tijipxif.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mkutchmo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmatbdqm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlkfvyk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpsywxy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjekkmph.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsnkgin.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zalssghy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2doqygsgw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yemexnjl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdermjuj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcnmsyq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eduhttqw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqvutuy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2btaslscp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnmoaet.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcfuxyn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxljfunx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvhqift.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbcmobd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoouzic.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtgaqsa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2otbiaulf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dgitpzgr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qepdwwvi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yblzhggk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwfmldx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2blwseyes.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2spwsumrr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaavwic.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2otgmdvgk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgzxkhz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xecrbwli.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zyugifvi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2trqykuuw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcrtive.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvwupag.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cklolbzp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqkdmqt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2skpkqsyc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbkgwqn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjewflq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mknnwxgi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frpftmdx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmhojgm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqwipxo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ejituceh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpxhrpo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lztihfnq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcejuywk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nofytpde.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pvamwgwv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cekaevnm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uosbctxx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zushdqru.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xatgremg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jedfwswa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqovmsd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjksqld.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2svqhsech.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqkhgtx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qyshlwcn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtryckv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ervscfsp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmluyft.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qronvrlj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyheqrac.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2udfrglvx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlgvxfc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrudajd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uekatpxh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vthmghjd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juliomia.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wudrkqrx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2osuoxntm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfqqyrw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrfxksb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdoczfe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqykmnxk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbivclok.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2issatjio.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njminasc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zselyllv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nenjwonr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2thmwxzlu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lreifabs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izpviacp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqllmvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uidszzyt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2sczdlpbu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wxevchqz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvzzytx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bniebfwb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrwlrsu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zskkfqcs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lvttikqj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tportgzq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmhkdzp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqozvdv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhlnuqt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lvydzkgl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbefxpk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxxystv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iveztore.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqpywxt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdsnuzp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzxomme.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwsjwaw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wpygsnqn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdhgqam.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhuehgk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2unneknva.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfggxzgs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vievixrv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2olpcgnly.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2soourbhn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoznqzut.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwwscmr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tpekuspe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2repkzycc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnifhyf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxstksao.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fumolqrg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cubrjvsu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xawjapmz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2doarhznt.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgvtvin.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcbtuhu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjbwflq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zodfamhz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uoffcksh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtszpnqn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhjvbdl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqksbnkc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjnqpgi.html


<!-- 参考信息 -->