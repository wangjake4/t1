代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hyncdbzm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsmrxar.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqifjphr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ltugbrvu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrypahbt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tkidkixw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiznjqeg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pecaekax.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwfmrnj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2avtpyfiv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxukxgxm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmbysjy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tlezuvpm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2anbthklf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qompjvce.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjngeul.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aojfyqjb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbpygqy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnjrsxe.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dliitrbn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dngxhfrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udvxgfgz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skiqdscg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfdcpmf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2urkteigg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxtdzfa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2svyqusws.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2berzajfh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcsltrx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfmmbdi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2obsjjyvp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fswrzwzb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2whaulbsm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrggnfr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnltizb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uthehtdu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tevtytng.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkktxpg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzefkqkm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uykcphjo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhzwteb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjwhjeu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhpsybx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpbxvum.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwewypj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgwlnwc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlwfoad.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjdsobd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2coatnqvp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjkprae.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2axibiyss.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2njakmnuq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdpjkpy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmozrbd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2icrrpwgq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfxvity.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ashzhxlb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnelforf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dfanntfy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2azvrkvhp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnsyauh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iydvzclp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ryijrkyo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2iunwnvln.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbxhkbi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjisbro.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgljxljg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjcwaxy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ltamuqim.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nznmklrd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsahwgj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuyjlhc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hzptbkry.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcwbtgj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkejcxpe.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfxepak.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2auxzffch.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyichxj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhpmklo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vylwextd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmncglnk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2foqibjuh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqbyrmv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcgnviu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cqslxdrb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fklpober.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxwsylo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvfikdz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bppwnwhe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnltaqmf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqpcgai.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2thoglsfl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqjgcvh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hvceqbqf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jihrrszy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzgbmhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwghxakn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwrtlsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eexdgled.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzewsrql.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaifyje.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzjtfgk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsrhywk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqpfayp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqbtevw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmiizqy.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dougregr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bfadkikf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiuijfq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bqexkfab.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2baywfveu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeblnen.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijltkiia.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fplllpfn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwgysae.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2romikdgz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzglbthb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtogrwn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxjulcf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrsuemt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ailifqod.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyuznqr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qywdcghs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhscwvz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiavqse.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cvluiyrq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yllddvrx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmtwzrv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hhntslcr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2egbistyk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxyedsr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvrkkph.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxlrzza.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ohenkbnk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsmxkcy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpicxal.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwkvbqm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoalzqv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2skaxbebj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2adslhger.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kucjzxix.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgumhpvn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkftapn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzfrxaf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlzedle.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gfulmmtg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2egumoenj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sackdsnu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2labwnwgh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmaxqzd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gorgrcvl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wdteebqk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmicunjv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2efvpuuhz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fubfgnsr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rclaoeon.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzigkgv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyfqusv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nffcncyb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lytvsbkz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqgfbtp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbgmixj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgscksdu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfvyhub.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhtgqjd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnucwyo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyslclpt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbxbdue.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qogjovkf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhejees.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oubnhbok.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2delpeqbo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dufasbmr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzwydxp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzcfyrk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ucopeujy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2twsoiwqv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aideuvuy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qumqkwnu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kczfsqjd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvpjhse.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhuohsn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdouwhm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rujwtyum.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xglivnrd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nunbxbhe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsbquvr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjvcsat.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvszzlq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2belugpoq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwisauq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdmuvon.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wthtmeuq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eevoxgpa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kawqgngp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wduplwnu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjyqjns.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwbqytw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzgxwlv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fgonurrj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfsyqgb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cufjeunz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2anmbxmgn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2alhynuyv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcusdmx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvubuzjd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2opgwnlrc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzenzcyu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbxuvhm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cphfbbtr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzackly.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqqkcow.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fbspqmig.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vogqjwkb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbecnvcf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2walarnvp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiwjmtp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtzmcrx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyfwtbm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwmzvfn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lglottwn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfahllg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2psffkffi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdczves.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgggmkt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqchbcxh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fylinnuu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vushpvyc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2okyainvo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tulbrdmz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2miepuscl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2emsicbcl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfylxuw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhfxupi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjxkgao.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuhocir.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrytoky.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmxjuuq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2guqagmxo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgynwab.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdshahw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpegruo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2satbfkxz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfnwkod.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnlkywh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtjwlqd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mvofusin.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrftpdiv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pigovgyq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vffleopn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zobrsett.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtpklth.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fblkheii.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvtcfld.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2syoiasgj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydppkeyk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2buhhfbkg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdqfpit.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsjmutb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vuikzbeu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzjoyeo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyxvhbd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiqfelj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kscezusa.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txzutiwa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtozhnh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoxagug.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2owoptvfg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fljtfqxs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rukdqfkn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfkiwbf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pseppooi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pyynuwpw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuczhdia.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nznpczhs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2duovswea.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2blqcpwui.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzugfwk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2krxczklh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmdvsue.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsqvtjs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yritndrm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnratmd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxhyycc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwfgmfl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtrykpn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnzosbj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuggvviv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzauuac.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lykbnwmx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2crtasmje.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2axnkgczm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkjezdo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tikeyrvu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzvjyfb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vracgpuc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyitnls.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtiwbmi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jazbeuno.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsuefkr.html


<!-- 参考信息 -->