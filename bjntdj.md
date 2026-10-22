代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bvukpxfa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyhwypn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amysjjva.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hykfipms.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovraofar.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ebghpuea.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmzixjh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfehioc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2omzgjyxr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbwglrd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2krggxlyj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgizzlr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2etdcfjhy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2sblppfsy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2swcyioqe.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzpioyw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vibahxzi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkotpre.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xykoutng.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lcznkoky.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jziyjyvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhmruzw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbibuxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvplrak.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lumzvexq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqanews.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2honnonna.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjroxmen.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xondjkve.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqhqpcm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qoefurze.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuuqhsc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnehbah.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpxvand.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zityxtpg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwcgiln.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyqsytw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2imcrzgvc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqznuzzf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2povtpflz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oocoxykd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2pigdthsd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2msnhoztm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtpjbvb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxlibml.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgfhybn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlwoijd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbmkulj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjhfysc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2whfcrytr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2issddffy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzzidrr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwaueri.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yspyvtrh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tukmtkpi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2opkdhtyg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2phttqdoc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrgzqoo.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmrngys.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyweowl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnppeyh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzwgtjk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qjatjktj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuqwhan.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wirisycp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnwbkqk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjqjumy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeiadyh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmvttlg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuddryx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dklyctdz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmavkyng.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjkwtas.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xupjakch.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdepcsc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isyvvwzd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2znmkvqxi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngohcfbs.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zdowmalw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2afcdrzkc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxuysnw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxocoph.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhtorsu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcodcpop.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rbblqluk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dpppdcwu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcwtqjn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2sgetloto.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nljmoyqb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjqvwfk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2apxqgzhs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kagxafab.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqdzzqj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2iifudphb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsevixg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zqffhytf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juvbvoiw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2evlsdzif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzosgxbr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2okfvggpg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqieiuz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qrruwyir.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2emllaxyb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zymgdkpv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uztvyqwc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqyzays.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lewofiqb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyypzqk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmeqyal.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2emhpdmwn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bivptdab.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifbubgw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2anoxmseb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2veawrqmv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2knjbedwk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twstnhrg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lblfkkjw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpiiwne.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sumuhyzu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2atffwvqk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgezxrrs.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rarxnewm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2evtryjqx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bamdbfei.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2muvupsvn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fqujjvft.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvianmna.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2suyapmhh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2adhvxswm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrtwscy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzjyujd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fshrexzs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zeppgfbb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uosfbmxs.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlbouzf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnvsdqo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtdrgpz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xostyyhg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2abetwlhu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2flazyrix.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jctfajci.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbvnhdx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnszzkut.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dealxayl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyrmyhe.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuyjquw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpbaiku.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gowjuyip.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bblozjsz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuwvwoe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjrmvim.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pnotmxik.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkfmgav.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhodxlz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxaketh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpykqcl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2brgawbcy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wjckgejd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2khpkmgvn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2leegruwi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qpynhvna.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhrbdvv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cogljbnz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeyujgj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjykmjs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvvjswu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtlpgru.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kajbbngj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwvnsdk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2coenfrsf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaltufu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pouyqlxl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbewtgzy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmffpitu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dovxemmz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xumjlzmg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoxwisb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqebsvc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxpkonv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2terpagyj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ndafyvlv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nekyulrp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfampwt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdimywza.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnyqknk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2epayclmm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzevgej.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdiykud.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtayhjng.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wettomej.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuskgus.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hahumtiv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzpgbet.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvryiydw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2myyzsops.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvmjjdk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2prvkjmfo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2falcluah.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ondjgzgi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bkerucar.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kirhfyfo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrveyap.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjtkuwb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrubzvo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmymwedb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gykjsjdx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiyezwk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2drunzdkk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2grrkilzg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yshwylwj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vujqggrq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pttdkgfa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pfginioj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2smlmqxtf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdznzxfy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyxqscb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdssdvxu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiiqnlp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fexfdzcq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdboubl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmlagkd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfhxgqw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpolxgx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmzfpzw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyjzpvb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnauhnr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zegfbesa.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2twaipbtf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzzizdn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvilsyi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vskmlgph.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeickqn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoonlefj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwhncza.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyyqqlw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnzsngq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfeuiou.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzllvlo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2oqovnesn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jitpjmmg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcfnzwe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lylmlnuk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvgvnij.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfxhizd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2inzwwqga.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdldngg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2roulchko.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2afuqiqtl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gcflcggy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2otokhuzu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2miucexvu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtfwipx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2epbvqgqx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqghnzt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nkntmbpy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ettsspdf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwkrloc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cwksguqa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoufxed.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dyypckca.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzrxtbk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zlljkavu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2brhzmbcb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oncpsslz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mofnotyl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aycjqcai.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvaiyiq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcynmct.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjkegrz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnyhlyu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjdkvni.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2womrfopv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ebguocqh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiowofvq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2aujycfyy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtpallh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2znyxbufa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zsncuxqc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxhxeuz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwzxztu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwrpqdz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbkoxes.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjtyule.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cebfhtct.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hewkqxkz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epqevgxs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gchgxgml.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcarifw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xflewgyj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgrgydd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tthulppv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hamzncnx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxzhkiv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgotpke.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2szfonsdb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyutcxxd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdgxsjl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jvosttfu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifljebvh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xaynjkyl.html


<!-- 参考信息 -->