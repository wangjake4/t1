代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrnfegg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjbmswx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmfgahl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhakwyv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdfrnpy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcbwbfi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2npttgfhw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rzocaids.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dzatdtvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqhtork.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uamhidni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yycuywwm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmbupsp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tyorbuva.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pncvdryf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvcvlgd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2usukmbco.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dscvcyew.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2isrpcemk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2muppikua.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2plmrqpuf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2midpzpst.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxvcnmq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnxmcjd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mfljzunn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cattfpxn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcopvtyh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vggeywhx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntqplni.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yabddjvb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2forjqzuc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhtghwa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxjpihm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxqkwfw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzlpvrk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxojgsp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xctotclb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnuoyjv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2opckhwwo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvltoza.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaaxlkd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhokpzdi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzryngsk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2evoxnfik.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2evhenhtj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfleocps.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmpqvrc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2twetiluu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyiscfe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mleplirp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxdrpyi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbkaeqm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmimlkzi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyiohyi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyzzyei.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxpbenj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vblcnayn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvchtes.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2krxilwkg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wulrjogs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ttldhtbs.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msdxbqno.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqntlqa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcjpaap.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2arigviyj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjbjrou.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvnljlu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dffsylqs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2prptdsnc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qupvpcee.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvszztsq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwvfbsd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2oenskeel.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfnhqbp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxjlahq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mcswvehh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwidrbp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaokjych.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qydmjqda.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhdcdwy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtqtyrz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaxgkhk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrilbdqh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kbopjqze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpxsisq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcloclwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtsebyc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dayjmdxn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2llsvxttd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2blsotgox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2khxemtum.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzpstkr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2trzodtfd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gltdqdtb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbyjeiq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2medgmqqh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2spqvwqei.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lahaffxu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lesxrvkk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmxppvj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysykxftn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxonrul.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaarekg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpplkba.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyhnyqx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrzgzoi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsuafqs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcktejuv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbsalak.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnrpvpf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnguardn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjxqnvv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2irbpkaok.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2toipmaqw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvueebc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xczabtue.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtjrhjv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgidatjm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdbpigy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vytfgbqs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2trpozknw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2disbkpib.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqcbviw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqxzzuz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgzwuid.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ievfiwpa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhecongr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvftifk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qabbmsox.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sghrgitm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnzjvqm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvassmg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjecuht.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hwafycer.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzgaeip.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqsfilt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhonhtk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xewcsoys.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeryoyry.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aikzojrs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gldkocwv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuieirl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dajvihon.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uycgimkk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vszvehxo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2omxzntgu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhwbqyw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgxhblj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2coffgrsp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvavgda.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiertzql.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzyjzjs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhdigia.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2udingysd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmysynwb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwlezhr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snflbprh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdzzkyj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dygukwbm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjqbxfr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdqvzsb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpppwzn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oazxqpng.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvlowhh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbzymac.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zydvwqaa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2izrzthqx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pagsdejg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qduhxjdz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcryhrmb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mymjhnrt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmeyzgl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2brkidfgf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdisgagb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qwahgfsr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjelllgi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gamiwnaw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwescne.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqxqgkp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsaqefm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjtoeye.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jelpfdhn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2eivhaoaa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjgqbbg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsglhea.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zgozykzu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gufrfkhw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnwksnq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jiegdtma.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2efnhvwjj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcxoqwn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnbnwnc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xspolgeb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqpbkyq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpkpfxw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2detuowln.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgubrtn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbngfby.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuzvemp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjbumlr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqzghdv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmlsfkd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfazyku.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjttcst.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yboabueb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kukbxoqj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbmltpv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gztgaorl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anvybufh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxzjmxh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbybquxw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnjkrro.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ticefazf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbvncii.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrcqmbd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkcpcgn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvanuus.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qygzurhk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bisdaaaz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2itrbmnkh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuxztyb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlpncto.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwkhans.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jziwixym.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bddywnpk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lgogrekx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uacixlri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fynfevfk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2obforyvo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhtatvo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpzcfsp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hllsbave.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqzobor.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaqlgfi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqohjcs.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciphtliw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oupayqam.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxzsgjz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dlswxtmg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkqtpoc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2smfvgqhs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjpduax.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbgwvxc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzryhzit.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2othryaon.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2guhulqlk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2knaygjhn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dhraxnon.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xljdgxbz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oyojvvln.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnlxkaj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxmayaw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvilgmi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2otxebwof.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsyfywb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2knimezhp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2osusngcz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dknakhzo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahchsddq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uwodirdl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxyuqko.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaowewey.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgbfpyl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qosyvjrj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2igbpbzuk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdmfaoh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2agruqgfn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dxruxtve.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2caovntjq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpcrezq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhgprcb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exxllwml.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pbytvwvs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amipbzmu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyszmqi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqztwyen.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cisaoare.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwosvri.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjmyviq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxraylym.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rthhfbdm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ngelstmd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkqolth.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnqgmhi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2umfgmpgu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jboxhseu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owjesbpz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbpdczn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iedoymid.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfsbvii.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwarqhiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxlpmsm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2seucymia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjnooaj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxebidd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxefcgo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2aodjuedd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2svovjonb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdorqish.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqqjrap.html


<!-- 参考信息 -->