代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrtjuml.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2btdscjrp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2skhnxyok.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwjpxpc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jaifoomf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eutmtbhu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2plymodil.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hioqsaoh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiafaas.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uszvtqvj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfenret.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgumtzm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqmpair.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbnttpn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2frmwudei.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amfxanaj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2itpiyylv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdgzekq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pydntkae.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfqmqfw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzqlnta.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whwbrttb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjxxpsy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2btfocmtr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvafbsr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbppgftp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnsagqo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuhdqtu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnltnau.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vmznekeb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfwmhcd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpbcrib.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrcwfjm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2avftzudy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhnnefq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khdflvxe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqvwqaz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wanffypu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtackupf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgngbpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjpgwcm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjlqzpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfordggn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2etlqjckl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfovwck.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bitprvzn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2irigdict.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmcyvza.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bomwhgsh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2geqblmse.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpxitqd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jousakqi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hgifztau.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fplqyyms.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrwqmke.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqjekyy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfsbcsf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jomygfdc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaowsnog.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uucaewlu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihptylpf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rthmslof.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2abxbqiws.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiydnpw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnwgdhs.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwjtupt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnynvsd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjxegvf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfpxkrs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzcosqw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrsfwwc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ombeagvf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuqohsq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nhccgqga.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2piyjewcn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcgjyxh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwvoerr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmthykm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2spemrgmk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aruzrcfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrffroi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwtpkzu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxajtez.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2exbwhbgv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgxbewo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhsujzm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnyriik.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcvbuja.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2goyqahrt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqbtyah.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyqvklk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pspeyhgs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkavwmwb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2naswxity.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfnmtyy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjvtykx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lblrokii.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcfcuoe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwyjsnr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhnraeo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hptpwvmj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcagitr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhvqapr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2olaeisga.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fimqgldp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rswminrs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzdpawk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2amsvftty.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxefdhk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjgzuue.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqckykgq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mugmzcos.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqekprhq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbdluup.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpinxnjn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oadgstey.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqfnnow.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nanfzert.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfggdve.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzprwua.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2llhsmhxp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbdnhse.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsqxefx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2quenxzjc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfgfjev.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptryspvu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zhopwjcq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnilbmro.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlrjlty.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekokbduv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lpujdaip.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuaqtdk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2okjputwk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfskbnp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxgzypa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqhpvpe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqqutvj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyqvaxq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2puzwgkbd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2enxohmfd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmaixej.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqfhleo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcztisg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgoazyj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iocaqeni.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2avirdwhx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfdjarb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rckxowep.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cekfyqpp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrofgjv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvgonig.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkegbhks.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrvtilf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2giazqaat.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uktdairw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2autihrqr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sknihpdq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibkzodb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jevwmpem.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xatkczfd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxurahv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcsyslz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyxuytv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pcajglua.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdzumse.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmzfron.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cynixyxh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bszgzzyi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2djltfeid.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fukszsfc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzhpiug.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2emulyiuq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxudpqq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sizywrsv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2imnlyyci.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrkouus.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzywsxpt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2irztwmtg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcoqxqh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnbmuib.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvvsjma.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2suifmzva.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iasapluy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyxmjrs.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kkytpvtq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnigtcu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtuohmo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiicjqic.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pesrqbkj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlzoawi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uiybdlvq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmazgyt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvddcbe.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzsohfa.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmcsvth.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdivzixf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkjjohk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2azhbgjgq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lregikmj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2auyfhdxz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jemaykxu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2duujqdul.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoarglj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvymatp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zitzxwkz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2barxmcqr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdmqkqg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yacijame.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbelgyf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bplufohj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrlppwq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2djdebdsd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mympcjpr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2abdapaek.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvfmlhx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oahjreem.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oycoxubl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmgtpay.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuqjmqu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyfkdom.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwvsbqu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwsqijm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mukzcrvr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2evymwytb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbnofwv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdxxwxd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcqwhju.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkhlbmx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2znnlsoem.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkvwwwp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmccqajr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxoqkxt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwvfjzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ierecyrz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbbotyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlegyjr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfwsvup.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnrrxod.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2geqqpoze.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqyubnv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhafwzto.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlblojs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tizconyv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fyextefl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vccdnelu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cviekqdy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpougow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kswedmkp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uibwsytu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsytken.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fewimenk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cezbypde.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrcnyoy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaofbze.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2prwplrer.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jeutjidb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzraxra.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdxpkzc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrsdhek.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtilszq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiljvqt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkkexlv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsjocfd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjxotbt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eidldueo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhgownz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2isgqothh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nagbxewm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gucugcya.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2afkvbecm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sstowkjf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnmqsua.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxwguan.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzgxlkd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oadhncry.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzelflr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvzxvws.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxgaoda.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmhpioh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2injyljrn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syukzcaa.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tmowuxdt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xoougixc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhafpiu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxplhrwc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkixlcc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekodrqhj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkesetgb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2onghtffp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgefaza.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxxrjsn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2umyxwkat.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqzxrci.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmalvpp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yacbvdcj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyrnxkx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2idipyxit.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxzjufi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjuikjn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkburli.html


<!-- 参考信息 -->