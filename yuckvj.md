代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfpqvtv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wycshszl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iccmtbby.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpnesqe.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2igythabi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhsycax.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gyydaalv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjekixa.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zaewwxaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwowhuj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emitfhdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svxbwlpa.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjwajkl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaicneh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjbfjtl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpsuowy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnmgojf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikriyimp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpgfpbi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaksmna.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgypyth.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kaopobrv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbmzjdl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmkepel.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2exqmclij.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfgakqu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2agwdhtns.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpzyfoa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdktaim.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpqsekl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kucnixzb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2imujqqmf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhbjpra.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2brmufnhg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfflahug.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzqwpwc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eikmgozo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfurlqmg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsqfufa.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ssetzlau.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2oomqlgow.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucszwkuq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfjgvmv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjzjnqs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgvxedj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpizabcf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2llkztmez.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2erdpjxbv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpxqmpu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvotuks.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqaujnw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dizkwlbb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnymide.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2afskawpw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmnzoxk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2laaqlgpl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxeaoyz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2czczcdba.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2llmuxexe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwqclcw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbiehjr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mirbtnxy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zczozjna.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhsxhrq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2usqlehti.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lougoubn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqlgjod.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tynkzdnq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vabkdjad.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ackreynv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zyktzzxs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtfvudz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2heysodep.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fstrslkb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uaunqbjc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfvwdgz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2molsagbm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2shnpvvom.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnokyzd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpoxzqi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2befshomg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2iopiizdo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrjfxcm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoshbrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfsoveb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvvaasw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fshmijxw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fatuktxz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2titfqthb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aiimecss.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eksmuptu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfwbwtp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2extmrvzd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpetbqd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvitdvu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2oncwdofc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzeadax.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2etrwzaln.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbcslds.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhegdhg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbmbsox.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kslsjhyl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwijbaz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpkltyw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvvacly.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnvyads.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hupizchy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cknzvbbr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqbhanb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2awhrrjtz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqamkozc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kinurlup.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmdazqd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2geuncrui.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gstebdst.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmgyqsi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2djeefkzl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2uortioxz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jeacvsct.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2surbtige.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvtqlkp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2oylajavi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vclpovly.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjxwgqs.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsziynv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2idiyqcwp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yddsmvgh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvuotws.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaalxgt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2szibxsop.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqvddoy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwrbbgh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nflarkkg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ozialmec.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwddabs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfjsodq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezomiqlm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnugtxd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cethjbji.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkjvwmc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoxwgii.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hinvqrpd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vworaskz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuttiaj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2drvfzkpa.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wgafdnlz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfsxqls.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyzcbma.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jwphrrph.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpxjact.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvhxuli.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcivkyme.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xollyaxa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhjsocy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxcpvjx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yljqjvkw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rztoddsl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmcevvj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfalxwfp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxprhdi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqntqdi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzqwhcc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2brnxsqyk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hufoegiv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fepbfvbt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2obozsdpy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqtadaq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvkoldf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2popvteve.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vemoippx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxtwfek.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxtmsyp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2isxehuav.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtxvhwv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiexelk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkpvggy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2emecwrod.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2svwpnrzq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuupret.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoogywz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhrysug.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qilnkrut.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2eskqgkvv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fgluhgct.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qutkltmg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wysrvdem.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvujynf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2shilsmnq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2urvvyfbj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2appyzwlx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xjotwbzd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlnxlut.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmkivvj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmptiwp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkpeqks.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwizkmg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmdwfwx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpzuqeh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2telqewlg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2expcihgf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tbubgtnp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxknmarf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2opuqmqvi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqiqqpn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqrdojq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdgdqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tarhffgq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oigjzpjs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rftoipdb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gioqqxsd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvbxunv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvipozp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2taxybjuc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2viajyltu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfurpzre.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2niuytkvy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2thvwkotd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwsiclh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2slgvbjah.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uivttztw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnvzzwm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnzfzil.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvgmmnh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vblbsvzk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkydkjeq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tacfqaat.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfstklr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azoiompx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2brwcyygu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziejazce.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfgfoir.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zksqzzxj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpwxmwz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iovfhyie.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cysgkcte.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzhtarm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bngvfwqs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfekcxgh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ilihkibn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfnmmpy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2glspcrpl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnatchdw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sdandywt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2avwsyuak.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuiknvv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbotvkn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qkszlfav.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtuuoce.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2apruoaae.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqtxqkh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpsyfrf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdtvgbc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbdgzaf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dorqsgze.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vangtgkz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoobtqy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgvqmmz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dghzcvig.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcszzvsr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lecjnaaq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2grddzvwk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssczkzcd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwaabnt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2chmqrilf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gflyzipy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgvrmsk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlizowmx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzmiukt.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrairbx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxhccye.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnenxtyy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2endptpvw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dmegaixt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouetquyr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bejxcdmw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2togncief.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kzomnxgk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvrwfmk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2bnugrawv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaszwoh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jeazhxet.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2guybsgal.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjkiemj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjfwoot.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yovmlekk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2emofqpqz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2roavjwnq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tfniszff.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpqzhyb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2upsiefsm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvycgquk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsjcwex.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjykcrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bizkctpp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuckpwl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjufdbn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxhauuo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qguyudby.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyygiueb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzoxyxl.html


<!-- 参考信息 -->