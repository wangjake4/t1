代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2etrlrxss.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2inwieunf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gecxoqbp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfueygo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsxlynu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjrvduw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgljopas.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2evzbplbc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbyofwu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaiaxke.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwfagxd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ptslzzal.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2klwfidef.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rnajsnaq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxcpogd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uymrrstx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzebphq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjvlmrk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2whvvncmo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbytgauy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oocsyfot.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsemefs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhhsprd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxjisuz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzbsytd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iujtstbs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wijximck.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsijxgf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2myxneivi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eifnpvsi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2auliturj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2isbmgvob.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jrglhags.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oiosjyjf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeuvvoz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skcghplq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpuycfl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdzhjup.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiwraep.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaacxcd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgtpcpn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvebrun.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xnegnnep.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeibwms.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwncdske.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpihwyk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwunzfec.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wkucjwkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdumngtt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yusaglmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmbtsaf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2corbgsdk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2umpqlohw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2npksomec.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlmmxkg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wegtriba.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2trgoypcp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhdhyor.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuacpig.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2udueyvdu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2inaexwsq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbvcalg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuglzob.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tursckug.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bufidmhh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2stshgcqd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtmqdms.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utfgmkfq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhkakuy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2suwzpdam.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbaygdd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2suehlpuu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pogjrsut.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcuylwj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pruknkxb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zpppydci.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eejucyok.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cqufxitf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukngwxjm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2acpevdlc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfsugel.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2otueuvel.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnuhwni.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqndhzu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ichfswpg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2biedwgrh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqvvyhh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjjgwev.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyhjgtu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2evxnfbpn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2newslknq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zwimthop.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amvatnmc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnorkaz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtpkbwu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzinecq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtocglc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmenwnu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnkjfcc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2alziwiuy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2esipqxhp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2icdvhpyt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fztefcdx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwmoykn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgepenx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkcwzfy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmbwufx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2neosanrx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkyyidy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rtocpxkx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuoabyu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnamqem.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2stdcejni.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvemyfi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qupbwttp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwweucjw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mibfotbo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jhutwqfz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2adwrvhir.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdwrwkk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wshcfpgj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgnnbpx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiunnkr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtkloer.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvavwcds.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uwadolvm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeemwtfc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qqewgipz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsbasly.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcmlgkx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2iofqfgmk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2acfdznbl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qymnyzgy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxrdxuk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxkbtbb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnzpaum.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hiszskwl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kukmgxfe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nnecguco.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cujvszzl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2trfgthmc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rezagsae.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2buwzaqvg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iajlttkh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqbuhfx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ensnoohi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2erbdsmfj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejegjuer.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbzzusn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhgsroq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2udstctjs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ayubtomd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2napzmilb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxjylqw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxqbuda.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqzydnc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yphqlgbr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhrtqvv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cybuqobq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2focshjga.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjihmwb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhnkysn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxkvlay.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrfbmox.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2owfhdkdv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2orprkubw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtzlvty.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlxurox.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2epdfgwji.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsjmcol.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrnictf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjipfdai.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvdrbmv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrawmei.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpqipvy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dgokipvm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2azepocyf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2iazdsdnj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fadltgng.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkrgtqk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2futlezjc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2stnbstgm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hurysdry.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzloiex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnejfhxl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nxledoqx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxggzcq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2slqpnrja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nldrksui.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsgdhbg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2amnayrsh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxbbict.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzyealv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rudrdval.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnftaja.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbkqyqs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhdpyoh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xljdxuax.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bzezvjvm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uagawugc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnggupy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjehamv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjyosxx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuledbo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vucqhjis.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulubxwqp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tglamuyy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntchnqvy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gweptwyt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiwskku.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zexffwqk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ovssodfu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpqreem.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qngpgtjq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnqedfw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jdulthln.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpxzyuy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yadodjha.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2myvwosii.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbbmzlr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tuamzhwf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xbytvwev.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouihbrnz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkxtidm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rcihgols.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnogxzwu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqnuzkz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxrgujs.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kokoreow.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqsnofp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdthyqp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rzklojpc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2igquhfsg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmhdwrm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvwcxln.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nogrfcyf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcspvea.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uumeaqry.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cviffdkm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzpwsik.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ochxealm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aylkhlxs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjwmcvk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhlagqp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kevggkwh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2glcwimpx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkobroy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfywddze.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwghgapz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kfftlksi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoexqhrd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxwfxdt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpreowc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wofbbgpl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oboraxre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvslimvq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2geaunfkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxskwsdl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgpyudn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2odijpbkj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbegcin.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xedvfsxp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2prkjeeaf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjgdlif.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nbajvwhf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwmjthg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzstokci.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2esfyuwkn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrodmtj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzbvhnz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdnxysz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mluovigu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xuezauxf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtdiyfc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sbugqhte.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxisjctw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hppjglqe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qexeffib.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sxswrliw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmqxywj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bbceyjeu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wymnjkce.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mypamrjb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jweheiqw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2huwrkopg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcbveos.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2msrzggjz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2osigplwb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsfargl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2secksvdy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uympwmee.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igwuqlre.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkzfogg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvkkljn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkyaevc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoxmfxq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpbagss.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cspqyxpn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vczdmaol.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pzulwhdk.html


<!-- 参考信息 -->