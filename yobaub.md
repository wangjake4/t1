代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdhirxj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wayubflg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njszzcka.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibctjrbi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxtmpnm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmwckoq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbapqxu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgealcm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2uobyzbzm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjjovzs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyrpsrx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2shpwgstr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kolaxmtu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoiolmy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyohfnvj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2idubvval.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxeqxmu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2euudxibs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpecfllb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcxbhzm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlfgalv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjevkec.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuafwcx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvavibf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2klidnpqy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2htvhdtmu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpmtyty.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wlslpazw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bobehoga.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2elhuwpsd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2okipgfad.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiqjdct.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wongxfev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozobxabu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lonstrod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mphfqrvy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwamrep.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lznkisnf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aunqcdjl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkfxzup.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvntlfz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tchytwiz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqduatd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwwxvek.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmlauax.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlejycn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfarhzh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpacrjnm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xltobddn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqvfzfk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiyqieg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkcgkmu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyihexbd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcgtnrk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2urjwawlb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2whsyygrd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsoyqwd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgzujpk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgxotyo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yurqyqtm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2idgcnvsm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmlpoqk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oiszfmvb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dpikssam.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nfprlesg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hprjwvxk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjrtmgk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2onkknavb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rumekvcx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqquchhw.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jacvmbvi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ishfpqhe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgemmjg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnaetff.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2phyodfts.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ithboshn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpnkhib.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hqspscph.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnbylur.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cidypibi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2npkvdpti.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcbimey.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxnvfui.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkbnoov.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2unlbtuvc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqefuog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmjwcae.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbioxrvh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2sitmysrj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eosvhbcc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhnqoxk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2snaywnjm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvznqie.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsweuyfx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dunthgkt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsxcrib.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xtomgzwe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgdmlci.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nvytpqjs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwqbnnp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxonpgvu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdapixu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2aurtmkeq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msthzhyi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2islhxzce.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfedywk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2usxeigcy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eoayoozs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jigiwcdk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhazakm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmrvdzx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkitkjb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wgknturx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrtdepl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlknusn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlgbdmt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqwazbq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjjdxfx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kztbiypq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbpioae.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2owfmcwez.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2onnabsry.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2llscbbud.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtdbddi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2azaqqeqh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvehkhs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrnwswd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbomxufv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2axtbugfg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqeubns.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lidajzvr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2irooldah.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fapsasdh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2trnbtdcn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuhcfls.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2swglvfum.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yetxgmdr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnkfhky.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lakevmpu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjwcpys.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgixnpp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzerokq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2szwsfxiu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqsnpfs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwlpesd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2clsbrlhf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2njfbqvns.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sovchfxq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2orcdimeo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rujpufqf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2indtaspy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2llotzncm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhvcxks.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2utnjgcpf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dabvnkya.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vafonkdm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjdgksx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxmeybo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iahrqmtr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ethkihfu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjegdgk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiyvgxj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2galnpetu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxyaoyz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvjcvrf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuspmcy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2szvgrfzz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2djsettaj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tggcpzco.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2izgceucg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umgpmkwu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsxmgef.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tncyvkjv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aexqehwm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmzjwkt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvpcunb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srqvdmgt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mivvrcwq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqliakes.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrjlwjj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aemvmnhb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jepvoggv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kckzfvjo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmkbvtn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2snxsawer.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tsylxluf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnydrygv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2boraknkk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxvowvn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2twtkmwyd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kibaotjc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2docebscz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhbzzgi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnujlvu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxvgieg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2thhmfkkg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ahajzmva.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrvupwe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxlwkny.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjgezuv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyspjdq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfvotng.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsqknni.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2blavwsvn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixuokda.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2agpzpgut.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2evhqjyhs.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxluhbg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaybnof.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vppphwqc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cezsaacb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwioise.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoegtvk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xowxhzug.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2smvywcel.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhlhwjb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xioxzixs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnferhgo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxhhtwr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2unvabcef.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbvinti.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyufbznx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjioqkkf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsivqeu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpbclqi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhqdokh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqpuind.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2asoxszeq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kykglgrx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfjnsrd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpsnkuc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2irisjhyj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnxspvx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2scevmzxa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtalycgj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zyruqxse.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfzfgdx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2krfgoqjw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpzoznl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfsbafz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzflradd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsvaqxh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xefowagm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2znvoqxlh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chksfsvl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdrfvxj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjormhy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvbnagv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlothgic.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wlteoccx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhdflfn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qspoyois.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2emtsxxys.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iarsvuaa.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjgyeql.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvsekji.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpgyagd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mozodkxd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cnohgtpk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxkyybl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnilndwy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mztzetnj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzloezar.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2olbevmmt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxvqwcn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2krsmnqnz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aypfcvjd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgdteix.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hboocqvu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwsycxd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsxyosw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jclsnbud.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cadpdbdm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcebnhe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lozsaaap.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nyghsewp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjuxhjp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqrdacg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcjecqm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdmdctz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpssmgo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2peevnnvv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nshbakxh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lcikcjyd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sebehmtk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnzxwef.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2judhydjj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2epoesanq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hkimumpw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2akjyfakw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnfbcos.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkbocfx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqapfna.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjdxwme.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kaakbmcd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvpxskq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxorqyhm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvvvygc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbczbfzw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfntbvle.html


<!-- 参考信息 -->