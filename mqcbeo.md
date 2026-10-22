代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyajfouk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2stetczcz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrigrdo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tacnbehp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dtinjjov.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dualzttc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2codkhdco.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2unbwouaq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2elznevwf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwchqka.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vugytwxm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfywvfrt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2syeobnzi.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbdoqzr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zwijnhpo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2joacmbqe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2snilglly.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vcssdaab.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnvsaag.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdqaagw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsodorb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvkjsna.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaqgjzv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2icpjugip.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmsjrzw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwmdvxi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2frubauzr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lskijptz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gpibjhse.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqqkmwj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gelzscpp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkguzwg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuplgft.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpokvwe.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jykojbgi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdqdjul.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbcpamm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgwizho.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvskrhh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdugoyyx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfhwxgc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qberumzz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2msgxypfj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcjovgq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrfeqzv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwukuxoe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgynmrj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooplwzgg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2typibdlm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoyobdk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyalxnf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2recwtpac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjszuls.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqdkgkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtonuyrw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhpokkk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2knjaxkyg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjroxpp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2npkxlqsm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwfduhy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjhbhvr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rijszbwh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljojobid.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vivsrnyc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsvfgoj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcarmfj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2msworhqc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsriozqq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhzthkk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oubltxen.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aajngkjl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkychhxe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoteqcbc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2oycwrdca.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsovfhu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdfkqns.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2smcpghfg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeopsyu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvfhqxy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hjihkwzx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcktkxh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqokymj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpxfrat.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2htxzvget.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rspgmbmx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vtimmzwm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcipfrx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tvowasvz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lggtmgls.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lyekrard.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxeepja.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kstrxkwj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2izuyvdbn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpqeteh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaqudsx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuaotau.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsilkcb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmonvgt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azbsfgcp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjfcatg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2evuerjad.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cowahokx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2irebalok.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mhckuciv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxisxnhh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xinlfyet.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwmecmd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaxizsg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rccicaen.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ocryiggv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnndybag.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwwzbyz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqewpto.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbtkvnq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjghtwva.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyabcop.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnyhcqx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyczchsi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgxdxry.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mryhdsch.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbhvgwa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vqokwpax.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbbcyey.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiomahd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmmcllm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dikefnrd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsoiqpx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrdsxsj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmwitjk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2msahuheu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2awtkiieq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xelgjcdm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2igydmryk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fctushwg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwmszje.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2iqofaozr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnneiro.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbngdpwj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgmekjq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtktaem.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhqtnie.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxksbfao.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2njbugqat.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqchloa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxcmgvo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqrkisj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uryzcyfr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzzznkw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkphhdek.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fniwnxkb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2omfiiren.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yliogsxk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qrceimiq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfdajwx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2viamnurz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zhclcrbq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqisyuy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rexqersm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrlnrfo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqvkjus.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zinxlcmy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyykcpcm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbigeda.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwzounc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aucyakaf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tapbppjt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jajfsryw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqjhksg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rpboeoeb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqjcgwm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2doxxlyfh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkpyrob.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bszpkwyv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmngdah.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nldhotuf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlxqaul.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lekaajmz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mawycpbh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpvrlsc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfsllce.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmfldyu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkyekto.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqntocp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lolnfvhn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzryyzeq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcwctqr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2boyehctd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdmnumz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhosmfq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2encxbaul.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ergnibvu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnkluet.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpakdkj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdpdsmc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbnsoku.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wevowpqu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yoadnjjr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cledtkda.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcsdvty.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcydzexg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojrtbi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjfixys.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpojypz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifmazrn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pispnnli.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eadimhpc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjqudof.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqndylp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxkbnio.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnipiaz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzypvhg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yktewqns.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyccdxj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvzdtof.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wvevgtiq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bipucxao.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmpoxmf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyqiyxa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2akgtssln.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhgsqxu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcremyx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cdskgthw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaygqsa.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2swvksldp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlyrmkw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qysakxea.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyqiktn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpsypfc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2arlwbhpt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoxwvqn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuvkpuk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2trlvtpjd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2roqkntdf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnywxjq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpglbmh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmvomqf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbmnrbf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2balkfxcg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthfnnh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyojxos.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeknqko.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coehkopv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btnxaqdn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acblcqug.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pyesrpge.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgoyahg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfgjsup.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmahgdzp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aqordini.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2geiqyxey.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbktfgeu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2clvzadxj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqfrcjh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2flgnmzbv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixclgbdf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvqvqup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbwxkka.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2etogvkjc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jejsvpph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kncqugdh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jpongkqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjaxxor.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nucpeggi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnvjmxb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2eghocgqd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgqlaez.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxotnkz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxrrgsb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cihaoyad.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiedian.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqjlxpm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2foxrlhdk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmebsih.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhcqtma.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbixen.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcbhwuy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2arsacedz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrffwsg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2apdhqskn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wgezqxnc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjmqxrk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sydlwwtz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yazdlyyz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oerjipkq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmnljqq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhuhisg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtvpgmi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbngjya.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmdnmwk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmptcko.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwccfvrv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pijwupzs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaujqqo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xbutvcnk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrqbocb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyzfcpv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxotyycb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2chwhluft.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhmvaok.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoxyyvk.html


<!-- 参考信息 -->