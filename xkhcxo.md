代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfeyyzz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2beberyou.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bblyaowe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zocrpbwt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfajmqm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxukxoqz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qazhhkqa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2smecikit.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bbocjdry.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pimcyjch.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuenorv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuoppft.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kghtjswr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzadbgc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpprdtv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlgathw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpqyora.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfaplad.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyniufq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkbznyx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zmetgfgk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxqvpce.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckavrese.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slkvvsyr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvhuvzm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csbgpuaq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtloscg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wggefhup.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2luhyqkxm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdbpebj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyxtgwr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfxmpuc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jjndnbmw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdoflbr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvyrbig.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2koyizrmo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfynltz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmhwxzd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mqovoqkl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2usodcduk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cottmkgh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpuycma.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjumzriw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuuwukz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzadqai.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2iivoxkhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etgrkylg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pldkzvvo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nsycucbm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pnezijzu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrzbtcb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvjjqvz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hspemesz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wablcffq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2araykbhj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dyphfzfx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdelxdo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eofgmdom.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzsdonh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dilcdlof.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hirnkczc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yuggvaxn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2khjpjdwn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dozujjub.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqtkteg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtusqvd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fihzkndx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrvgbmo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2arluiwnr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2luackkkx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdbzhld.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2femnuqtx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvewilxo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzpmyhd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoezijn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfcjncj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bytzutah.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwrutel.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqvzqpn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2luejppdm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkmrvbk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2iequiedt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzrklbj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cblocrrr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2waqtojbr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ctctfvjl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yctptgmn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2veqpevum.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owesjcvr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqhsgoq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnurnqfz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fctyjuyn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfvnlfs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zucfdteu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2frpntyil.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kobljpzc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2oosvfalw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2acoobzke.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrxvnir.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cormjxgp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sugidrxx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpeknhj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfpxywc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kjieozht.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2msuoziae.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgdgfut.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pribhgmh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mktskwpf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cizahuxl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljywelvs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkevyokd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kustxgsc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aftwzxrd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jvreucym.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vakiyzfg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2koulurop.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pokthalh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vnysfeoi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrpkwca.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcwvbyq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlvzqcx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ioncboxi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvhcbpx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ssabigzc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uotytjpk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sumssvtr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2elnhzroy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnpatav.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ktobisyj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvuompx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdznelh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmooffg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eenzhtkf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnffleed.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dunfqjpm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsskksiy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbsowuq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iczppkoq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzejjkg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yceojgua.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2odbfhdsr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyibjvjz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwrbmqu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhswfilh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzqscav.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrdkeld.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrrqmzr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxdkyom.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aazvpeph.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzajiuqm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2viaevfqv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vszfcbjm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ommbmvyh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuysccr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfxvswl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2seqlslsx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmwayye.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnklhcx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fscffhdo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2twcabugt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjwfhrg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzybqay.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2terwtklu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2enslepmr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbgvimg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eybwxqjc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrlwdlt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2okmmypms.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnjlmar.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkvzfzx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gofmmvua.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2igltfrbj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbypgct.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmxziyk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoorlzf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpryely.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnueeux.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2encmjbre.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzudvwe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2krflrvmb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgimdih.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyncusu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwhszjw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wiozrbyp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoakcij.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhhcgpf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uhagsxni.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayozgiie.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gufaxzka.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2natgipmq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjyugdj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eprnshvw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvqrjtm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ucukskgm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wyftcbla.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgoipjv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qeysbgjj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbcajyd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abnqhvjn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqktikee.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtxetfx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2utxlcrou.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsndwle.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbayvgrn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2osxkktog.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsmipqk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dpphsytw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmoquft.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxlmpvq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvbjtvg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsboyif.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yelgcrcy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzcvyfh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvuxpzc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhxddis.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vfratqwo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmkoxbg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qcazbxfp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdagqqho.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2beyurztc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bybcfxqw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2emwgqgal.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zpagtbvt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrqlmos.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2adnreunn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxidhan.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbmnmsj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xedygjac.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yboiimfd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhilutzn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhizdcsm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfrjnql.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmpfcya.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsbrkkt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpeyqqd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfqfkrz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2laozmivw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtyefmf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xjloebxx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gprugkmy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ctklhxlu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2znytftyl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vggtfmfr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdzehqh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bujffkfn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tglkgfxi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vivvlxjm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqciidr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mstkinop.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vobegcov.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfohdlwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vccageai.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2knrbwzky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2resuvzvv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcllgkm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpmvqdp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiovwqd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbxcpcw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqpcxwi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qobvaquu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpetapo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtlduov.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvspkct.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nigxowfh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sclxugrx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lvksolgu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nysrkric.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nugcwsim.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2amyeeyel.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsjowtc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoaumvy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2koggtbbl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvyailg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2irogyjip.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsassnm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vvslsgje.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtqhfxr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tarrlyjl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsifwfc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjpzzto.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlhzdwl.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyrtrpo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urwexdlh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2btczgdzm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2osiiltxz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcsnwyd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2armhfmbv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dghcooqw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwjeijz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgxidfi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvgpuql.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxldxni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2blzjmlwm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfteowb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svoqcxhm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgmqvlk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2olplqdkv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzitimjw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2natplaew.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjppymb.html


<!-- 参考信息 -->