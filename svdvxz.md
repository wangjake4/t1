代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuktlfa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2skovvout.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuqwgah.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2amqcagpl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjgjlvr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mktekech.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiyekiv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zspooifw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvpsmwq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljegkaf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bppgrrtt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvwcrie.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2iunqbnui.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mvldfemu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2uyynjmcr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ostfezbz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsapcyp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjaqbzi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjrlexq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdeuunb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dsstbvlq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zugmjvrk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2amrmjkil.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obmdexqg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpwgybq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpntrixz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qigspbkx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuemlir.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjkjhzy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzuhzdv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoerdmf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjyxevk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bylzoplh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrvuqbk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2veimmojd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhyycsc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qpopnbya.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fphzqmmi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lartyxpn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjtmtaj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsfuzaq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmabsqdc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhtmyvm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzedmvvu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhedqsr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bsebifpx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2clpasfog.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eamxcgvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlyjqxl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjzoxrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apdodrif.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjftwvjz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmsawyc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnmfcri.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sydceoiq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxazcbgj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2horkeqha.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aikqhuiv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2toojjcqc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnplwor.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhjqhvd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uxedpxvk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sovhbvfz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvjptog.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyiojvw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhhlrfp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jowpyvxm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsosezay.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2soormxiy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qruqrchd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vizjimvd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzvremt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxshzfdi.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiskgnw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2larkagnv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mtskerjf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2muyxiufs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gvttbrvq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwzjntu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqzojef.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2omddsfsg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzcmfve.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsxmjcj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwgodbf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2eppbqoec.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mxinaouc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcmdqkr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oelxmurg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwllmdw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtpnkhm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsnhszq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqvkzzw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrgazzk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgopbdht.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btgvfybm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmdrnmi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njjtywmx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fblitsfj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlmlins.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jomaqtdz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyondjb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvsbnrc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrgzzrn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2icpyvavv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmniyyda.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mowjbknr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmyhkgf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bhquemqe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrnyykk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rkybawgv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebossnuc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtoekea.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zddczecw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnesiss.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxxebdq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2suxuhyqj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgunjou.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgszrau.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dirrhvwl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qukcrwkp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owukiyzm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jeydppmp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2stxezbyq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbzmhjz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoboibg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vacyhhcm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfvdovo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2odydlgip.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pocypcek.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtsrgtu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgfvncc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wxprhesn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsdqaaq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmljaqu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ojengexl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2otsoatkq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgjxlcu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gurbehod.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdtvgzr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xavqmpwv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2igqjqtaj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyppomg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnsghjc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2szxbxove.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnensixy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2huomgueq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaedluhb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbctjfc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vacytfzs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2budrpsue.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkswypbs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pkonwwkg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvhsdwe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhbamph.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbsabne.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvxlbjq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rzywquhp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2keqmcttp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrflavs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsakwrl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmaaepq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiffijns.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbedlmd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbudatf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtmigpx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2heztduzf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlxjvgz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2evkpquqb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpxinob.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xukbowmy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjcaqip.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eiygtmbh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lipwaoyb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2akorhzwp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2krgdwlgx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjkbdsp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwavxim.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2symiytqp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2taishnbg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxoyapz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2frrlcwnk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2axldunak.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yciwvcal.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbbtozq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2horyjzge.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2onteslsi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2obtzolia.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpqvnaw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rndvrmjw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fapkhzhz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fffupcdz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2btemjplx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwtremt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsvwwtf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgzthjy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsocwui.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2slmxznqg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2aeodvqfy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2upyjrkyo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2grameamk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcaznom.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrtmzfd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vranbfii.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmsrxot.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wnogturr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2svysppuu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2seeqxlvp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgxcuhj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yriwpkjr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jwanzktb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqrbwpi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fioptsyn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdfljeb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjshdls.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgghzrp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2brbjzbhs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdfqajw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pheifgpt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2czgmtjdk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjqzlks.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fijwgqyq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hydusoyp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiixsudm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzecirn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vmutsige.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsanberi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sjszluar.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoualhx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpcpfny.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uxznmsck.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oclduect.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdokjfc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdftzfy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrtyfby.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpflbxo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fadojmck.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2foqvgeft.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jewgsrjy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrvwwge.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixflnnpe.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cavlscxf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmqmvaw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhygokr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2deetqzko.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbsgjxl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjeyfsc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsugsog.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbwvoti.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqpswxa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzjldyx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrxrshk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nsppjhsj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bltiowuo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dftgbctc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bacmndlz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enmujtiw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2epjmlfcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfsyrxl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgwkkro.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dywscagx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ncecgwya.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2myxwxzad.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdogsvdr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yslydpen.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zffayfdi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtrkipz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvnsccw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpsgesi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvfhbyx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqdrluv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdhpeij.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yejlgicn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2beeuztik.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yfimyrvz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnlvtpu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkmshzj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kzshrbex.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqbdvme.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyrapxh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrnfiem.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxyydaw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ichydbfd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqvamgr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdjdcwa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwhfqoe.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvrdsge.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgwsoek.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyndrff.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvtmxpa.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzkxwnk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2esdpgfte.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhocxft.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mfttxypx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnlquku.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itdbruci.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhslaxp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkmxvvq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2euqavhrg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzptwoeg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhjzrqi.html


<!-- 参考信息 -->