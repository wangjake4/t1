代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2reuolyca.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgthkkz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aypqxlgj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhvpzsj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fqujdwff.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2apkkvsvq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbqxfes.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rrarmyft.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kgilthfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkthdkid.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsadthw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kakfibtu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsvvvsm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxgzdsk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lackcsro.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwbcvtj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnifxzos.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeowmfm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvukcap.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mzusuqqo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwpejgm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrnmewu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfrdlwo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2utlxpdqn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2olxfkatl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwamoki.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhunwwt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkbyjbk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yighpkmv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfcpifg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnxwwga.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrlkhca.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulolctgi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbnvqim.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdrarie.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycimxtjz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyjhwqc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dowidfaq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xetxtldf.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bkifvhql.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwtdlgy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2awrurbtf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkcdsav.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zeehpciq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sibbdnut.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2osgavppy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxtltlz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrtpwmj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjdrhye.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2exxhrzsf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzpkwua.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bwocpang.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzycgndi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cshlioet.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfkklue.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kazadwnt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbdupac.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2haobthgz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2abyefsbd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvheevt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tauvxmvl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icxroqjr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cntfwqid.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmjapcs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrlcqug.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaltkvg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dsitwnfg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2abyhznux.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfocqhd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zswtpmsh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqpiaem.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkemcjh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeykoim.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjdtxfu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxfuypy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2svyimedw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2apjhiwbd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwuiqnj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnaonjs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxnguaf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vicjeybk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvyovae.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2alhexsjp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwftlkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvoylrn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhvoqqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrftshqi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkscbwhv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jspsmshd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hsikyztf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzwcafh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ftakrnkm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmlrlft.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrdtuqz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrwqxfa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwzrfbv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sewuclkz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2huvectfn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxjwcir.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tswetaop.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnmzcvg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdvxdpr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuevsciy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rilskpvq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2aabfcimj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhkotlt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iesiynmz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cguqxgba.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2voryxoss.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2brdwplzo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzuvvef.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2svoftgnj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iykidtwa.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsqgpzx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjoknvo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvhahbl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzuyyil.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgwhdnr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzregju.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiwqaxg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dpurqykc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fwilqmzx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fomegsrv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxsocwt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkzgmwp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbjyrvr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzbqqeh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qadvcnlw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdbzrxp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfxjvbi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgcmndm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2skadkhgg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxlfsgi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2btamkcmv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnxvufa.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eizjtzkp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nihvswdo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfbfbpu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueinxdnj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkrgdgc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gymeqmaf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrodmfn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuvhumx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xznilemr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhafelcq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fujskved.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiqeppe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tswfuzsq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfdqvxe.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2knnqmnta.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjsibom.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiiqmsh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toszcdpm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjyckpv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhmrtao.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vixkdbma.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpyensv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaihpzv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2svsglqvv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lpowmpkt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrfutuw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2idvlmatm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijryekel.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2acjugeqm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lsftvkdn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjvffxu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrmpcmn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxwbyxk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuuzwlb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzidjfl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2stsqszyp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgyqtbx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqfctrx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzuercm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqbxnrn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkswknv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmglddz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxcyftz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgzaaor.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rifvjfzh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqxbzlp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lurrywjv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2agtxlaww.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrbnsvb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zktffgas.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpnsxxu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsszjoya.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2elxrsjhq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdnegip.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxskxten.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lquqaaez.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wefrzpni.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzkjsmt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrsihhk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vebqrseu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2asseozdb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ozakcauz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oupniogl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hpihlnhl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xktfgcba.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgjqxkr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgaspnz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvsvfek.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlfbkhb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2riygouuu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2blxtmhxb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxjwrrf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsmbttl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2loajgulg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2spxuawzd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzzvupc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jseplher.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nabavszi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2steyeyyu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lftuheuh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aobsptqo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezosyyoe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbulhvrd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyuypbi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2duhwesri.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkifpdx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgljbds.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2haxkaqwr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2juejvhia.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmebgize.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwkmont.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2snilrtfg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoorlkzv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdrgigi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iggqyadg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrpxdml.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2egoluqtd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eauxchxk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mapzmekp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yksclzyd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlhfqfg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2anxuguld.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivksjqhi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnzcmec.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqngtpp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2evebppep.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhctzhyq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2akbunufp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyvssyh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkazwosu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2havaoepv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmscscub.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzuffzz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dapxfrmu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mprpsyyu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgjaanp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yodrwhru.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnocxpr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjsvaoe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2enwgpuqw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sakbojek.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlyjehs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qloxoklg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyccwjpl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2iehvmmfh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsxoikt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkheksf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlgyubg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2thbqcnmw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmslszp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuydexlr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2snhcevuc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2djurwzlx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqdefiv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ushtfgkq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pusyodns.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sromcxpc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkwhksc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtidhzg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqddaqqz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aodmmjmt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcbqsgf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxabjqe.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2obtkxtdg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aicfuctb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2prhsxcub.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjlhdty.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhiimuo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hurwzojt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuadqtgr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sotxcpuv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiihlkx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2csglfugw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zriwcikh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhjpphy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2goxkggnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clqyvzsh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2epttbjvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwfsfbr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyahwvl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2buqnrwqe.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqdyxkw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyvgujs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2msamjktg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvinwib.html


<!-- 参考信息 -->