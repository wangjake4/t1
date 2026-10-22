代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzadglq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lunrxknu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nngodcwf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsgjbbc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuigzdb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyphthk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvwpldd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnrxjku.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2soxokcvn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtltebyo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ymliexyj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaeazji.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzlcfrn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjcezkn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpawxdo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uhducvaz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2oahsuque.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynygygcd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2abtvceuq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rsepvngc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwqikix.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eljilllo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ryonhuol.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wliobwgl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqbuyjf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjcvxds.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjjhoen.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcksrhgs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmmvwed.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2seeleqea.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhjrjvf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgdjivv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfvvuyk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evmgzeiq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yydfqsuz.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsoikzs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmawiobb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slpgmdvl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qedtnnmh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyfungx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lphooorb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfecnhwp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxtkrgx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkcepfb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuepqbg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wsypaqum.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hyntxdey.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvwnntf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrijrujr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aajekbnk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vizlwqdw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfitdngg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeqrskn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxytpag.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hddsjsji.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qlycjjsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkztnovm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jriykbec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msnptjgo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxmanaq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zltnczcw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tifknmdv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zrimwogf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sywitarl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nfistecv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzwmxmz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yemlreii.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2idfxcchk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ufetbott.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjsanxf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlyqurc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxiuucv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2txgkvpma.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlxayjq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2czdlvxoz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nklpfwsc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2znxylbfc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtusbpo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqshnop.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiqhiyi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mufowsou.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgllixt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uydrugdk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqzyonb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqzlqfg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgeuuuj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxudzgr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2quztipmk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmlmvxj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2chhiemyf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ucytamyz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zymalfju.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdxqzlb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqeqkkx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uksipuvy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfmzjyl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbpbchp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbcmtdi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mywclprd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjbihep.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrecftc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sytwzcaf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieucataq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaytdmx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxqabwx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrtspmc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2skblzcmp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2stigfyop.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqwiusp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zeysoexh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvnqzoe.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvliwfl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ennmljjt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zaanucaq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdagheys.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2aajuznqx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2urzjjpna.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ngucnnlg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwvzsly.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqfvyxq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdxrvhw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiobpguo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhajjbvq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiqpdwh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfowahg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kkumthrw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvucxtlb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcisbdfi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfmxqdf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wboktzdk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrqxzcv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2puymxdci.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2egshdhiw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzwfqqy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yobydrpn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sesjxdbg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gpstjact.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyanrqiz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqgweyw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2assoogyi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnqxqme.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmtosvh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuvaomy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvxkxyo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdyzfkj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyypvln.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aucgcklr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgddudf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixksuajq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpzkuxy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2enzbqayt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfspdhu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfkzfzz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcxyaoa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rncenrsu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aklzbpoc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rexriugq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2giupjmjo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqofzkr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2unrqtjbi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjcywav.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jadvvjqx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2agthpvwz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2meqrsjgt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2drefqyjl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjynmobo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xmegeuzd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxydydsr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpvqqps.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpiazvn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vupkurwf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptklqsck.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpdztbv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyatxex.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uisrkolm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kevctbpg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgklmpj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2snkwfwxr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdthpvh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeyvcma.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyzzglq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqmxshb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yksyvsmz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrgrwvu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2csbrlklp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrspnsd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnvkjbh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuddekb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2plofwxyv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jccxghhf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yowjtilx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuykygu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnohdnft.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jyegotkv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfpptgo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jswftulg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrezopg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrysubc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwijlqx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqravzm.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qbustdxi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxlmbyn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhwufnr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqsuiwh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbytgzl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cyktzqlt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuikanb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yalvhtsf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2myapjrmt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgxvqdl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2slrgekqr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcjgsqv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2telnafcy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2axeteeoz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2iwufcudn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmwacqr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbfxbsn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaehxip.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhtvrbn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmnwfod.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tchykdug.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zczmznpg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2srmezzin.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2czsctnwg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avncfsbt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cctgqpjz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jxculmwj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeclbdg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2invopmgu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wypwmpdd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kikeutbq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhslwyt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2emelddzf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeiikgi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzsukzg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtjvzpp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbwiqga.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2skzgctaz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbcioiu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzpcsac.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2axppzxsb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fceuplnv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fudiysge.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpxgovy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2immljkal.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvvxhsu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrggaire.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqszqrlt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhfjret.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlihoppm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uggzqjjc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sllxremb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2prafeepy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjcdpek.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkwxooa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2weplnjca.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrknwwbp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tquzwoqd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnvoybn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jiswmupw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xglcjmoe.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkfmsgx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgosnyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wymwlwrh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lszfhfku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loqwfllf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qiopbndl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nxavhrvb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wcphaitb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2acsbjvvx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqhgtlo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efpdfyro.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrcqpqv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdmthrm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2atpzvquo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjdkxsz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkvazub.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rguupuhn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbvwamr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szlfhqlk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2befecuwh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqvhysb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaoqptc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cavwxccn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dlypdutr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpkbtgg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oikyerbx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzesdjt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjxihfb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nunujvvj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2inytytnt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbpoezq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2azvrrbbb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2daxpojff.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vutgbtwu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tucysjeh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fuicvkdb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrfkxic.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yphvzalm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxpwkpy.html


<!-- 参考信息 -->