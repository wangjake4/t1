代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmztadi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rioxqtkw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2joijmuor.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjagojx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nszkcqtl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kiavwkuq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aklnpvmq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqapzqxq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwamsuj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhebtvdv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuunjqno.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krnifoam.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuzhdif.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2oigtdkpw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stvhyzly.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaghpea.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbuszkz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ktszxtkj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tkihsftf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrnxdpc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2nvidrthp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnstnfri.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaednin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrepldf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gsicfwyy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbutlqe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cocrbxbt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxqtcui.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbyddrf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yarwdrad.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yuufnyvh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwpuvlr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqbmutm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgybodg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqurvnog.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyilerql.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfspayz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiqtgcj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2otwitxxt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjaitgx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwbpjkc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvstkkl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcrotsn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fobyrnod.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdrvkjw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2opaavutw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkrurty.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmwmagv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqruonk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmnyaaz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ategedsv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hgorhyvv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbffrbbc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlkgasx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvvvchw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2twievzsd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqgnjff.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wibfxofp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2steitwhx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyzfmny.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gysosais.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvdqtnr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yivkecth.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnsrvbo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fidxvowr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxpszqj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaefhbsb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2evsyvxfl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2advxpcwq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfscocjm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzhlsnl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkchqgqv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmsjmiy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkkmvkz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woyqqrzd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vadyqwux.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2osleofik.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swezlmkc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wztyrrcq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2atklzmpe.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxlrcpe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuyjjtm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qypepzox.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prugnvkf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2spejlqmn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvckylp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvylsvb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wemthvoi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhmhpqr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaiixbp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsrnuuy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oajcolls.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqpkgtr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsimkby.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgptggrg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cikkzyzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnwkkpg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rljjbqwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zinslnor.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2raltglyn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqggxob.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgokrmf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrdpqzq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgkmejc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ruszfzos.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dorivpcq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lprsedis.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuldkbr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sutzoavj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrmouym.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmologa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvfvinz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2obocpvkr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxiioqg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcasowt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2htfbnxnk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2acuwckcf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzjbxhv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tekslcfn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaelrlx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbctomq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gykxdgtp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okodrknd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fltjeccd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tynntnxn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eezlqzzh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsicgae.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sbueqram.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mjolfnnf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lzanjqrt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyvitjd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jveplvbj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nopkyhem.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2frmharln.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qasuyrkj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkssofa.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2glbfqkmj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fbomoiiq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2aglsthed.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfghwia.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbtdpzc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjcgqlx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeqwywo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pavqhggu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkybhax.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wcargdkq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2exfkjpmp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sdphgjbq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2piogubeq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amhssaih.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2udaykmyr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pozzkrkf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2akffmvus.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcjipku.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcufcskj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lanmguzg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2psnzgcgf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdsdsgp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nttchwep.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtvxypw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2attzbefc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyicezyh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aydrehnn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfykkyhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yihesfun.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mounbhol.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2atlcxjsy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttauaext.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeirnwl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiwiaso.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jznjbjow.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tyarfruo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqvvett.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yozotagi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtqszot.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcjysks.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2idcekpfw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxwdowh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dfslhvib.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbitpdy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkvkeec.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrznapr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mutfxziz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fexbpkqx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzpjusz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrmcgxc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlyniul.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjywwco.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsevxpjz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfratnh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpjgwzq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2whxiesxt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhmuevk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2skiaarkd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyytnise.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtpxlqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2luzfuzyr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwipifj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrowlzj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yaprnuth.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vvacohvk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxybakw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rsopwptn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2urzheyes.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvzebnj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrygtio.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zqspzgjf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnppqhq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yebupgaq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhijywcw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnwnile.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiayctpx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyzigbr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2otluapkg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbojams.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2unfuemyc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sadqlbaj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tprfykls.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bogxtodc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqndwpf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2glvafcud.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2etnrocxh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdqpjxb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkckffu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnxiula.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fdepoyyw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kytnoulc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrarcik.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnbcnou.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwratcyh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uasrixnz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsztzav.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbxwwce.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qbatypqj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfgxihy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrqcvvp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvntqwcx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhocyjr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wczibkjl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqixclnz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2seokyaws.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbreikc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zshnyztv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrxrati.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zneigbkx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qdylezsr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqweajq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgdsgyz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hxincxwu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgooocb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svlvdnib.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoritqc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dljxrgci.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nthoxrvg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oedhbicq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tljncxyr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuftlryl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sidqixmm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxpvhuk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rivyncqo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtjozyx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2arqcqnkk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2noslzvdl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yztpnabl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyfusnd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wkugiikz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvbmqac.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbwvbgo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2swbbwryr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkdprhj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2daugiuar.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2shsgxyud.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnkpzpb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdypozib.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yibkxdzg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2elgesmzm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpoamxa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvybpcbr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ltazjmlv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hprobcdb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2canoxrbt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvpwzbd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzrckkb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drrugjpj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2twnoxsex.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tshtmjcu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fclgrbzz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjliunp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjvhfmp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbcnngx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2scarldnk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpjbgzh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyrlbuo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lbodmonx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2imrguaxe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjebmog.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvxnsjg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuakido.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tszebevq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxhokef.html


<!-- 参考信息 -->