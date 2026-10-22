代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuhmecj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jruxosfp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvbalzw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsomemk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqwvfuy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2brdqjscb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysddyiqd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhqzrpu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2axpojsto.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mikqfcrs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vyabdwtt.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnvqjsj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2orjusrwy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwomgmy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irmemwuz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2awjpxdoo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mrefxiwg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kaokdqou.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjngsbyc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yckusykg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsmzjyt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hknsprhh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbqkjcj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aecpntnp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2prktkdfs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2islsgogm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlnsrri.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnelgfjo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qufieiks.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mskqotxe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwrcgje.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2srvbqivr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyedktc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2udufmdvq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhzoobf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlzcnce.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2shhficfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkhnclo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djdlmqvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgtcmsf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqvvclh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2srfhkrtx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gfztprxn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mumufiwb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xthcuzgb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyjjhbw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vpomgekx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fzouehyz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2csyegyvq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tugoooms.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjexyxk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwadwyg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fijrwvqz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvdgihh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdeihcz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmpcgyu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkxoeou.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2armzhgmt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yasbokue.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2szuhnwlv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2duijmpnn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cajnyhtq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2slwrcgkc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2usfifsqm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqknenk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cosdmgei.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rogurlnk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khoaasru.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gnljttok.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qprpeakj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaewkqz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ddusugzf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxfwdxc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2osofvcya.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcvtjxp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzcqigs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfdxska.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mbojlxge.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmacavk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyywqvj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsppurb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqhzaho.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sayzhmlw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yennzftw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fryzdldv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xezfxska.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ddviqrph.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiyjmbq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyszoaj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmqppdo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gazbrcps.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkjqyjm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnswbbzt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmexrdq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrfiarl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rvayxtja.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oougybne.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2shlosmdi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezartxev.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqppwqgm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmqkuxc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjlurmc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbapzrx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cyemssvq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oedohuqu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2edtaicbb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrceloc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jppcbrku.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqkidzr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dutrnrtg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovufhhod.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkmlntw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhryqlie.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzuscks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2midijfxo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxucmepn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyvweaj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwswwrrf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpewzsl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2espnkhpm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzpwmhj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpkjyrc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfyjeze.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpvarda.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pxozxunj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jeedniyd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gpleuiln.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsurjfk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2alalvbvf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbkzbag.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzasyxyu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfymkpsm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkjgauv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2javuqwqp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oorowcfi.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuiyvgw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxlcwkx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2siyactxv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhxgyql.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzybmts.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyilhki.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaylmsy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdjixvj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfywjeu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnmpzgp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2immdqmrl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpfaiim.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gwywdpxh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjridwq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dauihcnm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhqqtas.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sigaomrr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeurxrw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ncplzhfr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwelrexw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhvebyf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhxmamc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpqtjcq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvqazql.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwujfult.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiibkudw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xxktubbs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkwgqbx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqywmvb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilawinjr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iyprrcjp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbwcxfy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vpafqjct.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkemwzep.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpkjgpb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqxjfxc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2scconxdy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhgfsuc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxlrgax.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfabhfex.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzbvqeq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuliepd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2taxtvhob.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhnfkvm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhihavwg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwweysh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jjktuyak.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hykwkbfk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gstkjgis.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiijiwwt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvwwcba.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgsudne.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2harmbqaj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqapqct.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjlogbx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsezsmj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuwyxfj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2poypzdcj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfgvhul.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfqudcn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2snfgtosp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkwccrg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiczizj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlbkfwl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qogkfbzr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnwxzni.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxicymto.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjzybmr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfohaps.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2glykhuac.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mktpituv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yusoxlkc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hallbivx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrrhvan.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2adarksti.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsyzrcz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pucpsgqi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2etogzyji.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qchvgohh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuocgyak.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2izgclyob.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2unyigfth.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwvubbu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2belgbqxt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiuille.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgydnky.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdsxxri.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2folkvtyb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnxrezx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2voeddsqi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxjgwnj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxfvvkt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjyzbps.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnulsao.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2taowhzmg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnsiayg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xdygknkd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsvuwyp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkrjajm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qguswtjz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2unciozuh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlbbeye.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmrzhdo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnrsmeo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhejyim.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zbownyqk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpiaski.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfojdsb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2thrvydtw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqqrptz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2blfcftpe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmejhzb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eoawoivv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvjssqk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgzgtww.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbammdme.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2punoblno.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwulhtoo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2falcvhwh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uunzictf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyksgvgc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2itezbpbr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlyhdoa.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrhpwpd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwrubpr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvtzhhb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xpooxkmh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmglvqm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkrxubw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2skfrocpo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfakkbxc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsbabzd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oymewcqw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwubglo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ignndtxs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2csdfqjpa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iggmkpha.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htjwpace.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvztlfz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqhzjpq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2izdrufaz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvepozu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2augvsfxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2przdwomu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cvojikew.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2muoyxjcw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsfgjao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sljnrbnn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgrplpv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2egvyqahc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qocaekqn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzzrsly.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkdavry.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzwbmgj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfqixhp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnhmnnx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2awuzwzgd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2puaugmba.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvnqlrv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybngdbiu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnqfwpc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wbetxity.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qithjdsx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vposvhnu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2luiypghd.html


<!-- 参考信息 -->